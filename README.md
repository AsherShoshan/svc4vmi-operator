# cnv-svc4vmi-operator
expose a service for VirtualMachineInstance (CNV, kubevirt)


Installation
------------
export TARGET_NAMESPACE=your-target-namespace     (default to openshift-operators)

curl -k https://raw.githubusercontent.com/AsherShoshan/cust0-pvc-operator/master/deploy.sh | bash

Uinstall
--------
export TARGET_NAMESPACE=your-target-namespace     (default to openshift-operators)

curl -k https://raw.githubusercontent.com/AsherShoshan/cust0-pvc-operator/master/undeploy.sh | bash
