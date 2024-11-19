# alias_for_Kubernetes
1. Open the ~/.bashrc file in the editor:
   # vi ~/.bashrc

3. Scroll to the end of the file using the arrow keys.

4. Press i to enter insert mode in vi.

5. Paste the list of aliases

6. Reload the ~/.bashrc to apply the changes:
   # source ~/.bashrc
 
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
