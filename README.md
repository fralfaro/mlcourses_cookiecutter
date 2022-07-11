# Machine Learning Courses - CookieCutter
Cursos de Machine Learning generados de manera automática 
con [Google Colab](https://colab.research.google.com/?hl=en), [Mkdocs](https://www.mkdocs.org/) y [Github Actions](https://github.com/features/actions) mediante **CookieCutter**.

## Creación del proyecto

1. Crear un proyecto en Github (público).
2. Usar [Cookiecutter](https://cookiecutter.readthedocs.io/en/stable/index.html) para crear el proyecto:

    ```
    python -m cookiecutter https://github.com/fralfaro/mlcourses_cookiecutter
    ```

    donde los parámetros asignados por consola son:

     * `full_name`: nombre completo .
     * `email`: email personal.
     * `project_name`: nombre del proyecto .
     * `project_description`: descripción del proyecto .
     * `year`: año actual.
     * `github_user`: usuario de github.
     * `linkedin_user`: usuario de linkedin.

    >    **Nota**: el nombre del proyecto debe coincidir con el nombre asignado en el punto 1.

3. Para agregar un remoto nuevo, utiliza el comando git remote add en la terminal, en el directorio en el cual está almacenado tu repositorio.

   El comando `git remote add` toma dos argumentos:

    * Un nombre remoto, por ejemplo, `origin`
    * Una URL remota, por ejemplo, https://github.com/user/repo.git

   Por ejemplo:

    ```
    $ git remote add origin https://github.com/user/repo.git
    # Set a new remote

    $ git remote -v
    # Verify new remote
    > origin  https://github.com/user/repo.git (fetch)
    > origin  https://github.com/user/repo.git (push)
    ```
   >    **Nota**: para más detalle consultar el siguiente [link](https://docs.github.com/es/get-started/getting-started-with-git/managing-remote-repositories).