Don't forget to add the namespaces:

```
helm install everest \
percona/everest-db-namespace \
--create-namespace \
--namespace <name of namespace>
```

or in the case of Epinio default:
```
helm install everest \
percona/everest-db-namespace \
--create-namespace \
--namespace workspace
```