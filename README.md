# reconhecimento-de-celebridades

realizei um desafio utilizando o AWS Rekognition para detectar celebridades em imagens. O objetivo era explorar a API de reconhecimento facial da AWS e verificar sua precisão na identificação de figuras públicas.

Passos do Desafio
Configuração do Ambiente: Configurei uma conta na AWS, criei uma IAM Role com permissões adequadas para o Rekognition e utilizei o SDK do AWS para Python (Boto3).
Upload de Imagens: Selecionei algumas imagens contendo celebridades conhecidas e armazenei-as no Amazon S3 para facilitar o processamento.
Detecção com Rekognition: Utilizei a função recognize_celebrities() da API do AWS Rekognition para analisar as imagens e identificar possíveis celebridades.
Resultados e Avaliação: O Rekognition retornou nomes das celebridades, nível de confiança e metadados adicionais, como coordenadas faciais e URLs de referência.
Conclusão
O AWS Rekognition mostrou-se eficiente na identificação de celebridades, reconhecendo corretamente a maioria das figuras públicas testadas. No entanto, algumas falhas ocorreram em imagens com baixa qualidade ou ângulos incomuns. Esse desafio demonstrou o potencial da ferramenta para aplicações de reconhecimento facial, podendo ser útil em diversas áreas, como segurança, entretenimento e marketing.

Foi uma experiência interessante e mostrou como a inteligência artificial da AWS pode ser aplicada para resolver problemas do mundo real de maneira simples e escalável. 🚀
