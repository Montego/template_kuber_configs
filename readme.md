                                For deployment
**Create** : kubectl create -f deployment-definition.yml

**Create with saving change-cause** : kubectl create -f deployment-definition.yml --record

**Get** : kubectl get deployments

**Update** : kubectl apply -f deployment-definition.yml

**Status** : kubectl rollout status deployment/myapp-deployment

**Rollback** : kubectl rollout undo deployment/myapp-deployment
                                
                                 For service
f 