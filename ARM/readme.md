#To quick off this deployment, the parameter file must be updated with your values.

az group deployment create --template-file aks-internal-mi.json --parameters parameters-mi-basic-sample.json -g "yourRGName"
