# Changes done to deploy Staging environment

1. make elasticsearch non va perche' elasticsearch e' stato messo esternamente
2. Cambiato il REGISTRY nel Makefile da ```nexus.default.svc.cluster.local:5000``` a ```nexus.teamdigitale.test```
3. Modificato l'indirizzo delle images degli yaml nella cartella /kubernetes/deployment 
    da ```10.98.74.120:5000``` a```nexus.teamdigitale.test```