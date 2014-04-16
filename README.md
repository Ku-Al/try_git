apt-get install python-virtualenv, python-pip
pip install virtualenvwrapper


vim .bashrs 
 export WORKON_HOME=$HOME/.virtualenvs
 source /usr/local/bin/virtualenvwrapper.sh
 
 
mkvirtualenv xxx
workon xxx

lsvirtualenv                           - вывести список доступных виртуальных окружений
rmvirtualenv ххх      - удалить виртуальное окружение "env_name1"
deactivate                              - выйти из текущего виртуального окружения

git init xxx

git config --global user.name " "
git config --global user.email "Ku-Al"

