Hi,
The code runs in notebook.
The below process will install spark, jupyter-lab, dependencies in a virtual python enviroment so as to be able to run the code.
If you import the notebook in Databricks and change the path and also upload the data, you should probably also be good to run it.

How to run the code:

1. Unzip the folder

2. Navigate inside the folder and type in shell to create the virtual environment
python -m venv venv

3. Activate the enviroment
navigate to venv\Scripts
type in shell: activate 
Note in linux based and MAC, you need to source activate

ref: https://docs.python.org/3/library/venv.html

4. Navigate back to our root with the data and notebook

5. Install all the dependencies packages by typing in shell
pip install -r requirements.txt 

6. Now we should have everything installed pyspark, jupyter-lab, 
many dependecies including pyarrow for pandas udf 

7. From our root directory of our unzip, type in shell to start jupyter-lab the below
jupyter-lab

8. If notebook EMIS_IA is not selected by default, we just double click on it.

9. We run the notebook shell by shell

10. When we finish our run, we should remember to use deactivate to stop the virtual environment

Hope this will work, i did do dry in Windows from scratch. 

Many thank !





