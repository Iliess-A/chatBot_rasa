# chatBot_rasa
let's create a chat bot in python and Rasa

## first set up vsCode:

Here i am using Visual studio code, but i want to work in a virtual envirenement so let set it up( for wsl ), 

1. Open your project folder in VS Code.
2. Open the terminal in VS Code.
3. Create a virtual environment by running the following command in the terminal:
<< python3 -m venv myenv >>
//Replace myenv with the name you want for your virtual environment.
4. Activate the virtual environment:
<< source myenv/bin/activate >>

Select the Python interpreter for your virtual environment in VS Code:
Press Ctrl + Shift + P to open the Command Palette.
Type Python: Select Interpreter and choose the interpreter from your virtual environment.
Install necessary packages using pip within the activated virtual environment:
pip3 install package_name ( here we will be using Rasa ).

This setup will allow you to manage your project’s dependencies in an isolated environment.

!!! Don't forget to enter the isolated environement by doing in the bash command :
<< source myenv/bin/activate >>, now u can do the pip3 install.
ps: to get out of the isolated environement do: << deactivate >>

While installing and setting up ur environement u will need pip3 so don't forget to update it.

## Second rasa setUp:

When I tried installing rasa the first time I got a probleme cause I used pip install rasa instead of pip3 install rasa. ( error was about an old package or whatever ).

While installing u will get to choose where to install the package and if you want the bot to get train by the pre-training file and finaly if you want to speak with ur bot
in the terminal, you can try it but the bot won't be able to answear a lot of question it's just a try/test.( when ur finished just do crtl + C ).

It's should be all for the setup.

## third step :

Now we finally get to train our bot for what we want, but to do so we need to now for what u wanna train ur bot and get a lot of data the more the best to train it.

Here i am gonna train it for basic help in a web site so it should be able to answear customer question, redircet the customer to the right page and so on.



