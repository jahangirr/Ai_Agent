download google antigravity
install
sign-in through google account
open folder where you want to work
-to create virtual environment , 
going to powersell run below command
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex" 
[it gets from  uv docs ]
then restart your IDE.
then open cmd => run below command
uv init
uv venv
.venv\Scripts\activate

add requirements.txt to the root folder
write package name then run below command
uv add -r requirements.txt

uv add ipykernel

