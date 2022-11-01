FROM fedora:36

RUN sudo dnf install -y dnf-plugins-core 
RUN sudo dnf config-manager --add-repo https://rpm.releases.hashicorp.com/fedora/hashicorp.repo 
RUN sudo dnf install -y vault 
		
