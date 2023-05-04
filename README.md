# swagger-compact-css
A compact style sheet for use with .net swashbuckle and other swagger UI implementations. Less unused white space and scrolling.

1. Add the custom.css stylesheet to your wwwroot/swagger-ui/ directory just like it is in this repo.
2. Edit your program.cs file and add <i>InjectStylesheet</i> to your SwaggerUI options and specify the same file as in step 1 
   ``` .InjectStylesheet("/swagger-ui/custom.css"); ```.   
3. Then add ```UseStaticFiles()``` to your app configuration. 
   
![image](https://user-images.githubusercontent.com/13120778/236339410-743a712b-9ffa-41e0-b88f-0cb33de2e3fa.png)

# Default CSS (before custom CSS)
> Info section takes up 1/3 of the page, need to move the mouse across the screen and back to "Try This Out" and "Execute" then scroll down futher to see the response.
![alt-text-1](https://raw.githubusercontent.com/karlpothast/swagger-compact-css/master/default-swagger-css.png "Default")

# Compact CSS (after custom CSS)
> All buttons on the left with the info section in a side bar, no wasted white space and this particular response is visible without scrolling down.
![alt-text-2](https://raw.githubusercontent.com/karlpothast/swagger-compact-css/master/compact-swagger-css.png "Compact")










