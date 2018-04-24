# Backend Django project structure

### Project structure

    {project_name}/
        .gitignore
        requirements.txt
        Dockerfile
        docker-compose.yml
        config/
            nginx/
            uwsgi/
            supervisor/
            docker/
            ...
        tools/
            sql/
            docker/
            ...
        var/
            static/
            media/
            log/
            venv/
            ...
        {project_name}/
            manage.py
            static/
            templates/
            {project_name}/
                uwsgi.py
                urls.py
                apps/
                    app1/
                        migrations/
                        admin.py
                        models.py
                        views.py
                    app2/
                        migrations/
                        admin.py
                        models.py
                        serialisers.py
                settings/
                    __init__.py
                    common.py
                    local.py
                    local-sample.py
