## About
My [resume](./Mohamed_Yamani_CV.pdf) generated by the [RenderCV](https://docs.rendercv.com/) engine which takes a [YAML file](./Mohamed_Yamani_CV.yaml) and returns variety of output files: PDF, Markdown, HTML, PNG, LaTeX...

## Usage
- Create a Python virtual environment and activate it:
```
python3 -m venv venv
source venv/bin/activate
```
- Install the dependencies:
```
pip install -r requirements.txt
```
- Generate the resume in different formats:
```
rendercv render "Mohamed_Yamani_CV.yaml"
```