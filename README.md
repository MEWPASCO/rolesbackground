# Contact me through Discord

[![Discord](https://img.shields.io/discord/1196075698301968455?style=social&logo=discord&label=ΛVΛRIΛ)](https://discord.gg/avia)

# Roles Background

Gives Roles on a Userprofile a background to the box, effectively making the colors & roles "more" distinct from each other

### Example
![image](https://github.com/user-attachments/assets/c3b43d8a-76fa-4284-82c8-602b8b03cb75)

# Installing it to your Discord

Use [Vencord](https://github.com/Vendicated/Vencord) or an equivalent client mod that allows you to install themes.

Paste the following link into your online theme links:
```
https://raw.githubusercontent.com/MEWPASCO/rolesbackground/refs/heads/main/background
```

### Other method 
Paste this into your QuickCSS (Or any non-Vencord equivalent) to make it a little easier:
> [!NOTE]
> Must be at the top of your code, @import does not work otherwise - this is for all the @import code you might have - put it to the top!  
```
/* RolesBackground */
@import url('https://raw.githubusercontent.com/MEWPASCO/rolesbackground/refs/heads/main/background');
```

Alternatively if your client does not support online themes you can download the theme file found in this repository and put it into your theme folder.

# Configuration

Put this into your QuickCSS (Or any non-Vencord equivalent) to configure some behavior of this theme:
> [!NOTE]
> Values over 50% make it progressively harder to read the text!
```css
/* RolesBackground */
:root {
  --opacity-role-design: 50!important;
}
```
