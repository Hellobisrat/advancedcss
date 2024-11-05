# advancedcss

it shows how to save different variables
as a root and we can use with the var()
function
we can use many times as needed once we save in the root

variables can be saved like below

:root {
/* FONT */
  --FF: "Nunito",sans-serif;
  --FS:1.5rem;
  --FS-XL:3rem;
}

we can use like this

font: var(--FS) var(--FF);

# final page looks like

<img src='./img1.png'>

# bisrat