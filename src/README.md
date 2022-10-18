# Tutoriais básicos
## Tutorial Packages
* Pastas
  * my_py_pkg/
  * my_cpp_pkg/
* Teste cpp
  * ```ros2 run my_package my_cpp_pkg```
* Teste py
  * ```ros2 run my_package my_py_pkg```
## Tutorial Publisher - Subscriber
* Pastas
  * cpp_pubsub/
  * py_pubsub/
* Teste cpp
  * ```ros2 run cpp_pubsub talker```
  * ```ros2 run cpp_pubsub listener```
* Teste py
  * ```ros2 run py_pubsub talker```
  * ```ros2 run py_pubsub listener```
## Tutorial Service - Client
* Pastas
  * cpp_srvcli/
  * py_srvcli/
* Teste cpp
  * ```ros2 run cpp_srvcli server```
  * ```ros2 run cpp_srvcli client```
* Teste py
  * ```ros2 run py_srvcli server```
  * ```ros2 run py_srvcli client```
## Tutorial Custom Types
### Custom .msg - .srv
* Pasta
  * tutorial_interfaces/
* Teste cpp
  * ```ros2 run cpp_srvcli server```
  * ```ros2 run cpp_srvcli client 2 3 1```
* Teste py
  * ```ros2 run py_srvcli server```
  * ```ros2 run py_srvcli client 2 3 1```
### Custom Interface
* Pasta
  * more_interfaces/
* Teste
  * ```ros2 run more_interfaces publish_address_book```
  * ```ros2 topic echo /address_book```
## Custom paramters
* Pasta
  * cpp_parameters/
  * python_parameters/
* Teste cpp
  * ```ros2 launch cpp_parameters cpp_parameters_launch.py```
  * ```ros2 run cpp_parameters parameter_node```
* Teste py
  * ```ros2 launch python_parameters python_parameters_launch.py```
  * ```ros2 run python_parameters parameter_node```
## Plugins
* Pasta 
  * polygon_base
  * polygon_plugins
* Teste
  * ```ros2 run polygon_base area_node```

# Tutoriais Intermediários
## Criando uma Ação
* 

## Um servidor de uma Ação
* 

## Multiplos nós em um único processo
* 

## Launch
* 

## TF2
* 

## Testando
* 

## URDF
* 
  
