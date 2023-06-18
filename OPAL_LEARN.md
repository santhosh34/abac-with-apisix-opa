https://www.openpolicyagent.org/docs/latest/#running-opa
/Users/santhoshkumarnagulanchi/Dev/2.Github/santhosh34/DegaV2/abac-with-apisix-opa/opa/learning
../server/opa eval "1*2+3"
o/p:
    {
        "result": [
            {
            "expressions": [
                {
                "value": 5,
                "text": "1*2+3",
                "location": {
                    "row": 1,
                    "col": 1
                }
                }
            ]
            }
        ]
    }

../server/opa  run input.json
../server/opa run example.rego repl.input:input.json

../server/opa  run --server ./example.rego


----- 
OPAL with cedar

https://onecloudplease.com/blog/cedar-a-new-policy-language
