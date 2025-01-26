





venv:
	if [ -d "~/venv_{{ cookiecutter.repo_name }}" ]; then \
        echo "venv_found"; \
	else 
		python3.11 -m venv venv_{{ cookiecutter.repo_name }}
    fi	

requirements: requirements.txt:
	venv_{{cookiecutter.repo_name}}/bin/pip.exe install -r requirements.txt
