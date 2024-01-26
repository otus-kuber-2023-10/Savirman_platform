# ReplicaSet

Обновление ReplicaSet не повлекло обновление запущенных под, так как поды являются независимыми единицами, и их количество при этом не изменилось. Если бы было изменено и количество реплик, то новые поды создавались бы уже из новых образов. Кроме того, поды могут выполнять важные задачи, которые могут прерваться при удалении старых подов и создании новых. ReplicaSet влияет только на вновь создаваемые поды и не следит за уже созданными подами.

# Deployment

Создал Deployment paymentservice-deployment, paymentservice-deployment-bg, paymentservice-deployment-reverse, frontend-deployment. Применил Probes.

# DaemonSet

Создал Daemonset node-exporter. Изменил Daemonset так, чтобы он применился ко всем нодам.
