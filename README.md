# Mss
Matrix-synapse-server


创建管理员

docker exec -it synapse register_new_matrix_user http://localhost:8008 -c /data/homeserver.yaml -a

//////////////////////////////////////////////

docker exec -it synapse register_new_matrix_user -c /data/homeserver.yaml http://localhost:8008
