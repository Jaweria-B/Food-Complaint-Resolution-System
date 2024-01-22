[![Streamlit](https://img.shields.io/badge/Streamlit-1.30.0-brightgreen)](https://www.streamlit.io/)
[![Clarifai](https://img.shields.io/badge/Clarifai-9.10.4-blue)](https://www.clarifai.com/)
[![Python](https://img.shields.io/badge/Python-3.11.3-blue)](https://www.python.org/)

# Food Complaint Resolution
<p align="center">
  <a href="https://github.com/rsnagarkar10/Food-complaint-resolution-app"><img src="images/assets/logo.png" alt="logo.svg" height="200" width = "200"/></a>
</p>


#

<p align="center">
  <strong>User Friendly AI-Driven Food Delivery Complaint System</strong>
</p>

![GitHub Stars](https://img.shields.io/github/stars/rsnagarkar10/Clarifai_ai_project?style=social)
![GitHub Forks](https://img.shields.io/github/forks/rsnagarkar10/Clarifai_ai_project?style=social)
![GitHub Watchers](https://img.shields.io/github/watchers/rsnagarkar10/Clarifai_ai_project?style=social)

<!-- ![](/images/cover.png) -->
<p align="center">
  <img src="images/assets/cover.png" alt="cover.png" width = "600" height = "500">
</p>

The Food Complaint Resolution application is an AI-based system designed for customer complaints specific to food delivery companies. While many such companies already have a customer complaint system, it often involves humans in handling customer issues.

For instance, if a customer orders pita bread and receives an expired one, filing a complaint means a human has to check it later. The human evaluates the complaint using metadata like images and descriptions. If the complaint is valid, the customer gets a cash refund. This process is time-consuming and depends on the availability of human resources.

Our Food Complaint Resolution application streamlines this process, reducing both time and human effort in handling complaints. It processes customer complaints in just a few seconds, providing a quicker resolution.

We developed this application with ❤️ using the latest AI models, including Food Item Recognition, GPT-4 Turbo, and GPT-4 Vision, to automate complaint resolution. The system features a user-friendly interface created with the Streamlit library.

The application processes complaints similarly to how a human would, evaluating metadata like complaint descriptions and images. After analyzing the information, our system follows company policies to provide a cash refund to eligible customers. If the customer is dissatisfied with the refund or after multiple attempts, the system redirects the complaint to a human for further assistance.

### Features
    - Using AI for receiving the complaint reducing the human effort and time
    - User can select the item, write description and upload images of food for complaint
    - Complain will only be processed when user will provide all the required inputs
    - Using the *Food Item Recognition* model to recognize the food items in the image
    - GPT4-Turbo is used to validating the selected category and image entered
    - GPT4-vision model analyzes the description
    - Cashback or discount provided based on company's rules and regulations
    - User friendly interface for complaint submission
    - A maximum try limit has been set
    - Once the limit gets exceeded, user'll have to refer to the restaurant's management

### Built with
* [Clarifai's streamlit module](https://github.com/clarifai/module-template) - a template for creating a UI module with Clarifai using streamlit 
* [Food Item Recognition](https://clarifai.com/clarifai/main/models/food-item-recognition) - AI model for recognizing a wide variety of food items in images
* [GPT-4 Turbo](https://clarifai.com/openai/chat-completion/models/gpt-4-turbo) - is an advanced language model (llm)
* [GPT-4 vision](https://clarifai.com/openai/chat-completion/models/gpt-4-vision) - extends GPT-4's capabilities that can understand and answer questions about images

## Installation

To install and run Food Complaint Resolution locally, follow these steps:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/rsnagarkar10/Food-complaint-resolution-app.git

    ```

2. **Install the packages:**

    ```bash
        pip install -r requirements.txt
    
    ```

3. **Run the Application**
<br>Make sure to update the .env_example with your CLARIFAI_PAT or provide PAT through UI on application
    ```bash
        streamlit run app.py
    
    ```

## Usage
Food-complaint-resolution uses the streamlit library to provide user ease to complain about the food he received. User can easily select the choice for which he wants to raise the complaint, write the complaint and upload the photos of food. When user will done with entering information our system automatically will use that information to process the user complaint. User can see his complaint is processing, stage and reply (%ag of cashback return to user or not) of complaint from our system. After max tries if user is not satisfied with the reply then our system will redirect the user to human. 

### Visuals
![](/images/assets/app_tour.png)
As the user will fill all input fields then processing will start:
![](/images/assets/Input.png)
After Processing done user can see the results:
![](/images/assets/output.png)

### Where to ask for help?
Open a discussion or stop by our [discord](https://discord.gg/n58UfpCX) server

## Contributing 

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

To contribute to Food Complaint Resolution App, 

Clone this repo locally and commit your code on a separate branch.
If you're making core changes please write unit tests for your code, and check that everything works by running the following before opening a pull-request

or 

1. Fork the Project
2. Create your Feature Branch (`git checkout -b yourBranchName`)
3. Make changes and make sure everything is working fine
4. Commit your Changes (`git commit -m 'Add message here'`)
5. Push to the Branch (`git push origin yourBranchName`)
6. Open a Pull Request

## Team Members
This software is written by the mutual effort of diverse team members :
**Team Leader [Indar Kumar](https://www.linkedin.com/in/indarkarhana/)**,
[Inam ul Rehman](https://www.linkedin.com/in/inamulrehman/),
[Jaweria Batool](https://www.linkedin.com/in/jaweria-batool/),
[Ranjeet Nagarkar](https://www.linkedin.com/in/ranjeet-nagarkar-772060104/),
[Ayesha Mehmood](https://www.linkedin.com/in/ayesha-mehmood-9264a228b/) and
[Usman Ali](https://www.linkedin.com/in/usmaneali/).

Also, thanks to all [contributors](https://github.com/rsnagarkar10/Food-complaint-resolution-app/graphs/contributors) of the software.

### Demo
See the demo [here](/).
