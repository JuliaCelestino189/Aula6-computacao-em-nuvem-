
# Aula 6 — ConfigMaps e Persistência de Dados

Nesta aula, foi criada uma página HTML utilizando um ConfigMap, que armazenou o conteúdo exibido pelo servidor Nginx. Em seguida, foram criados um PersistentVolume (PV) e um PersistentVolumeClaim (PVC) para disponibilizar armazenamento persistente no Kubernetes.

Um Pod utilizou esse volume para criar arquivos. Após sua exclusão, outros Pods foram criados e conseguiram acessar os mesmos arquivos, demonstrando que os dados permaneceram armazenados independentemente do ciclo de vida dos Pods.

Por fim, os recursos utilizados foram excluídos, encerrando a prática.
