AI-Powered Marketplace Assistant

AIListIt is an AI-powered demo marketplace where sellers can upload a product image, and the system auto-generates a product title, description, and price using multimodal AI. Buyers can interact with an AI agent to find products and simulate checkout.

🚀 Features

AI-generated product listings (BLIP + price predictor)

Buyer-side chat assistant for smart search

Cart, order tracking, and shipping label generator

Gradio-powered multi-tab interface

🧱 Tech Stack

PyTorch, Transformers (Hugging Face), Gradio

ResNet18, DistilBERT, BLIP

CSV-based dataset (images, titles, prices)

📊 Run the Project

pip install -r requirements.txt
python app.py  # or launch from notebook

📚 Dataset Format

image_path, title, price
