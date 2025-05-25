kubectl taint nodes foo key=value:effect

Persistent Volume PLUS Node Affinity 

search: volume
strg+F: kind: persis

The problem here is that you DO NOT find node affinity yaml for a persistent volume in the persistent volumes section or if you search for nodeAffinity

Pods plus Node Affinity 

search: Node Affinity
strg+F: kind: pod

This should be enough entry for Affinity and also Anti Affinity. 

Deployment plus Node Affinity
search: Node Affinity 
strg+F: kind: deploy
