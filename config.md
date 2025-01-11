<h2>Configurar o terminal</h2>
<h3>Install App</h3>
<a href="https://git-scm.com/downloads/win" target="_blank">
  <img src="https://img.shields.io/badge/-Git-05122A?&logo=git"/>
</a>
<a href="https://www.nerdfonts.com/font-downloads" target="_blank">
  <img src="https://img.shields.io/badge/-Nerd Font-05122A?&logo=symfony&logoColor=FF79C6"/>
</a>
<a href="settings.json" target="_blank">
  <img src="https://img.shields.io/badge/-Settings Terminal-05122A?&logo=gnometerminal&logoColor=44475A"/>
</a>

<h3>Install oh-my-posh</h3>
<li>Execute o PowerShell em modo adm</li>

```pwsh
 
Set-ExecutionPolicy Bypass -Scope Process -Force; Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://ohmyposh.dev/install.ps1'))
 
```
<li>Editar o aquivo de .bashrc</li>

```javascript
 
eval "$(oh-my-posh init bash --config ~/AppData/Local/Programs/oh-my-posh/themes/jblab_2021.omp.json)"
 
```


<h2>Configurar o VSCode</h2>
<h3>Install Extension</h3>

- Cody AI
- Docker
- Material Icon Theme
- Portuguese (Brazil)
- Prisma


<a href="https://fonts.google.com/specimen/Fira+Code" target="_blank">
  <img src="https://img.shields.io/badge/-Fira Code-05122A?&logo=symfony&logoColor=FF79C6"/>
</a>

```Javascript
{
    "editor.fontFamily": "Fira Code",
    "editor.fontSize": 14,
    "editor.fontLigatures": true,
    "files.autoSave": "afterDelay",
} 
```


