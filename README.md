# FILE CLONING COMMAND
pip uninstall requests chardet urllib3 idna certifi -y;pip install chardet urllib3 idna certifi requests
rm -rf FILEX
git clone https://github.com/AHMADOAFRIDI/FILEX
cd FILEX
python FILE.py
