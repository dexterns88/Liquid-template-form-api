/*
| Example for form api
| How to create form and fields into template form api
*/


# Create input type text,email,phone ....

{% include _form/input_text.html text='Full name:' name='full_name' required=true %}