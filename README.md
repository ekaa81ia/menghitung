import streamlit as st

st.write("""
#menghitung volume kubus""")

sisi =st.number_input("sisi", 0)

hitung = st.button("hitung volume")

if hitung:
   luas = 3 * sisi 
   st.success(f"volume kubus adalah {luas} cm") 
   st.balloons()
st.page_link("http://localhost:8501/", label="Home", icon="🏠")
st.page_link("http://localhost:8502/", label="volume kubus", icon="1️⃣")
