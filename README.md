# Streamlit_Basics

## Installtion
 pip install streamlit

## Importing the library 
 import streamlit as st

## To display
 st.write("This is streamlit app")

## To run
 streamlit run app.py (if you have saved your file name as app.py)

## Markdown, Title, Button and Sidebar
 st.markdown("msg")

 st.title("Streamlit App")

 st.button("Click here")

 st.sidebar.title('Options')

## Streamlit background image
 st.markdown(
   
    """
    
    <style>
    
    body {
    
        background-image: url("https://example.com/background-image.jpg");
        
        background-size: cover;
    
    }
    
    </style>
    
    """,
    
    unsafe_allow_html=True
)
