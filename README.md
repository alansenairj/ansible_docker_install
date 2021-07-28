# ansible_docker_install - automação para a VM Vagrant da Disciplina New-Generation Virtualization

# Playbook para automatizar a instalação do Docker em uma VM vagrant. 

Playbook simples, sem roles ou templates. 

- Salva o nome da versao e salva em uma varivel
- Ajusta o Timezone
- Gera Chave SSH
- Ajusta o Arquivo de Configuração do Ansible 
- Instala Pacotes da dependência do docker
- Adiciona a GPG key do Docker
- Adiciona o repositorio do Docker e usando a versão registrada
- Instala o Docker
- Adiciona o User docker ao grupo vagrant
- Inicia o Docker Service Daemon

Clonar o repositório, entrar no repositório extaído e executar "vagrant up" 

Dica no Linux - instalar pacote unzip e digitar " unzip ansible_docker_install.zip

