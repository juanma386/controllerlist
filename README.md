# controllerlist
Controlador para listar controladores dentro de codeigniter

Controllerlist
A simple library to list all your controllers and methods of your Codeigniter 2 application.

Usage
Copy the file "Controllerlist.php" to your application/libraries folder. In one of your controllers do the following:

$this->load->library('controllerlist');
print_r($this->controllerlist->getControllers());
This will show you an array with all the controllers and their methods.

Contact me at Peter Prins
