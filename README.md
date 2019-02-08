# PHP1000_basic_template_creation
Simple exercise to create a new HTML template and fill it using PHP data from an associative array.

## 1) Create the template file
Create a new file "profile.php" and recreate the below template using HTML and CSS only. Do not use PHP so far, just try to reproduce the design the best way you can without putting too much effort. Is does not have to look exactly as in the image, it just need to have the same text and components. Use any online picture for the src of the IMG element.  

![profile template image](https://raw.githubusercontent.com/techlaunch/PHP1000_basic_template_creation/master/template_image.png)

## 2) Connect to PHP dynamically
On top of the file "profile.php", open and close PHP tags and paste the array below. Then proceed to replace the content of the HTML code previously created by dynamic PHP code brought from the array.  

In instance, where you find the text "Maria Santos" in the HTML, replace it by <?= $profile["name"] ?>, and so on. For elements like links, you will be replacing in the "href" attribute. If the gender is "F", make the picture to have a pink border, if the gender is "M", make it to have a blue border. 

```
$profile = [
	"name" => "Teresa Santos",
	"age" => "19",
	"position" => "Junior Developer",
	"gender" => "F",
  "facebook_link" => "https://www.facebook.com/teresa",
  "github_link" => "https://github.com/teresa",
	"bio" => "Teresa is an young entrepreneur living in Miami who likes ice cream and watches superheroes movies at night. She is a happy fellow.",
	"picture" => "https://www.imagen.com.mx/assets/img/imagen_share.png"
];

```

## 3) Add your own information!
Replace the information in the array by your own. Refresh the page and looks your very own profile working!
