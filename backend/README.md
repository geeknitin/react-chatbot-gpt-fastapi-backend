# Install dependencies 
pip3 install -r requirements.txt

# Run the server
uvicorn app:app --reload 

or 

python3 -m uvicorn app:app --reload
