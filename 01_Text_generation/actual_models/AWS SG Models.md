

##### On demand models:

The models with `"inferenceTypesSupported": ["ON_DEMAND"]` are:

| Model Name                  | Model ID                                 | Provider   |
|-----------------------------|------------------------------------------|------------|
| Claude 3 Haiku              | anthropic.claude-3-haiku-20240307-v1:0   | Anthropic  |
| Claude 3.5 Sonnet           | anthropic.claude-3-5-sonnet-20240620-v1:0| Anthropic  |
| Embed English               | cohere.embed-english-v3                   | Cohere     |
| Embed Multilingual          | cohere.embed-multilingual-v3              | Cohere     |


# CROSS REGION INFERENCE MODELS

The models with `"inferenceTypesSupported": ["INFERENCE_PROFILE"]` are:

| Model Name                  | Model ID                                      | Provider   |
|-----------------------------|-----------------------------------------------|------------|
| Embed v4                    | cohere.embed-v4:0                             | Cohere     |
| Claude Sonnet 4.5           | anthropic.claude-sonnet-4-5-20250929-v1:0    | Anthropic  |
| Nova Pro                    | amazon.nova-pro-v1:0                          | Amazon     |
| Nova Lite                   | amazon.nova-lite-v1:0                         | Amazon     |
| Nova Micro                  | amazon.nova-micro-v1:0                        | Amazon     |
| Claude 3 Sonnet             | anthropic.claude-3-sonnet-20240229-v1:0      | Anthropic  |
| Claude 3.5 Sonnet v2        | anthropic.claude-3-5-sonnet-20241022-v2:0    | Anthropic  |
| Claude 3.7 Sonnet           | anthropic.claude-3-7-sonnet-20250219-v1:0    | Anthropic  |
| Claude Sonnet 4             | anthropic.claude-sonnet-4-20250514-v1:0      | Anthropic  |

##### λ aws bedrock list-foundation-models --region ap-southeast-1

```json
{
    "modelSummaries": [
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/cohere.embed-v4:0",
            "modelId": "cohere.embed-v4:0",
            "modelName": "Embed v4",
            "providerName": "Cohere",
            "inputModalities": [
                "TEXT",
                "IMAGE"
            ],
            "outputModalities": [
                "EMBEDDING"
            ],
            "responseStreamingSupported": false,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "INFERENCE_PROFILE"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/anthropic.claude-sonnet-4-5-20250929-v1:0",
            "modelId": "anthropic.claude-sonnet-4-5-20250929-v1:0",
            "modelName": "Claude Sonnet 4.5",
            "providerName": "Anthropic",
            "inputModalities": [
                "TEXT",
                "IMAGE"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "INFERENCE_PROFILE"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/amazon.nova-pro-v1:0",
            "modelId": "amazon.nova-pro-v1:0",
            "modelName": "Nova Pro",
            "providerName": "Amazon",
            "inputModalities": [
                "TEXT",
                "IMAGE",
                "VIDEO"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "INFERENCE_PROFILE"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/amazon.nova-lite-v1:0",
            "modelId": "amazon.nova-lite-v1:0",
            "modelName": "Nova Lite",
            "providerName": "Amazon",
            "inputModalities": [
                "TEXT",
                "IMAGE",
                "VIDEO"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "INFERENCE_PROFILE"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/amazon.nova-micro-v1:0",
            "modelId": "amazon.nova-micro-v1:0",
            "modelName": "Nova Micro",
            "providerName": "Amazon",
            "inputModalities": [
                "TEXT"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "INFERENCE_PROFILE"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/anthropic.claude-3-haiku-20240307-v1:0",
            "modelId": "anthropic.claude-3-haiku-20240307-v1:0",
            "modelName": "Claude 3 Haiku",
            "providerName": "Anthropic",
            "inputModalities": [
                "TEXT",
                "IMAGE"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "ON_DEMAND"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/anthropic.claude-3-5-sonnet-20240620-v1:0",
            "modelId": "anthropic.claude-3-5-sonnet-20240620-v1:0",
            "modelName": "Claude 3.5 Sonnet",
            "providerName": "Anthropic",
            "inputModalities": [
                "TEXT",
                "IMAGE"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "ON_DEMAND"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/anthropic.claude-3-sonnet-20240229-v1:0:28k",
            "modelId": "anthropic.claude-3-sonnet-20240229-v1:0:28k",
            "modelName": "Claude 3 Sonnet",
            "providerName": "Anthropic",
            "inputModalities": [
                "TEXT",
                "IMAGE"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/anthropic.claude-3-sonnet-20240229-v1:0:200k",
            "modelId": "anthropic.claude-3-sonnet-20240229-v1:0:200k",
            "modelName": "Claude 3 Sonnet",
            "providerName": "Anthropic",
            "inputModalities": [
                "TEXT",
                "IMAGE"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/anthropic.claude-3-sonnet-20240229-v1:0",
            "modelId": "anthropic.claude-3-sonnet-20240229-v1:0",
            "modelName": "Claude 3 Sonnet",
            "providerName": "Anthropic",
            "inputModalities": [
                "TEXT",
                "IMAGE"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "INFERENCE_PROFILE"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/anthropic.claude-3-5-sonnet-20241022-v2:0",
            "modelId": "anthropic.claude-3-5-sonnet-20241022-v2:0",
            "modelName": "Claude 3.5 Sonnet v2",
            "providerName": "Anthropic",
            "inputModalities": [
                "TEXT",
                "IMAGE"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "INFERENCE_PROFILE"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/anthropic.claude-3-7-sonnet-20250219-v1:0",
            "modelId": "anthropic.claude-3-7-sonnet-20250219-v1:0",
            "modelName": "Claude 3.7 Sonnet",
            "providerName": "Anthropic",
            "inputModalities": [
                "TEXT",
                "IMAGE"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "INFERENCE_PROFILE"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/anthropic.claude-sonnet-4-20250514-v1:0",
            "modelId": "anthropic.claude-sonnet-4-20250514-v1:0",
            "modelName": "Claude Sonnet 4",
            "providerName": "Anthropic",
            "inputModalities": [
                "TEXT",
                "IMAGE"
            ],
            "outputModalities": [
                "TEXT"
            ],
            "responseStreamingSupported": true,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "INFERENCE_PROFILE"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/cohere.embed-english-v3",
            "modelId": "cohere.embed-english-v3",
            "modelName": "Embed English",
            "providerName": "Cohere",
            "inputModalities": [
                "TEXT"
            ],
            "outputModalities": [
                "EMBEDDING"
            ],
            "responseStreamingSupported": false,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "ON_DEMAND"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        },
        {
            "modelArn": "arn:aws:bedrock:ap-southeast-1::foundation-model/cohere.embed-multilingual-v3",
            "modelId": "cohere.embed-multilingual-v3",
            "modelName": "Embed Multilingual",
            "providerName": "Cohere",
            "inputModalities": [
                "TEXT"
            ],
            "outputModalities": [
                "EMBEDDING"
            ],
            "responseStreamingSupported": false,
            "customizationsSupported": [],
            "inferenceTypesSupported": [
                "ON_DEMAND"
            ],
            "modelLifecycle": {
                "status": "ACTIVE"
            }
        }
    ]
}
```

