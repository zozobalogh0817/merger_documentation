---
layout: page
title: Usage & Setup
options: { toc: true, menuItem: true, archived: false }
---

# Installation steps
1. Download the `program.zip` from [HERE](LINK)
2. Extract the downloaded `program.zip`
3. Use the program 

## Extraction

> This can be done with various of programs.
> I recommend to use WinRar
  
![before_extract](https://user-images.githubusercontent.com/67690333/166434996-65f94440-88d4-4534-9a64-6e6d18b7b8a8.png)

After the extraction you left with a `program` folder and the `program.zip`.

![after_extract](https://user-images.githubusercontent.com/67690333/166435435-eca4a12a-09e1-4506-a50c-157053f6c38d.png)

# First usage and setup

Go into the `program` folder that we have just created.
Where we should find the following files and folders

![structure_extracted_folder](https://user-images.githubusercontent.com/67690333/166435722-a25dc425-7c6a-4dfc-8b8a-4acd6b3ea16d.png)

From here we just simply need to run the `Merger@0.0.2.exe`

What will leads us to the application.

![application](https://user-images.githubusercontent.com/67690333/166435949-39a3b5c5-6494-4c1b-8d00-2eca7c56dc0d.png)

## The application segments
If we go from top to buttom there is three segment in the application

### The first
The soruce file selection and basic settings
![segment_select_file](https://user-images.githubusercontent.com/67690333/166436300-8eb69a98-a843-4049-944a-a9741713e867.png)

Here we can
   - select the `source file` that we have got from the `RMayer` (other companies may can come in the future)
      - ![mayer_file](https://user-images.githubusercontent.com/67690333/166437642-3109c28d-84f2-454e-a290-a6c333009e1c.png)
      - ![file_select_ok](https://user-images.githubusercontent.com/67690333/166437746-8225c792-6a5a-4a9c-a005-a4c5d868251a.png)
   - check if you want `product pictures` included next to the result ![image](https://user-images.githubusercontent.com/67690333/166437828-e417b5e7-5464-473d-9bdf-41cd840077a3.png)
      - this makes a `50mb` zip file **16 times (this can depend on the number of items in the source file, size of the pictures, and so on)**
      - you can read more about this at **UNAS** [Csoportos Képfeltöltés](https://unas.hu/tudastar/admin/termek-kepek)
   - start the proccess with ![ok_button](https://user-images.githubusercontent.com/67690333/166437875-c6b92aa0-2ce3-4516-9b72-f5d3f49bf48b.png)
      - you can only start when a source file selected 


### The secound
**The feedback** from our process. This way we can track the what happening currently.

![image](https://user-images.githubusercontent.com/67690333/166437196-af89d530-cac1-4e01-92bd-063773168c27.png)

When a process is active we will get **`logs` and the progress bar will be loading with `Green Color`** during it.

![image](https://user-images.githubusercontent.com/67690333/166437977-af3259a1-0739-467b-a069-9ca5ee72f1fe.png)

Here we can 
   - Do nothing just watch!

### The Third
The `zoned pricing` function 

![zoned_pricing_default](https://user-images.githubusercontent.com/67690333/166438356-23b71a5f-1fc6-40ef-a65a-1f244341d434.png)

Here you can set **zones** for the pricies what will be applied during the proccess. 

So if the price zones are set up like this

![zoned_pricing_setup](https://user-images.githubusercontent.com/67690333/166438581-ee6bbd7a-2349-4acc-8f5f-290561dd98de.png)

Then all the pricies between `0` and `1000` will be increased by the `tax percentage` what is `27%` for default and the set `90%` spread value in the first row
So for example if an item **costs netto** *1000ft*
  > 1000 * 100 = 10 // one percentage 
  
  > 10 * 27 = 270 // the tax from netto
  
  > 1000 + 270 = 1270 // price with tax
  
  > 1270 * 100 = 12,7 // one percentage of the tax price
  
  > 12,7 * 90 = 1143 // spread price 
  
  > 1270 + 1143 = 2413

So our *1000ft* item's brutto price will be *2413ft*


