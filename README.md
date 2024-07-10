# llm-api

- Proiectul se ruleaza folosind un kernel de Jupyter Notebook de Python 3.12
- Am folosit huggingface_cli pentru downladarea modelului phi3
- Am folosit onnxruntime pentru a putea rula modelul folosind compatibilitatea DirectX12
- Am folosit python-docx pentru citirea textului din documente docx
- Nu am putut antrena sau modifica modelul. Din pacate placa mea video nu sustine librariile pytorch si transformers, motiv pentru care am folosit onnxruntime, o solutie alternativa bazata pe DirectX12, care din pacate nu are capacitati de antrenare a modelelor predefinite
- Am reusit totusi sa rulez phi3, insa rezultatele nu sunt cele dorite
