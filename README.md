# Template for BESSER-PEARL Organization

This Github template provides a collection of base files for the configuration and creation of repositories in the BESSER-PEARL organization.

## Steps to create and customize your repo

1. Create a new repository in the BESSER-PEARL GitHub organization using this template. You have to set the `Repository template` field to `BESSER-PEARL/template`.

    ![Repositoy Template](docs/images/repositoryTemplate.png)

2. Edit the project description. You can do it in the `About` tab of the repository (click on the gear icon). Try to create a descriptive entry for the project, and include at least three tags. If the project has a website, indicate also the URL.

    ![Project Description](docs/images/about.png)

3. In the preovious menu, decide also whether your repository page should include `Releases`, `Packages` or `Environments` tabs. In case of doubt, remove them

4. Review the contributing guidelines in `CONTIBUTING.md`. Please, read carefully the provided template and adapt to your repository.

5. Review the code of conduct in `CODE_OF_CONDUCT.md`. Please, read carefully the provided template and adapt to your repository.

6. Review the governance model in `GOVERNANCE.md`. Please, read carefully the provided template and adapt to your repository.

7. Check that the proposed license matches with your project. The template includes the MIT license (the standard license for public repositories of the BESSER-PEARL organization), but you can change it to any other license. You can find a list of licenses in [Choose a License](https://choosealicense.com/).

8. Decide whether your project will use issues, projects, and wikis. You can de/activate them in the `Settings` tab of the repository.

9. Review the templates proposed for issues and pull requests. You can find them in the `.github` folder. Remove the folder if you do not plan to use them. 

    9.1. Issue templates are located in `.github/ISSUE_TEMPLATE`. You can find a template for proposals and questions, but you can modify or create new ones. You can find more information in [About issue and pull request templates](https://help.github.com/en/github/building-a-strong-community/about-issue-and-pull-request-templates). 

    9.2. Pull request template is located in `.github`. You can find more information in [About issue and pull request templates](https://help.github.com/en/github/building-a-strong-community/about-issue-and-pull-request-templates).

10. If your work is related to a paper, and you want to facilitate its citation, review the `CITATION.cff` file. The provided template will help to fill the gaps, but if you need more help, you can find more information in [Citation File Format](https://citation-file-format.github.io/). Otherwise, just remove the file.

11. Modify the `README.md` file. Once you have done the previous steps, write the README file for your project.

12. This template also provides the base files to deploy the repository documentation using [readthedocs](https://docs.readthedocs.io/en/stable/index.html) tool. In the `docs` folder you can find all the Sphinx documentation sources. For more information on how to connect your repository, import the project, and deploy the documentation in readthedocs, you can follow this [tutorial](https://docs.readthedocs.io/en/stable/tutorial/index.html). Finally, you should get the basic template for BESSER-PEARL projects. You can modify the documentation for your project.

    ![readthedocs template](docs/images/repositoryTemplate.png)

If you do not plan to use redthedocs, remove the `docs` folder and the `.readthedocs.yaml` file.