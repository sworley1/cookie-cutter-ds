





venv:
	if [ -d "~/{{ venv_cookiecutter.repo_name }}" ]; then \
        echo "venv_found"; \
	else 
		mkdir {{ venv_cookiecutter.repo_name }}
    fi	

requirements: requirements.txt:
	{{venv_cookiecutter.repo_name}}/bin/pip.exe install -r requirements.txt