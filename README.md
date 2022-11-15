


<div style="color: linen; border-color: linen">
  <a href="https://github.com/PothpothBR">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=PothpothBR&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
</div>

Weird perfectionist "Rules of Code":
* Functions/Methods in camelCase
* Structs/Classes/Objects in PascalCase
* Variables/Files/ in snake_case
* Constants/Flags in SCREAMING_SNAKE_CASE
* Keys/Ids/'Conf. File Keys' dot.case

* When closing keys that are not on the same line, they must be placed in the same scope as their owner.
ex:
 ```C
f(
    ...,
    ...
)
 ```
* Each comma that follows on a different line must be parallel to the code with a comma of the previous line.
  ex:
```
// It's unaligned
fNotIsFoo(..., ..., ...,
    ..., ..., ...
    ..., ..., ...
)

// In this special case, not beatiful
fNotIsFoo(..., ..., ...,
          ..., ..., ...
          ..., ..., ...
)

// make separated
fNotIsFoo(
    ..., ..., ...,
    ..., ..., ...
    ..., ..., ...
)
 
// align it
float abc_abc_abc,
      cde_cde_cde,
      fgh_fgh_fgh;
  
// this is horrible, separe
unsigned short int abc_abc_abc,
                   cde_cde_cde,
                   fgh_fgh_fgh;
  
unsigned short int
    abc_abc_abc,
    cde_cde_cde,
    fgh_fgh_fgh;
```
  
* Code that can be shortened, so it must be shortened.
  ex:
 ```
// It's short, reduce it
f(
    ...,
    ...
)
  
f(..., ...)
  
// It's short, but in one line its bigger
fNotIsFooItsOnlyF(
    ...do_somewone_in_here, ...do_more_somewone_in_here
)
  
// Use ','  instead a multiple definitions
int a;
int b;
int c;
int d;
int e;
int f;
  
// The short type
int a, b, c, d, e, f;
  
// It's short, but in one line its bigger
int abc_abc_abc = 1234567890,
     cde_cde_cde = 1234567890,
     fgh_fgh_fgh = 1234567890;
 ```
