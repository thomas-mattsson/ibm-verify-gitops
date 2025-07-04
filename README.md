# ibm-verify-gitops

GitOps for IBM Verify

## Clean-up LDAP entries

Script to remove LDAP entries added by runtime registration

```bash
oc exec -n ibm-verify -i isvd-isvd-master-pvc -- bash -s < scripts/remove_ldap_entries.sh
```
