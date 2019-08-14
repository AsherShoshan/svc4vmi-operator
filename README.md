# cnv-svc4vmi-operator
expose a service for VirtualMachineInstance (CNV, kubevirt)


Install
-------
export TARGET_NAMESPACE=your-target-namespace     (default to openshift-operators)

curl -k https://raw.githubusercontent.com/AsherShoshan/svc4vmi-operator/master/deploy.sh | bash

Uninstall
---------
export TARGET_NAMESPACE=your-target-namespace     (default to openshift-operators)

curl -k https://raw.githubusercontent.com/AsherShoshan/svc4vmi-operator/master/undeploy.sh | bash
