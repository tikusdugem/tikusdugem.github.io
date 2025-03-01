# GOALS!

**[Live Preview](http://rothem.info/)**

## Make User Profile Website

- For the design I am using this template https://startbootstrap.com/template-overviews/resume/
- Further information for the template https://github.com/BlackrockDigital/startbootstrap-resume

## Hosting By Github-Pages

- Create a new repository with your github username. Example: ***username*.github.io**
- Push your template or file index.html to your repository
- Open your browser and fire! **https://*username*.github.io**
- Further information for hosting in github-pages https://pages.github.com

## Using Custom URL

- Add CNAME file to your root folder
- Save CNAME file with your custom url
    ```
    example.com
    www.example.com
    ```
- Push to your repository
- Make sure you already have domain. Configure your DNS domain with your custom url

    Name | Type | Data
    --- | --- | ---
    www | CNAME | *username*.github.io
    @ | A | 185.199.108.153
    @ | A | 185.199.109.153
    @ | A | 185.199.110.153
    @ | A | 185.199.111.153

- Further information for using custom URL https://help.github.com/articles/using-a-custom-domain-with-github-pages/


# USAGE

## Development
- Clone this repo
    ```
    git clone https://github.com/tikusdugem/tikusdugem.github.io
    ```
- Move to the directory repo
    ```
    cd tikusdugem.github.io
    ```
- Make sure your Node Version start with === 10 (TODO: Update Project)
    ```
    node -v
    ```
- Run NPM
    ```
    npm install
    ```
- Make sure you already have [gulp](https://gulpjs.com/) on global
    ```
    gulp dev
    ```