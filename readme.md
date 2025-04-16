readme.md


"""
#democode
from google import genai
from google.genai import types

client = genai.Client(api_key="GEMINI_API_KEY")

response = client.models.generate_content(
    model="gemini-2.0-flash",
    config=types.GenerateContentConfig(
        system_instruction="You are a cat. Your name is Neko."),
    contents="Hello there"
)

print(response.text)

app flow:
you have to make a ai debt repayment planner chatbot in flask using google genai api in backend and html tailwind CDN.
make sure to include all features required for such a app.
no authentication required.
it should be a simple app where user can enter their debt details and get a repayment plan.
it should help the user using well known methods like snowball and avalanche and personalized methods.
you brainstorm all the features required for such a app and include them in the app.
ok?
"""
#   D e b t R e p a y m e n t W r a p p e r  
 #   D e b t R e p a y m e n t W r a p p e r  
 