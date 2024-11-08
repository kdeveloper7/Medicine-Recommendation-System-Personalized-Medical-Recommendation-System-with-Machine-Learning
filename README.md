
Paso 1: Configurar el Entorno de Desarrollo
Primero, abre tu terminal y sigue estos comandos.

Crear y activar un entorno virtual en Python:

    

    python3 -m venv socialenv
    source socialenv/bin/activate  # En Windows usa: socialenv\Scripts\activate
    python.exe -m pip install --upgrade pip
    pip install -r requirements.txt
    pip freeze > requirements.txt

    Opción1.:
    
    **Levantar el servidor con templates**
    python run main.py



     Opción2.:

    **Se puede levantar el servidor Flask como una API rest con el fichero main_api_rest.py**

        1. Prueba el Endpoint con Postman
            Abre Postman.
            Selecciona POST como método de la solicitud.
            En la URL, escribe http://127.0.0.1:5000/predict (ajusta el puerto si es necesario).
            En la pestaña Body, selecciona raw y JSON.
            Inserta un ejemplo de datos JSON en el cuerpo, como:

                    {
                    "symptoms": ["itching", "skin_rash"]
                    }
            Haz clic en Send y Postman mostrará la respuesta en JSON que retorna la API.







# Personalized-Medical-Recommendation-System-with-Machine-Learning
Welcome to our cutting-edge Personalized Medical Recommendation System, a powerful platform designed to assist users in understanding and managing their health. Leveraging the capabilities of machine learning, our system analyzes user-input symptoms to predict potential diseases accurately. Here's what sets our system apart:

User-Friendly Interface: Our intuitive interface allows users to input their symptoms effortlessly, creating a seamless user experience.

Advanced Machine Learning Models: We've integrated state-of-the-art machine learning models that accurately predict diseases based on input symptoms, ensuring reliable and precise results.

Tailored Recommendations: Receive personalized recommendations for the top 5 medicines, prescription details, and even workout routines based on the predicted disease.

Flask App Integration: The entire system is powered by a Flask web application, making it easily accessible to users. Experience the convenience of accessing healthcare recommendations from anywhere.

Privacy and Security: We prioritize user privacy and data security. Your health information is handled with the utmost confidentiality, adhering to the highest industry standards.

Continuous Improvement: Our system is designed for continuous improvement. As we gather more data, the machine learning models evolve, providing increasingly accurate and relevant recommendations.

Take charge of your health with our Personalized Medical Recommendation System. Your well-being is our priority, and we're dedicated to providing you with the tools and insights you need for a healthier, happier life.


credits to : https://www.youtube.com/watch?v=1xHU20MgvqI

The code has been refactorized by kdeveloper7 for implementing API rest and configure de datasets and files.



