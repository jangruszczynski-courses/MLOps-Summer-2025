# Homework Assignment: Deploying a Model as a Service  

### **Objective:**  
The goal of this assignment is to deploy a machine learning model as a REST or gRPC service using one of the following deployment frameworks:  
- **BentoML**  
- **NVIDIA Triton Inference Server**  
- **TorchServe**  
- (or any similar deployment tool)  

You must expose an API endpoint that accepts requests and returns model predictions.  

---

## **Assignment Details**  

1. **Select a framework** (e.g., BentoML, NVIDIA Triton, or TorchServe).  
2. **Prepare a trained model** (e.g., a simple PyTorch or TensorFlow model), if possible use the one you have trained for previous classes.  
3. **Deploy the model** as a service.  
4. **Expose an API** that can be accessed via `cURL`, Python `requests`, or the specific client of the chosen framework.  
5. **Demonstrate the working API** with an example request.  

---

## **Acceptance Criteria**  

1. **Model Deployment Code**  
   - Showcase a script or configuration file to deploy the model.  
   - Example: BentoML service, TorchServe `.mar` file, or NVIDIA Triton model repository setup.  

2. **API Endpoint Exposure**  
   - Show the endpoint and how the API is called.  
   - Example: A REST or gRPC endpoint handling inference requests.  

3. **Client Request Example**  
   - Provide an example of how to send a request to the deployed model using one of the following:  
     - `cURL`  
     - Python `requests`  
     - The framework’s specific client (e.g., TritonClient for NVIDIA Triton).  

4. **Working Output**  
   - The service must return a valid prediction from the model.  

## **Grading**  

- **Base Score: 0.5 points** (for using BentoML, TorchServe, or a similar framework).  
- **Bonus: +0.25 points (Total: 0.75 points)** if the model is deployed using **NVIDIA Triton Inference Server**.  

## **Useful links**
*
*
*
