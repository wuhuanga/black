注意所有API须换成自己的api，可以在https://platform.deepseek.com里充值然后获取api_key。一般10块以内即可完成整门课程的内容。
api.py为使用API调用模型。
local.py为本地部署模型，内部提示词是场景嵌套的越狱攻击。
black_scenairo.py为使用本地部署模型和一些提示词尝试越狱。（可更换模型【huggingface上可以找】，更换提示词，自己尝试一下）
Cryptographic_Strategy.py为密码学策略，使用API实验。
Linguistic_Strategy.py为语言学策略，可以在其它软件上翻译你的prompt再输入到模型去攻击，并不必须完整使用该代码。
