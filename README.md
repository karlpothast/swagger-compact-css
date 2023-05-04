# swagger-compact-css
A compact style sheet for use with .net swashbuckle and other swagger UI implementations. Less unused white space and scrolling.

1. Add the custom.css stylesheet to your wwwroot/swagger-ui/ directory just like it is in this repo.
2. Edit your program.cs file and add <i>InjectStylesheet</i> to your SwaggerUI options and specify the same file as in step 1 
   ``` .InjectStylesheet("/swagger-ui/custom.css"); ```.   
3. Then add ```UseStaticFiles()``` to your app configuration. 
   
![image](https://user-images.githubusercontent.com/13120778/236339410-743a712b-9ffa-41e0-b88f-0cb33de2e3fa.png)


