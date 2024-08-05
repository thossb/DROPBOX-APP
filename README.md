## Dropbox App in DENO with SUPABASE

As my final project for mmy learning phase as a kalbe farma intern, i learn to make a dropbox app using fresh framework in deno
and i will use supabase as my database.

### Usage

Make sure to install Deno: https://deno.land/manual/getting_started/installation
Then start the project:

```
deno task start
```

### Interface

landing page
![image](https://github.com/user-attachments/assets/45d33e64-778e-40dd-9efe-fd7b9bc4a604)

create folder
![image](https://github.com/user-attachments/assets/330ed7eb-7512-4d3f-b872-ad2bc1e16528)

upload files to existing folder
![image](https://github.com/user-attachments/assets/49d0a267-04bb-46ed-9c0f-208db438892a)

results
![image](https://github.com/user-attachments/assets/3e492692-f84e-44f1-a3a0-bbab602ca762)

![image](https://github.com/user-attachments/assets/06a462f5-9937-4840-bcfe-214f6492f729)

# Code explanation

```
components -> front end components
island     -> functions that needs interactivity
models     -> our models
utils      -> function to configure database ( using deno KV ) and supabase
```
