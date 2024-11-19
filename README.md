# alias_for_Kubernetes
1. vi ~/.bashrc  
2. add list to the end of the page
3. source ~/.bashrc 

# User specific aliases and functions
    alias k='kubectl'
    alias kg='kubectl get' 
    alias kge='kubectl get events'
    alias kdp='kubectl describe pod'
    alias kds='kubectl describe service'
    alias kdd='kubectl describe desployment'
    alias kgh='kubectl get hpa'
    alias ktp='kubectl top pods'
    alias kgrs='kubectl get rs'
    alias kgp='kubectl get pods'
    alias kgpv='kubectl get persistentvolumes'
    alias kgpvc='kubectl get persistentvolumeclaim'
    alias kgsc='kubectl get sc'
    alias kgi='kubectl get ingress'
    alias kgd='kubectl get deploy'
    alias kgs='kubectl get service'
    alias ka='kubectl apply -f'
    alias kd='kubectl describe'
    alias kgn='kubectl get nodes'
    alias kdi='kubectl describe ingress'
    alias kgns='kubectl get ns'
    alias kdel='kubectl delete'
    alias kinfo='kubectl cluster-info'
    alias kgc='kubectl get configmaps'
    alias kgsec='kubectl get secrets'
    alias kgsa='kubectl get serviceaccounts'
    alias kgds='kubectl get ds'
