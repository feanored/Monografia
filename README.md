# Monografia

Texto do meu TCC em Matemática Aplicada no IME-USP  


## Link

https://github.com/ccsl-usp/modelo-latex  


## Instalação

For Debian/ubuntu systems (use latexmk para produzir o tese.pdf):

*sudo apt install texlive-base texlive-latex-base texlive-fonts-recommended texlive-generic-recommended texlive-latex-recommended texlive-latex-extra texlive-fonts-extra texlive-bibtex-extra texlive-lang-portuguese texlive-lang-english lmodern biber latexmk*

For Red Hat/CentOS systems (use make para produzir o tese.pdf):

*sudo rpm --import "https://keyserver.ubuntu.com/pks/lookup?op=get&search=0xD6BC243565B2087BC3F897C9277A7293F59E4889"*  
*sudo curl -L -o /etc/yum.repos.d/miktex.repo https://miktex.org/download/centos/8/miktex.repo*  
*sudo dnf update*  
*sudo dnf install miktex*  
*miktexsetup finish*  
*initexmf --set-config-value [MPM]AutoInstall=1*  
*sudo yum install libnsl*
