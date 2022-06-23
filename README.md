We would need spacy module version '3.2.4' to run the jupyter code
You will also need en_core_web_sm model from spacy which you can download after downloading spacy using:
pip install spacy
python -m spacy download en_core_web_sm

You can send the input as a text in the text variable then call the get_entities function and it will return list of dictionaries each dictionary will consist of the text,its type,start pos,end pos.
