Vagrant.configure("2") do |config|
  # Configuración del Servidor
  config.vm.define :servidor do |servidor|
    servidor.vm.box = "bento/ubuntu-22.04"
  # Configuración IP  
    servidor.vm.network :private_network, ip: "172.16.1.3"
    servidor.vm.hostname = "servidor"
  end

  # Configuración del Cliente
  config.vm.define :cliente do |cliente|
    cliente.vm.box = "bento/ubuntu-22.04"
  # Configuración IP  
    cliente.vm.network :private_network, ip: "172.16.1.2"
    cliente.vm.hostname = "cliente"
  end
end