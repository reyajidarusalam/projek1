conda create --name main-ds python=3.9
conda activate main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel

RUN
streamlit run salinan_proyek_analisis_data.py
