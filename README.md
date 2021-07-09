# IBY1.0

How to setup the Project- 
1. Clone the repository and open it in Visual studio as a WPF app(.NET Framework). 
2. Download the ML model from the following link- https://drive.google.com/file/d/1vSX64fpGY602C0jQDE98k11DQ4R_5lvZ/view?usp=sharing
3. Select the .onnx file and drag and drop it into the /assets/Model folder icon in the Solution explorer in Visual Studio. Copy pasting in the file Explorer might not work. 
4. Go to Project->Manage NuGet Packages and install the following packages -        
      -> EmguCV v.3.1.0.1. 
      -> Microsoft.ML
      -> Microsoft.ML.ImageAnalytics 
      -> Microsoft.ML.OnnxTransformer 
      -> Microsoft.ML.OnnxRuntime
     
