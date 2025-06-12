<%*  
let name = await tp.system.prompt("Enter creature name");  
let cr = await tp.system.prompt("Enter challenge rating");  
let sizeType = await tp.system.prompt("Enter Size/Type");  
let alignment = await tp.system.prompt("Enter Alignment");  
let initiative = await tp.system.prompt("Enter Initiative");  
let senses = await tp.system.prompt("Enter Senses");  
let hp = await tp.system.prompt("HP");  
let AC = await tp.system.prompt("AC");  
let AC_desc = await tp.system.prompt("AC desc"); 
let AC_touch = await tp.system.prompt("Touch AC");
let AC_flatfooted = await tp.system.prompt("Flat-Footed AC");
let walk = await tp.system.prompt("walk speed");
let bab = await tp.system.prompt("Base attack bonus");
let grapple = await tp.system.prompt("grapple bonus");
let reach = parseInt(await tp.system.prompt("reach"));

let callout = `> [!statblock] ${name} ${cr}  
> **Size/Type:** ${sizeType}  
> **Alignment:** ${alignment}  
> **Initiative:** *${initiative}* **Senses:** ${senses}  
> **HP:** ${hp};  
>
> **AC:** *${AC}* (${AC_desc})   **Touch:** *${AC_touch}*   **Flat-Footed:** ${AC_flatfooted} 
> **Speed:**  ***Walk:*** *${walk}*  
>
> **Base Attack:** *${bab}*   **Grapple:** *${grapple}*  
> **Space/Reach:** ***${reach}u/${reach}u*** (${reach * 5}ft/${reach * 5}ft)
>
> **Standard + move:**`;

tR += callout;  
%>
