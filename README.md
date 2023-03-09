# python-openai
This Python code utilizes the OpenAI API to generate a Python script based on a prompt provided as a command-line argument.

Example:
python3 python-openai.py "migrate any website + mariadb database from one virtual machine to another using ssh and rsync, for paths and credentials use variables in the beginning of the script, first do the database dump into website root folder to rsync it together with the web and then import in target" "migrate-website.py"
