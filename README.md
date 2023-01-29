# Atrob
Add some validation attributes to your asp.net core project and enjoy

[![Nuget](https://img.shields.io/nuget/v/Atrob?logo=nuget&style=for-the-badge&color=00467C&labelColor=1c1917)](https://www.nuget.org/packages/Atrob)

>This Library Is Currently A Preview Version, If You Find Any Bugs, Please Report Them. Also Let Me Know If You Have Any Comments

**Pull requests are welcome**

## Install via NuGet
To install Atrob, run the following command in the Package Manager Console :
```powershell
PM> Install-Package Atrob
```
<<<<<<< HEAD
## [List of attributes](/docs/Attributes.md " List of attributes") 🔗
=======
##[ List of attributes](/docs/Attributes " List of attributes") 🔗
>>>>>>> 8d2cdeb (Add README and docs)

## Client Validation
Some attributes include user side validation, follow the steps below to add it
> In **api** projects, client-side validation are not activated and will have no overhead

1. download [atob.js](/ClientJs/Atrob.js "atob.js") and add to project
2. Then add it after the jquery-validation-unobtrusive 
> I recommend adding it inside _ValidationScriptsPartial.cshtml

```
<script src="~/js/Atrob.js"></script>
```
<<<<<<< HEAD
Adding client-side validations is done!
=======
Adding client-side validations is done!
>>>>>>> 8d2cdeb (Add README and docs)
