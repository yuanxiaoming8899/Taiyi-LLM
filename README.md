<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英文</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/DUTIR-BioNLP/Taiyi-LLM/blob/main/README_ZH.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></p>
<p align="center" dir="auto">
    <br>
    <a target="_blank" rel="noopener noreferrer" href="/DUTIR-BioNLP/Taiyi-LLM/blob/main/fig/logo-all.png?raw=true"><img src="/DUTIR-BioNLP/Taiyi-LLM/raw/main/fig/logo-all.png?raw=true" width="800" height="381" style="max-width: 100%;"></a>
    <br>
</p>
<p align="center" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
        🤗</font></font><a href="https://huggingface.co/DUTIR-BioNLP/Taiyi-LLM" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">抱脸</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;&nbsp; | 🤖</font></font><a href="https://modelscope.cn/models/DUTIRbionlp/Taiyi-LLM/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型范围</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;&nbsp; | 🖥️</font></font><a href="http://117.161.233.22:1234/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;&nbsp; | 📃</font></font><a href="/DUTIR-BioNLP/Taiyi-LLM/blob/main/data_file/dataset_inf.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;&nbsp; | &nbsp;&nbsp; </font></font><a href="https://doi.org/10.1093/jamia/ocae037" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">纸</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;&nbsp;| &nbsp;&nbsp; </font></font><a href="https://mp.weixin.qq.com/s/HlyzalsxdNy6yFV2iGqbBQ" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">微信 (微信)</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> | &nbsp;&nbsp; </font></font><a href="https://www.wisemodel.cn/models/DUTIR-BioNLP/Taiyi" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">智慧模型</font></font></a>
<br>
<br>
</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taiyi（太一）：针对多种生物医学任务的双语（中文和英文）微调大语言模型</font></font></h1><a id="user-content-taiyi-太一-a-bilingual-chinese-and-english-fine-tuned-large-language-model-for-diverse-biomedical-tasks" class="anchor" aria-label="永久链接：太一：用于多种生物医学任务的双语（中文和英文）微调大语言模型" href="#taiyi-太一-a-bilingual-chinese-and-english-fine-tuned-large-language-model-for-diverse-biomedical-tasks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目背景</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">随着深度学习技术的快速发展，像ChatGPT这样的大型语言模型（LLM）在自然语言处理领域取得了重大进展。在生物医学应用背景下，大语言模型促进医疗保健专业人员和患者之间的沟通，提供有价值的医疗信息，并在辅助诊断、生物医学知识发现、药物开发和个性化医疗保健解决方案等方面具有巨大潜力。然而，在人工智能领域，现有的开源生物医学大型模型相对匮乏，大多数主要集中于中文或英文的单语医学问答对话。因此，本项目致力于生物医学领域大模型的研究，推出了第一个版本的双语（中英）生物医学大语言模型“太一”，旨在探索大模型处理各种问题的能力。生物医学领域的双语自然语言处理任务。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">消息</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"></font><a href="https://doi.org/10.1093/jamia/ocae037" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024/03/01 我们的论文在JAMIA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在线发表</font><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024/01/05 我们发布了原始指令数据（</font></font><a href="https://github.com/DUTIR-BioNLP/Taiyi-LLM/releases/download/Taiyi_Instruction_Data_001/Taiyi_Instruction_Data_001.zip"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taiyi_Instruction_Data_001</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。数据按照</font></font><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?spm=a2c22.12282016.0.0.32263d000YGHLB" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CC BY-NC-SA 4.0</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分发</font><font style="vertical-align: inherit;">。支持这项研究的原始基准数据集可从带有数据使用协议的自然语言处理挑战的官方网站获得。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024/01/03 由于资源有限，demo移至huggingface空间，并使用INT8量化部署。为了体验更好的结果，建议下载权重并使用脚本进行非定量部署测试。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目亮点</font></font></strong></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">丰富的生物医学训练资源</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：针对生物医学领域，该项目收集并整理了一套多样化的双语（中文和英文）生物医学自然语言处理（BioNLP）训练数据集。该集合共包含 38 个涵盖 10 个 BioNLP 任务的中文数据集和 102 个涵盖 12 个 BioNLP 任务的英文数据集。为了满足特定任务的要求，设计并应用了标准化数据格式，以确保所有数据集的格式保持一致。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">双语BioNLP多任务能力</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：利用丰富的双语教学数据（超过100万个样本）对LLM进行微调，模型在生物医学智能问答、生物医学对话、报告生成、信息等各种BioNLP任务中展现出双语能力提取、机器翻译、标题生成、文本分类等等。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">突出的泛化能力</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除了生物医学对话能力外，该模型还保留了通用领域对话能力。通过多样化的指令模板的设计，它在相似任务的各种场景中表现出良好的泛化能力，甚至激发了模型的零样本学习能力。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为推动NLP在生物医学领域的发展，本项目发布了中英BioNLP数据集整理详情、太乙大模型权重以及模型推理使用脚本。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">框架概述</font></font></strong></p>
<p align="center" dir="auto">
    <br>
    <a target="_blank" rel="noopener noreferrer" href="/DUTIR-BioNLP/Taiyi-LLM/blob/main/fig/overview_en.png?raw=true"><img src="/DUTIR-BioNLP/Taiyi-LLM/raw/main/fig/overview_en.png?raw=true" width="900" height="451" style="max-width: 100%;"></a>
    <br>
</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内容</font></font></h2><a id="user-content-contents" class="anchor" aria-label="永久链接： 内容" href="#contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="#taiyi-%E5%A4%AA%E4%B8%80a-bilingual-chinese-and-english-biomedical-large-language-model-finetuned-with-rich-biomedical-data"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太一：基于丰富生物医学数据的双语（中英）生物医学大语言模型</font></font></a>
<ul dir="auto">
<li><a href="#contents"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内容</font></font></a></li>
<li><a href="#use-cases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用例</font></font></a>
<ul dir="auto">
<li><a href="#1-question-answering"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1. 问答</font></font></a></li>
<li><a href="#2-biomedical-dialogue"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2. 生物医学对话</font></font></a></li>
<li><a href="#3-medical-report-generation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3. 医疗报告生成</font></font></a></li>
<li><a href="#4-biomedical-information-extraction"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.生物医学信息提取</font></font></a>
<ul dir="auto">
<li><a href="#41-named-entity-recognition"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.1 命名实体识别</font></font></a></li>
<li><a href="#42-relation-extraction"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.2 关系抽取</font></font></a></li>
<li><a href="#43-event-extraction"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.3 事件提取</font></font></a></li>
</ul>
</li>
<li><a href="#5-machine-translation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5. 机器翻译</font></font></a></li>
<li><a href="#6-title-generation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6. 标题生成</font></font></a></li>
<li><a href="#7-text-classification"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">7. 文本分类</font></font></a></li>
<li><a href="#8-text-semantic-similarity"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8. 文本语义相似度</font></font></a></li>
</ul>
</li>
<li><a href="#training-data"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">训练数据</font></font></a>
<ul dir="auto">
<li><a href="#data-collection"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据采集</font></font></a></li>
<li><a href="#standardized-data-format"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标准化数据格式</font></font></a></li>
<li><a href="#instruction-tuning-data"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指令调整数据</font></font></a></li>
</ul>
</li>
<li><a href="#model-training"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型训练</font></font></a>
<ul dir="auto">
<li><a href="#introduction-to-the-base-model"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基础模型简介</font></font></a></li>
<li><a href="#training-details"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">培训详情</font></font></a></li>
</ul>
</li>
<li><a href="#model-usage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">型号用途</font></font></a>
<ul dir="auto">
<li><a href="#environment-setup"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境设置</font></font></a></li>
<li><a href="#model-inference"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型推理</font></font></a></li>
</ul>
</li>
<li><a href="#overall-performance"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整体表现</font></font></a></li>
<li><a href="#limitation-and-future-work"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">限制和未来的工作</font></font></a></li>
<li><a href="#development-team"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发团队</font></font></a></li>
<li><a href="#acknowledgements"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></a></li>
<li><a href="#disclaimer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免责声明</font></font></a></li>
<li><a href="#citation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></a></li>
<li><a href="#star-history"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">明星历史</font></font></a></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用例</font></font></h2><a id="user-content-use-cases" class="anchor" aria-label="永久链接：用例" href="#use-cases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1. 问答</font></font></h3><a id="user-content-1-question-answering" class="anchor" aria-label="永久链接： 1. 问答" href="#1-question-answering"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务介绍</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生物医学问答旨在通过问答的形式帮助用户获取与生物医学科学领域相关的答案和信息。有助于更有效地管理生物医学信息，提高医疗决策质量，提高生物医学教育的有效性。</font></font></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></b></summary>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文示例</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>用户：最近肚子总是隐隐作痛，感觉胀胀的，吃下去的东西都没法吸收，胃疼的特别厉害，偶尔伴有恶心想吐的感觉，请问是什么回事？
太一：您好，根据您的描述，您可能正在经历胃肠道不适的症状。这些症状可能是由多种原因引起的，例如消化不良、胃炎、胃溃疡、胆囊炎、胆囊结石等。建议您尽快就医，进行相关检查以确定病因，并根据医生的建议进行治疗。同时，您可以注意饮食，避免辛辣、油腻、刺激性食物，多喝水，保持良好的生活习惯，避免过度劳累和情绪波动。希望您早日康复。
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="用户：最近肚子总是隐隐作痛，感觉胀胀的，吃下去的东西都没法吸收，胃疼的特别厉害，偶尔伴有恶心想吐的感觉，请问是什么回事？
太一：您好，根据您的描述，您可能正在经历胃肠道不适的症状。这些症状可能是由多种原因引起的，例如消化不良、胃炎、胃溃疡、胆囊炎、胆囊结石等。建议您尽快就医，进行相关检查以确定病因，并根据医生的建议进行治疗。同时，您可以注意饮食，避免辛辣、油腻、刺激性食物，多喝水，保持良好的生活习惯，避免过度劳累和情绪波动。希望您早日康复。" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语示例</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>User：What is the best treatment for sleep problems?
Taiyi：The best treatment for sleep problems depends on the specific cause of the sleep problem. There are many different factors that can contribute to sleep problems, including sleep disorders, stress, anxiety, depression, medication, and lifestyle habits. Some common treatments for sleep problems include:
1. Cognitive-behavioral therapy (CBT) for sleep disorders, which is a type of talk therapy that helps people identify and change negative thoughts and behaviors that are interfering with their sleep.
2. Relaxation techniques, such as deep breathing, progressive muscle relaxation, and visualization, which can help people relax and fall asleep.
3. Sleep hygiene, which is a set of practices that promote healthy sleep habits, such as avoiding caffeine and electronics before bedtime, maintaining a regular sleep schedule, and creating a relaxing bedtime routine.
4. Medications, such as sleep aids, which can help people fall asleep and stay asleep, but may have side effects and risks.
5. Lifestyle changes, such as exercise, avoiding alcohol and nicotine, and creating a relaxing bedtime routine, which can all help improve sleep quality..
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="User：What is the best treatment for sleep problems?
Taiyi：The best treatment for sleep problems depends on the specific cause of the sleep problem. There are many different factors that can contribute to sleep problems, including sleep disorders, stress, anxiety, depression, medication, and lifestyle habits. Some common treatments for sleep problems include:
1. Cognitive-behavioral therapy (CBT) for sleep disorders, which is a type of talk therapy that helps people identify and change negative thoughts and behaviors that are interfering with their sleep.
2. Relaxation techniques, such as deep breathing, progressive muscle relaxation, and visualization, which can help people relax and fall asleep.
3. Sleep hygiene, which is a set of practices that promote healthy sleep habits, such as avoiding caffeine and electronics before bedtime, maintaining a regular sleep schedule, and creating a relaxing bedtime routine.
4. Medications, such as sleep aids, which can help people fall asleep and stay asleep, but may have side effects and risks.
5. Lifestyle changes, such as exercise, avoiding alcohol and nicotine, and creating a relaxing bedtime routine, which can all help improve sleep quality.." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2. 生物医学对话</font></font></h3><a id="user-content-2-biomedical-dialogue" class="anchor" aria-label="永久链接：2.生物医学对话" href="#2-biomedical-dialogue"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务介绍</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙模型能够模拟医学专家与患者之间的自然语言对话。这些对话可以涵盖各种生物医学主题，包括医学询问、疾病预防、药物咨询等。</font></font></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></b></summary>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文示例</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>用户：什么是鼠疫？
太一：鼠疫是由鼠疫杆菌引起的传染病，鼠疫杆菌是一种细菌，通常通过跳蚤叮咬传播。鼠疫杆菌主要存在于啮齿类动物的，如老鼠、土拨鼠等，当这些动物被感染后，它们会通过跳蚤叮咬传播给其他动物，包括人类。鼠疫杆菌主要通过跳蚤叮咬传播，也可以通过直接接触感染。
用户：它有什么预防方法吗？
太一：
预防鼠疫的方法包括以下几点：
避免接触感染源：尽量避免接触啮齿类动物，如老鼠、土拨鼠等，特别是在疫区或疫区附近。
保持个人卫生：勤洗手，保持身体清洁，避免接触感染源。
食用安全食品：在疫区或疫区附近，尽量避免食用未经煮熟的肉类、蛋类等食品。
做好防护措施：在疫区或疫区附近，佩戴口罩、手套等防护用品，避免直接接触感染源。
接种疫苗：在疫区或疫区附近，可以接种鼠疫疫苗，增强免疫力，预防感染。
用户：鼠疫常发生在哪些国家？
太一：鼠疫是一种全球性传染病，主要分布在温带和寒带地区。目前，鼠疫主要分布在亚洲、非洲和欧洲等地区。其中，亚洲地区是鼠疫的主要流行区，包括中国、蒙古、俄罗斯、朝鲜、韩国、日本等国家。非洲地区是鼠疫的高发区，包括非洲中部、南部、东部等地区。欧洲地区是鼠疫的高发区，包括欧洲中部、北部、东部等地区。
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="用户：什么是鼠疫？
太一：鼠疫是由鼠疫杆菌引起的传染病，鼠疫杆菌是一种细菌，通常通过跳蚤叮咬传播。鼠疫杆菌主要存在于啮齿类动物的，如老鼠、土拨鼠等，当这些动物被感染后，它们会通过跳蚤叮咬传播给其他动物，包括人类。鼠疫杆菌主要通过跳蚤叮咬传播，也可以通过直接接触感染。
用户：它有什么预防方法吗？
太一：
预防鼠疫的方法包括以下几点：
避免接触感染源：尽量避免接触啮齿类动物，如老鼠、土拨鼠等，特别是在疫区或疫区附近。
保持个人卫生：勤洗手，保持身体清洁，避免接触感染源。
食用安全食品：在疫区或疫区附近，尽量避免食用未经煮熟的肉类、蛋类等食品。
做好防护措施：在疫区或疫区附近，佩戴口罩、手套等防护用品，避免直接接触感染源。
接种疫苗：在疫区或疫区附近，可以接种鼠疫疫苗，增强免疫力，预防感染。
用户：鼠疫常发生在哪些国家？
太一：鼠疫是一种全球性传染病，主要分布在温带和寒带地区。目前，鼠疫主要分布在亚洲、非洲和欧洲等地区。其中，亚洲地区是鼠疫的主要流行区，包括中国、蒙古、俄罗斯、朝鲜、韩国、日本等国家。非洲地区是鼠疫的高发区，包括非洲中部、南部、东部等地区。欧洲地区是鼠疫的高发区，包括欧洲中部、北部、东部等地区。" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语示例</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>User：Do you know colchicine?
Taiyi：Colchicine is a medication used to treat gout, a type of arthritis that causes joint pain, swelling, and redness. It works by reducing the amount of uric acid in the body.
User：Does it have any potential side effects?
Taiyi：Yes, Colchicine can have potential side effects. Some of the common side effects of Colchicine include nausea, vomiting, diarrhea, abdominal pain, and loss of appetite. However, there are also some rare but serious side effects of Colchicine, such as muscle weakness, confusion, and difficulty breathing. If you experience any of these side effects, you should seek medical attention immediately.
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="User：Do you know colchicine?
Taiyi：Colchicine is a medication used to treat gout, a type of arthritis that causes joint pain, swelling, and redness. It works by reducing the amount of uric acid in the body.
User：Does it have any potential side effects?
Taiyi：Yes, Colchicine can have potential side effects. Some of the common side effects of Colchicine include nausea, vomiting, diarrhea, abdominal pain, and loss of appetite. However, there are also some rare but serious side effects of Colchicine, such as muscle weakness, confusion, and difficulty breathing. If you experience any of these side effects, you should seek medical attention immediately." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3. 医疗报告生成</font></font></h3><a id="user-content-3-medical-report-generation" class="anchor" aria-label="永久链接：3. 医疗报告生成" href="#3-medical-report-generation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务介绍</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">医疗报告自动生成旨在总结诊断过程中的信息。该任务要求语言模型根据患者自我报告和医患对话生成指定格式的医疗报告。该任务可以帮助医生更有效地处理大量医疗信息，并为患者提供准确的诊断和治疗建议。</font></font></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></b></summary>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>问诊对话历史：
患者：小孩受凉了，流清鼻涕，咳嗽，应该是风寒咳嗽，去药店买哪种药好呢
医生：你好，宝宝咳嗽，流涕比较常见，西医角度上呼吸道感染可能性大，中医上叫做风寒咳嗽，请问宝宝除了咳嗽有没有其他不适症状呢？例如发热等，请详细描述一下，我好帮你诊治分析病情
患者：精神状态好，也没有发热，就是喉咙有一点痛，咳嗽
医生：先帮你分析一下病情，宝宝受凉之后免疫力降低，就会被细菌或病毒侵袭体内，气道分泌物增多，支气管平滑肌痉挛，咳嗽，咳痰，咽通。
医生：目前没有发热，宝宝病情不重，不用过分紧张的。
医生：我帮推荐治疗方法
医生：宝宝目前多大了？有没有再医院看过？做过化验检查
患者：嗯
患者：7岁，没去医院，做过很多检查，平常就是爱咳嗽，喉哝发炎
患者：医生说，扁桃体偏大
医生：近期这次有没有去医院看过？做过检查
医生：如果宝宝没有其他不适？可以口服氨溴索，桔贝合剂效果好
医生：另外如果条件允许，可以做做雾化吸入治疗直接作用与支气管粘膜，效果更直接
患者：不用做雾化吧，吃点药就行了
医生：也可以先吃药
患者：近期没有去过
医生：你们这次没有去医院看过？
患者：要吃消炎的吗
患者：没
患者：要吃消炎药吗
医生：你好，可以先不吃的
患者：那家里有蒲地蓝，可以吃吗
患者：口服液
患者：喉哝痛要吃吗
医生：先治疗看看，可以吃的，假如宝宝出现发热或咳嗽加重，医院就诊，复查血常规和胸片，那个时候再考虑加抗生素
患者：另外买个止咳的，行吗
医生：我们的观点是宝宝小，尽量少吃消炎药，可以先吃那几个药三天看看效果
患者：嗯谢谢
根据上述对话，给出诊疗报告
说明：诊疗报告分为主诉, 现病史, 辅助检查, 既往史, 诊断, 建议这六个章节。
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="问诊对话历史：
患者：小孩受凉了，流清鼻涕，咳嗽，应该是风寒咳嗽，去药店买哪种药好呢
医生：你好，宝宝咳嗽，流涕比较常见，西医角度上呼吸道感染可能性大，中医上叫做风寒咳嗽，请问宝宝除了咳嗽有没有其他不适症状呢？例如发热等，请详细描述一下，我好帮你诊治分析病情
患者：精神状态好，也没有发热，就是喉咙有一点痛，咳嗽
医生：先帮你分析一下病情，宝宝受凉之后免疫力降低，就会被细菌或病毒侵袭体内，气道分泌物增多，支气管平滑肌痉挛，咳嗽，咳痰，咽通。
医生：目前没有发热，宝宝病情不重，不用过分紧张的。
医生：我帮推荐治疗方法
医生：宝宝目前多大了？有没有再医院看过？做过化验检查
患者：嗯
患者：7岁，没去医院，做过很多检查，平常就是爱咳嗽，喉哝发炎
患者：医生说，扁桃体偏大
医生：近期这次有没有去医院看过？做过检查
医生：如果宝宝没有其他不适？可以口服氨溴索，桔贝合剂效果好
医生：另外如果条件允许，可以做做雾化吸入治疗直接作用与支气管粘膜，效果更直接
患者：不用做雾化吧，吃点药就行了
医生：也可以先吃药
患者：近期没有去过
医生：你们这次没有去医院看过？
患者：要吃消炎的吗
患者：没
患者：要吃消炎药吗
医生：你好，可以先不吃的
患者：那家里有蒲地蓝，可以吃吗
患者：口服液
患者：喉哝痛要吃吗
医生：先治疗看看，可以吃的，假如宝宝出现发热或咳嗽加重，医院就诊，复查血常规和胸片，那个时候再考虑加抗生素
患者：另外买个止咳的，行吗
医生：我们的观点是宝宝小，尽量少吃消炎药，可以先吃那几个药三天看看效果
患者：嗯谢谢
根据上述对话，给出诊疗报告
说明：诊疗报告分为主诉, 现病史, 辅助检查, 既往史, 诊断, 建议这六个章节。" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>上述问诊对话的诊疗报告如下：
主诉：咳嗽、流涕。
现病史：患儿无明显诱因下出现咳嗽、流涕，无恶心呕吐，无其他明显不适症状。精神状态一般，胃纳一般，余如常。
辅助检查：暂无。
既往史：既往体健。
诊断：小儿咳嗽。
建议：口服氨溴索、桔贝合剂，密观。
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="上述问诊对话的诊疗报告如下：
主诉：咳嗽、流涕。
现病史：患儿无明显诱因下出现咳嗽、流涕，无恶心呕吐，无其他明显不适症状。精神状态一般，胃纳一般，余如常。
辅助检查：暂无。
既往史：既往体健。
诊断：小儿咳嗽。
建议：口服氨溴索、桔贝合剂，密观。" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.生物医学信息提取</font></font></h3><a id="user-content-4-biomedical-information-extraction" class="anchor" aria-label="永久链接：4.生物医学信息提取" href="#4-biomedical-information-extraction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.1 命名实体识别</font></font></h4><a id="user-content-41-named-entity-recognition" class="anchor" aria-label="永久链接：4.1 命名实体识别" href="#41-named-entity-recognition"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务介绍</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生物医学命名实体识别旨在从文本中识别预定义的生物医学实体。这些实体可以包括生物医学概念，例如疾病、药物、基因、蛋白质等。</font></font></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></b></summary>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>从下面文本中识别出指定的实体类型：
治疗以选用大环内酯类抗生素，沙眼衣原体肺炎也可用磺胺二甲基异唑，年长儿和成人用氟喹诺酮类效果也很好。
实体类型：疾病，药物
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="从下面文本中识别出指定的实体类型：
治疗以选用大环内酯类抗生素，沙眼衣原体肺炎也可用磺胺二甲基异唑，年长儿和成人用氟喹诺酮类效果也很好。
实体类型：疾病，药物" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>疾病：沙眼衣原体肺炎
药物：大环内酯类抗生素; 磺胺二甲基异唑; 氟喹诺酮类
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="疾病：沙眼衣原体肺炎
药物：大环内酯类抗生素; 磺胺二甲基异唑; 氟喹诺酮类" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Extract the gene, disease entities from the following text:
Identification of a novel FBN1 gene mutation in a Chinese family with Marfan syndrome.
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Extract the gene, disease entities from the following text:
Identification of a novel FBN1 gene mutation in a Chinese family with Marfan syndrome." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>gene: FBN1
disease: Marfan syndrome
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="gene: FBN1
disease: Marfan syndrome" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.2 关系抽取</font></font></h4><a id="user-content-42-relation-extraction" class="anchor" aria-label="永久链接：4.2 关系提取" href="#42-relation-extraction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务介绍</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生物医学关系提取旨在从文本中自动提取生物医学实体之间的预定义关系或关联，例如蛋白质与基因之间的相互作用、药物与疾病之间的治疗关系等等。</font></font></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></b></summary>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>给出句子中药物治疗关系类型的实体对：慢性阻塞性肺疾病@减少急性加重：有高质量的证据证实，β2 受体激动剂在减少 12-52 周急性加重方面比安慰剂更有效。
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="给出句子中药物治疗关系类型的实体对：慢性阻塞性肺疾病@减少急性加重：有高质量的证据证实，β2 受体激动剂在减少 12-52 周急性加重方面比安慰剂更有效。" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>具有药物治疗关系的实体对如下：[慢性阻塞性肺疾病, β2 受体激动剂]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="具有药物治疗关系的实体对如下：[慢性阻塞性肺疾病, β2 受体激动剂]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Find the relations of drug entity pairs in the text：
Mitotane has been reported to accelerate the metabolism of warfarin by the mechanism of hepatic microsomal enzyme induction, leading to an increase in dosage requirements for warfarin. Therefore, physicians should closely monitor patients for a change in anticoagulant dosage requirements when administering Mitotane to patients on coumarin-type anticoagulants. In addition, Mitotane should be given with caution to patients receiving other drugs susceptible to the influence of hepatic enzyme induction.
Relation Types: ADVISE, MECHANISM, EFFECT, INT
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Find the relations of drug entity pairs in the text：
Mitotane has been reported to accelerate the metabolism of warfarin by the mechanism of hepatic microsomal enzyme induction, leading to an increase in dosage requirements for warfarin. Therefore, physicians should closely monitor patients for a change in anticoagulant dosage requirements when administering Mitotane to patients on coumarin-type anticoagulants. In addition, Mitotane should be given with caution to patients receiving other drugs susceptible to the influence of hepatic enzyme induction.
Relation Types: ADVISE, MECHANISM, EFFECT, INT" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>ADVISE: [Mitotane, coumarin-type anticoagulants]
MECHANISM: [Mitotane, warfarin]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="ADVISE: [Mitotane, coumarin-type anticoagulants]
MECHANISM: [Mitotane, warfarin]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.3 事件提取</font></font></h4><a id="user-content-43-event-extraction" class="anchor" aria-label="永久链接：4.3 事件提取" href="#43-event-extraction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务介绍</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生物医学事件提取是从非结构化的海量生物医学文献中提取结构化的生物医学事件，挖掘文献中描述的生物实体，以及生物医学事件之间的细粒度关系。该任务可以节省人工审阅文献的时间，为相关数据库建设、疾病诊断、预防研究等提供支持。</font></font></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></b></summary>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>找出指定的临床发现事件属性：
因患者需期末考试，故予以口服“雷贝拉唑钠肠溶片”治疗，现腹痛情况明显好转。
事件抽取说明：临床发现事件由主体词，发生状态，描述词和解剖部位组成
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="找出指定的临床发现事件属性：
因患者需期末考试，故予以口服“雷贝拉唑钠肠溶片”治疗，现腹痛情况明显好转。
事件抽取说明：临床发现事件由主体词，发生状态，描述词和解剖部位组成" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>上述句子中的临床发现事件如下：
主体词：疼痛；发生状态：；描述词：明显好转；解剖部位：腹
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="上述句子中的临床发现事件如下：
主体词：疼痛；发生状态：；描述词：明显好转；解剖部位：腹" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Input text: "Contaminated drinking water is responsible for causing diarrheal diseases that kill millions of people a year.
Even Types: Treatment of disease, Cause of disease
Role Types: Cause, Theme
Please extract events from the input text.
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Input text: &quot;Contaminated drinking water is responsible for causing diarrheal diseases that kill millions of people a year.
Even Types: Treatment of disease, Cause of disease
Role Types: Cause, Theme
Please extract events from the input text." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Cause of disease: (Trigger: responsible, Theme: diarrheal diseases, Cause: Contaminated drinking water]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Cause of disease: (Trigger: responsible, Theme: diarrheal diseases, Cause: Contaminated drinking water]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5. 机器翻译</font></font></h3><a id="user-content-5-machine-translation" class="anchor" aria-label="永久链接：5.机器翻译" href="#5-machine-translation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务介绍</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器翻译可以将生物医学文本从一种自然语言转换为另一种自然语言。此任务可以协助将各种医疗问题和建议、疾病名称、症状和其他信息进行英汉互译。</font></font></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></b></summary>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">汉英翻译实例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>将下面文本翻译成英文：
光动力疗法（PDT）作为一种新兴的肿瘤治疗手段，因其不良反应较少、靶向性好、可重复治疗等优点，已广泛应用于临床多种肿瘤的治疗。相比于手术、化疗及放疗等传统治疗策略，光动力疗法不仅可杀伤原位肿瘤，还可通过激活机体的免疫效应对转移瘤发挥抑制作用。然而，PDT诱导免疫效应的高低受多种因素影响，包括光敏剂在细胞内的定位和剂量、光参数、肿瘤内的氧浓度、免疫功能的完整性等。本文针对PDT介导抗肿瘤免疫效应的相关机制，以及PDT免疫效应的主要影响因素进行综述，以探讨PDT用于肿瘤治疗的未来发展方向。
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="将下面文本翻译成英文：
光动力疗法（PDT）作为一种新兴的肿瘤治疗手段，因其不良反应较少、靶向性好、可重复治疗等优点，已广泛应用于临床多种肿瘤的治疗。相比于手术、化疗及放疗等传统治疗策略，光动力疗法不仅可杀伤原位肿瘤，还可通过激活机体的免疫效应对转移瘤发挥抑制作用。然而，PDT诱导免疫效应的高低受多种因素影响，包括光敏剂在细胞内的定位和剂量、光参数、肿瘤内的氧浓度、免疫功能的完整性等。本文针对PDT介导抗肿瘤免疫效应的相关机制，以及PDT免疫效应的主要影响因素进行综述，以探讨PDT用于肿瘤治疗的未来发展方向。" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>As a new tumor treatment method, photodynamic therapy (pdt) has been widely used in clinical practice because of its advantages of few side effects, good targeting, and repeatability. Compared with traditional treatment strategies, such as surgery, chemotherapy, and radiotherapy, pdt can not only kill the primary tumor, but also inhibit the metastatic tumor by activating the body's immune effect. However, the induction of immune effect by pdt is affected by many factors, including the localization and dose of photosensitizers in cells, light parameters, oxygen concentration in tumor, and the integrity of immune function. In this review, we focus on themechanisms of antitumor immune effect mediated by pdt, and the main influencing factors of immune effect of pdt, to discuss the future development direction of pdt in thetumor treatment.
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="As a new tumor treatment method, photodynamic therapy (pdt) has been widely used in clinical practice because of its advantages of few side effects, good targeting, and repeatability. Compared with traditional treatment strategies, such as surgery, chemotherapy, and radiotherapy, pdt can not only kill the primary tumor, but also inhibit the metastatic tumor by activating the body's immune effect. However, the induction of immune effect by pdt is affected by many factors, including the localization and dose of photosensitizers in cells, light parameters, oxygen concentration in tumor, and the integrity of immune function. In this review, we focus on themechanisms of antitumor immune effect mediated by pdt, and the main influencing factors of immune effect of pdt, to discuss the future development direction of pdt in thetumor treatment." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英汉翻译示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Translate the following text into Chinese:
Metabolic-associated fatty liver disease (MAFLD), formerly known as non-alcoholic fatty liver disease (NAFLD), is one of the most popular chronic liver diseases in the world. There are many explorations on the epidemiology and risk factors of the disease published in recent years. With the increasing burden of MAFLD on medical care and social economy, drug treatment of MAFLD has become an urgent research hotspot. Based on this, the current epidemiological status, risk factors, diagnostic criteria and treatment of MAFLD were summarized in this review in order to enlighten the clinical practice and scientific research of MAFLD.
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Translate the following text into Chinese:
Metabolic-associated fatty liver disease (MAFLD), formerly known as non-alcoholic fatty liver disease (NAFLD), is one of the most popular chronic liver diseases in the world. There are many explorations on the epidemiology and risk factors of the disease published in recent years. With the increasing burden of MAFLD on medical care and social economy, drug treatment of MAFLD has become an urgent research hotspot. Based on this, the current epidemiological status, risk factors, diagnostic criteria and treatment of MAFLD were summarized in this review in order to enlighten the clinical practice and scientific research of MAFLD." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>代谢相关脂肪肝病(Metabolic Associated Fatty Liver Disease,MAFLD)又称非酒精性脂肪性肝病(Non Alcoholic Fatty Liver Disease,NAFLD)，是目前全球最为流行的慢性肝病之一。近年来，关于该病的的流行病学和危险因素的探索性研究颇多。随着MAFLD对医疗和经济的负担日益加重，其药物治疗已成为研究的热点。基于此，本文对该病的流行病学现状、危险因素、诊断标准和治疗进行了总结,以期为临床实践和科学研究提供参考。
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="代谢相关脂肪肝病(Metabolic Associated Fatty Liver Disease,MAFLD)又称非酒精性脂肪性肝病(Non Alcoholic Fatty Liver Disease,NAFLD)，是目前全球最为流行的慢性肝病之一。近年来，关于该病的的流行病学和危险因素的探索性研究颇多。随着MAFLD对医疗和经济的负担日益加重，其药物治疗已成为研究的热点。基于此，本文对该病的流行病学现状、危险因素、诊断标准和治疗进行了总结,以期为临床实践和科学研究提供参考。" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6. 标题生成</font></font></h3><a id="user-content-6-title-generation" class="anchor" aria-label="永久链接：6.标题生成" href="#6-title-generation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务介绍</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标题生成旨在为输入的生物医学文本段落生成信息丰富的文章标题并进行摘要。</font></font></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></b></summary>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>请给下面摘要起标题：
气管食管瘘是指气管或支气管与食管之间的病理性瘘道，包括气管-食管瘘和支气管-食管瘘，临床以气管-食管瘘较多见。气管食管瘘致病原因较多，可引起严重的并发症，是对患者生活质量影响显著、治疗困难和病死率较高的疾病。气管食管瘘目前治疗方式较多，但多数疗效欠佳，对新兴治疗手段的需求迫切。胸腹部X线摄影检出鼻胃管滞留是气管食管瘘诊断的金标准，其主要治疗方法包括外科手术治疗、支架置入、局部生物胶水封闭、干细胞治疗等。本文综述近年气管食管瘘诊断与治疗的主要研究进展，旨在为该病的临床诊治提供参考。
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="请给下面摘要起标题：
气管食管瘘是指气管或支气管与食管之间的病理性瘘道，包括气管-食管瘘和支气管-食管瘘，临床以气管-食管瘘较多见。气管食管瘘致病原因较多，可引起严重的并发症，是对患者生活质量影响显著、治疗困难和病死率较高的疾病。气管食管瘘目前治疗方式较多，但多数疗效欠佳，对新兴治疗手段的需求迫切。胸腹部X线摄影检出鼻胃管滞留是气管食管瘘诊断的金标准，其主要治疗方法包括外科手术治疗、支架置入、局部生物胶水封闭、干细胞治疗等。本文综述近年气管食管瘘诊断与治疗的主要研究进展，旨在为该病的临床诊治提供参考。" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>气管食管瘘诊断与治疗进展
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="气管食管瘘诊断与治疗进展" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Output a title for the following abstract:
The incidence of diabetes mellitus has been increasing, prompting the search for non-invasive diagnostic methods. Although current methods exist, these have certain limitations, such as low reliability and accuracy, difficulty in individual patient adjustment, and discomfort during use. This paper presents a novel approach for diagnosing diabetes using high-frequency ultrasound (HFU) and a convolutional neural network (CNN). This method is based on the observation that glucose in red blood cells (RBCs) forms glycated hemoglobin (HbA1c) and accumulates on its surface. The study incubated RBCs with different glucose concentrations, collected acoustic reflection signals from them using a custom-designed 90-MHz transducer, and analyzed the signals using a CNN. The CNN was applied to the frequency spectra and spectrograms of the signal to identify correlations between changes in RBC properties owing to glucose concentration and signal features. The results confirmed the efficacy of the CNN-based approach with a classification accuracy of 0.98. This non-invasive diagnostic technology using HFU and CNN holds promise for in vivo diagnosis without the need for blood collection.
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Output a title for the following abstract:
The incidence of diabetes mellitus has been increasing, prompting the search for non-invasive diagnostic methods. Although current methods exist, these have certain limitations, such as low reliability and accuracy, difficulty in individual patient adjustment, and discomfort during use. This paper presents a novel approach for diagnosing diabetes using high-frequency ultrasound (HFU) and a convolutional neural network (CNN). This method is based on the observation that glucose in red blood cells (RBCs) forms glycated hemoglobin (HbA1c) and accumulates on its surface. The study incubated RBCs with different glucose concentrations, collected acoustic reflection signals from them using a custom-designed 90-MHz transducer, and analyzed the signals using a CNN. The CNN was applied to the frequency spectra and spectrograms of the signal to identify correlations between changes in RBC properties owing to glucose concentration and signal features. The results confirmed the efficacy of the CNN-based approach with a classification accuracy of 0.98. This non-invasive diagnostic technology using HFU and CNN holds promise for in vivo diagnosis without the need for blood collection." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>A novel approach for diagnosing diabetes using high-frequency ultrasound and a convolutional neural network
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="A novel approach for diagnosing diabetes using high-frequency ultrasound and a convolutional neural network" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">7. 文本分类</font></font></h3><a id="user-content-7-text-classification" class="anchor" aria-label="永久链接：7.文本分类" href="#7-text-classification"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务介绍</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生物医学文本分类旨在自动将生物医学文本分类为预定义的类别标签，帮助医疗保健专业人员、研究人员和机构更好地管理和分析医疗信息。</font></font></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></b></summary>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>现有以下文本：
治皮肤病费用大概多少？
请将上述文本分类至指定类别中：医疗费用，后果表述，指标解读，病情诊断，就医建议，疾病描述，其他，治疗方案，病因分析，功效作用，注意事项
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="现有以下文本：
治皮肤病费用大概多少？
请将上述文本分类至指定类别中：医疗费用，后果表述，指标解读，病情诊断，就医建议，疾病描述，其他，治疗方案，病因分析，功效作用，注意事项" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>上述文本被分类为：医疗费用
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="上述文本被分类为：医疗费用" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Document triage: "Will my mask from sherwin williams paint store with filters protect me from corona virus along with paint fumes?"
Labels: patient, doctor
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Document triage: &quot;Will my mask from sherwin williams paint store with filters protect me from corona virus along with paint fumes?&quot;
Labels: patient, doctor" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Result: patient
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Result: patient" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8. 文本语义相似度</font></font></h3><a id="user-content-8-text-semantic-similarity" class="anchor" aria-label="永久链接：8.文本语义相似度" href="#8-text-semantic-similarity"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务介绍</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本语义相似度旨在确定两个医学文本之间的关联或相似程度。该任务通常涉及文本匹配、相似性测量和语义理&ZeroWidthSpace;&ZeroWidthSpace;解，并且可用于各种应用，例如医学信息检索和文档匹配。</font></font></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></b></summary>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中文示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>语句1：乙肝小二阳会转成小三阳吗？
语句2：乙肝小三阳会不会转成肝硬化、肝癌？
请从下面选项中评估这段文本的语义相似度：语义不相同，语义相同
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="语句1：乙肝小二阳会转成小三阳吗？
语句2：乙肝小三阳会不会转成肝硬化、肝癌？
请从下面选项中评估这段文本的语义相似度：语义不相同，语义相同" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>语义不相同
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="语义不相同" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英语示例</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户输入：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>1. How can someone's happiness level affect someone's health?
2. Can staying happy improve my health? What specific steps should I take?
Assess the semantic similarity of the text pairs based on the following labels: dissimilar, similar
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="1. How can someone's happiness level affect someone's health?
2. Can staying happy improve my health? What specific steps should I take?
Assess the semantic similarity of the text pairs based on the following labels: dissimilar, similar" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙输出：</font></font></strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>similar
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="similar" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">训练数据</font></font></h2><a id="user-content-training-data" class="anchor" aria-label="永久链接：训练数据" href="#training-data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据采集</font></font></h3><a id="user-content-data-collection" class="anchor" aria-label="永久链接：数据收集" href="#data-collection"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了充分利用现有的生物医学自然语言处理数据集，该项目共收集了170个中英文开源数据集。其中，涵盖10个BioNLP任务的中文数据集有38个，涵盖12个BioNLP任务的英文数据集有131个。下图提供了数据集的概述。</font></font></p>
<p align="center" dir="auto">
    <br>
    <a target="_blank" rel="noopener noreferrer" href="/DUTIR-BioNLP/Taiyi-LLM/blob/main/fig/data_overview.png?raw=true"><img src="/DUTIR-BioNLP/Taiyi-LLM/raw/main/fig/data_overview.png?raw=true" width="1200" height="350" style="max-width: 100%;"></a>
    <br>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目整理了每个数据集的信息，包括任务类型、数据规模、任务描述和相关数据链接。具体详情请参阅</font></font><a href="/DUTIR-BioNLP/Taiyi-LLM/blob/main/data_file/dataset_inf.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">《生物医学数据集概述》</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标准化数据格式</font></font></h3><a id="user-content-standardized-data-format" class="anchor" aria-label="固定链接：标准化数据格式" href="#standardized-data-format"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/bigscience-workshop/biomedical"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了方便后续的数据转换，本项目借鉴了BigBio</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目的灵感</font><font style="vertical-align: inherit;">，根据任务类型，设计了统一的数据格式。有关此标准化数据格式的具体详细信息，请参阅</font></font><a href="/DUTIR-BioNLP/Taiyi-LLM/blob/main/data_file/Task_schemas_en.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“DUTIR-BioNLP Data Schema Documentation”</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并且数据已转换为符合此标准化格式。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指令调整数据</font></font></h3><a id="user-content-instruction-tuning-data" class="anchor" aria-label="永久链接：指令调整数据" href="#instruction-tuning-data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据数据质量筛选和选择数据集后，基于</font></font><a href="https://github.com/michael-wzhu/PromptCBLUE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PromptCBLUE</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目设计教学模板，并按照标准化数据格式转换数据。指令调整数据汇总如下表所示：</font></font></p>
<table>
<tbody><tr>
  <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务类型</font></font></th>
  <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中国数据规模</font></font></th>
  <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英文数据量表</font></font></th>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命名实体识别</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">44,667</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">28,603</font></font></td>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关系抽取</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">26,606</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">17,279</font></font></td>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">事件提取</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2,992</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2,022</font></font></td>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本分类</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">37,624</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">40,339</font></font></td>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本对任务</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">45,548</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">11,237</font></font></td>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器翻译</font></font></td>
  <td colspan="2" align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">74,113</font></font></td>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单轮问答</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">129,562</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">57,962</font></font></td>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多轮对话</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">16,391</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10,000</font></font></td>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他附加任务</font></font></td>
  <td colspan="2" align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">9,370</font></font></td>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般对话数据</font></font></td>
  <td colspan="2" align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">560,000</font></font></td>
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全部的</font></font></td>
  <td colspan="2" align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1,114,315</font></font></td>
</tr>
</tbody></table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关训练所使用的指令数据的详细信息，请参阅</font></font><a href="/DUTIR-BioNLP/Taiyi-LLM/blob/main/data_file/final_instruction_data.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“指令-调优数据详细信息”</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型训练</font></font></h2><a id="user-content-model-training" class="anchor" aria-label="永久链接：模型训练" href="#model-training"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基础模型简介</font></font></h3><a id="user-content-introduction-to-the-base-model" class="anchor" aria-label="永久链接：基本模型简介" href="#introduction-to-the-base-model"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当前版本的太乙是基于</font></font><a href="https://huggingface.co/Qwen/Qwen-7B" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Qwen-7B基础</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型，通过Instruct-tuning进行了微调。 Qwen-7B是阿里云Qwen大模型系列中的70亿参数模型。它已经过超过 200 万亿个代币的预训练，涵盖中文、英文、多语言、代码、数学等高质量数据。培训语料库涵盖通用领域和专业领域。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">培训详情</font></font></h3><a id="user-content-training-details" class="anchor" aria-label="永久链接：培训详情" href="#training-details"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们使用 Qlora 在 6 个 Nvidia A40 48 GB GPU 上进行指令引导微调。我们的训练代码是基于</font></font><a href="https://github.com/yangjianxin1/Firefly"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Firefly</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目修改的。训练过程中使用的关键超参数如下：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>num_train_epochs:3
per_device_train_batch_size:12
gradient_accumulation_steps:2
learning_rate:0.0002
max_seq_length:1024
lr_scheduler_type:"constant_with_warmup"
warmup_ratio:0.1
lora_rank:64
lora_alpha:16
lora_dropout:0.05
weight_decay:0
max_grad_norm:0.3
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="num_train_epochs:3
per_device_train_batch_size:12
gradient_accumulation_steps:2
learning_rate:0.0002
max_seq_length:1024
lr_scheduler_type:&quot;constant_with_warmup&quot;
warmup_ratio:0.1
lora_rank:64
lora_alpha:16
lora_dropout:0.05
weight_decay:0
max_grad_norm:0.3" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的训练数据集包含大约 100 万个训练样本。每个训练周期大约需要两天才能完成。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">型号用途</font></font></h2><a id="user-content-model-usage" class="anchor" aria-label="永久链接：模型使用" href="#model-usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境设置</font></font></h3><a id="user-content-environment-setup" class="anchor" aria-label="永久链接：环境设置" href="#environment-setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们用于训练和测试的环境配置如下：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>torch==1.13.0
accelerate==0.21.0
transformers==4.30.2
peft==0.4.0
bitsandbytes==0.39.0
loguru==0.7.0
numpy
pandas==1.2.5
tqdm==4.62.3
deepspeed==0.9.5
tensorboard
sentencepiece
transformers_stream_generator
tiktoken
einops
scipy
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="torch==1.13.0
accelerate==0.21.0
transformers==4.30.2
peft==0.4.0
bitsandbytes==0.39.0
loguru==0.7.0
numpy
pandas==1.2.5
tqdm==4.62.3
deepspeed==0.9.5
tensorboard
sentencepiece
transformers_stream_generator
tiktoken
einops
scipy" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要使用以下命令自动安装所有依赖项：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ pip install -r requirements.txt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ pip install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型推理</font></font></h3><a id="user-content-model-inference" class="anchor" aria-label="永久链接：模型推理" href="#model-inference"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们将多轮对话连接成以下格式，然后将它们标记化。其中 eod 是 qwen 分词器中的特殊字符 &lt;|endoftext|&gt;。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>&lt;eod&gt;input1&lt;eod&gt;answer1&lt;eod&gt;input2&lt;eod&gt;answer2&lt;eod&gt;.....
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="<eod>input1<eod>answer1<eod>input2<eod>answer2<eod>....." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下代码可用于使用我们的模型执行推理：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">transformers</span> <span class="pl-k">import</span> <span class="pl-v">AutoModelForCausalLM</span>, <span class="pl-v">AutoTokenizer</span>
<span class="pl-k">import</span> <span class="pl-s1">torch</span>

<span class="pl-s1">model_name</span> <span class="pl-c1">=</span> <span class="pl-s">"DUTIR-BioNLP/Taiyi-LLM"</span>

<span class="pl-s1">device</span> <span class="pl-c1">=</span> <span class="pl-s">'cuda:0'</span>

<span class="pl-s1">model</span> <span class="pl-c1">=</span> <span class="pl-v">AutoModelForCausalLM</span>.<span class="pl-en">from_pretrained</span>(
    <span class="pl-s1">model_name</span>,
    <span class="pl-s1">low_cpu_mem_usage</span><span class="pl-c1">=</span><span class="pl-c1">True</span>,
    <span class="pl-s1">torch_dtype</span><span class="pl-c1">=</span><span class="pl-s1">torch</span>.<span class="pl-s1">float16</span>,
    <span class="pl-s1">trust_remote_code</span><span class="pl-c1">=</span><span class="pl-c1">True</span>,
    <span class="pl-s1">device_map</span> <span class="pl-c1">=</span> <span class="pl-s1">device</span>
)


<span class="pl-s1">model</span>.<span class="pl-en">eval</span>()
<span class="pl-s1">tokenizer</span> <span class="pl-c1">=</span> <span class="pl-v">AutoTokenizer</span>.<span class="pl-en">from_pretrained</span>(
    <span class="pl-s1">model_name</span>,
    <span class="pl-s1">trust_remote_code</span><span class="pl-c1">=</span><span class="pl-c1">True</span>
)

<span class="pl-k">import</span> <span class="pl-s1">logging</span>
<span class="pl-s1">logging</span>.<span class="pl-en">disable</span>(<span class="pl-s1">logging</span>.<span class="pl-v">WARNING</span>)
<span class="pl-s1">tokenizer</span>.<span class="pl-s1">pad_token_id</span> <span class="pl-c1">=</span> <span class="pl-s1">tokenizer</span>.<span class="pl-s1">eod_id</span>
<span class="pl-s1">tokenizer</span>.<span class="pl-s1">bos_token_id</span> <span class="pl-c1">=</span> <span class="pl-s1">tokenizer</span>.<span class="pl-s1">eod_id</span>
<span class="pl-s1">tokenizer</span>.<span class="pl-s1">eos_token_id</span> <span class="pl-c1">=</span> <span class="pl-s1">tokenizer</span>.<span class="pl-s1">eod_id</span>
<span class="pl-s1">history_token_ids</span> <span class="pl-c1">=</span> <span class="pl-s1">torch</span>.<span class="pl-en">tensor</span>([[]], <span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s1">torch</span>.<span class="pl-s1">long</span>)
<span class="pl-s1">max_new_tokens</span> <span class="pl-c1">=</span> <span class="pl-c1">500</span>
<span class="pl-s1">top_p</span> <span class="pl-c1">=</span> <span class="pl-c1">0.9</span>
<span class="pl-s1">temperature</span> <span class="pl-c1">=</span> <span class="pl-c1">0.3</span>
<span class="pl-s1">repetition_penalty</span> <span class="pl-c1">=</span> <span class="pl-c1">1.0</span>

<span class="pl-c"># begin chat</span>
<span class="pl-s1">history_max_len</span> <span class="pl-c1">=</span> <span class="pl-c1">1000</span> 
<span class="pl-s1">utterance_id</span> <span class="pl-c1">=</span> <span class="pl-c1">0</span>
<span class="pl-s1">history_token_ids</span> <span class="pl-c1">=</span> <span class="pl-c1">None</span>

<span class="pl-s1">user_input</span> <span class="pl-c1">=</span> <span class="pl-s">"Hi，could you please introduce yourself？"</span>

<span class="pl-s1">input_ids</span> <span class="pl-c1">=</span> <span class="pl-en">tokenizer</span>(<span class="pl-s1">user_input</span>, <span class="pl-s1">return_tensors</span><span class="pl-c1">=</span><span class="pl-s">"pt"</span>, <span class="pl-s1">add_special_tokens</span><span class="pl-c1">=</span><span class="pl-c1">False</span>).<span class="pl-s1">input_ids</span>
<span class="pl-s1">bos_token_id</span> <span class="pl-c1">=</span> <span class="pl-s1">torch</span>.<span class="pl-en">tensor</span>([[<span class="pl-s1">tokenizer</span>.<span class="pl-s1">bos_token_id</span>]], <span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s1">torch</span>.<span class="pl-s1">long</span>)
<span class="pl-s1">eos_token_id</span> <span class="pl-c1">=</span> <span class="pl-s1">torch</span>.<span class="pl-en">tensor</span>([[<span class="pl-s1">tokenizer</span>.<span class="pl-s1">eos_token_id</span>]], <span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s1">torch</span>.<span class="pl-s1">long</span>)
<span class="pl-s1">user_input_ids</span> <span class="pl-c1">=</span> <span class="pl-s1">torch</span>.<span class="pl-en">concat</span>([<span class="pl-s1">bos_token_id</span>,<span class="pl-s1">input_ids</span>, <span class="pl-s1">eos_token_id</span>], <span class="pl-s1">dim</span><span class="pl-c1">=</span><span class="pl-c1">1</span>)


<span class="pl-s1">model_input_ids</span> <span class="pl-c1">=</span> <span class="pl-s1">user_input_ids</span>.<span class="pl-en">to</span>(<span class="pl-s1">device</span>)
<span class="pl-k">with</span> <span class="pl-s1">torch</span>.<span class="pl-en">no_grad</span>():
    <span class="pl-s1">outputs</span> <span class="pl-c1">=</span> <span class="pl-s1">model</span>.<span class="pl-en">generate</span>(
        <span class="pl-s1">input_ids</span><span class="pl-c1">=</span><span class="pl-s1">model_input_ids</span>, <span class="pl-s1">max_new_tokens</span><span class="pl-c1">=</span><span class="pl-s1">max_new_tokens</span>, <span class="pl-s1">do_sample</span><span class="pl-c1">=</span><span class="pl-c1">True</span>, <span class="pl-s1">top_p</span><span class="pl-c1">=</span><span class="pl-s1">top_p</span>,
        <span class="pl-s1">temperature</span><span class="pl-c1">=</span><span class="pl-s1">temperature</span>, <span class="pl-s1">repetition_penalty</span><span class="pl-c1">=</span><span class="pl-s1">repetition_penalty</span>, <span class="pl-s1">eos_token_id</span><span class="pl-c1">=</span><span class="pl-s1">tokenizer</span>.<span class="pl-s1">eos_token_id</span>
    )

<span class="pl-s1">response</span> <span class="pl-c1">=</span> <span class="pl-s1">tokenizer</span>.<span class="pl-en">batch_decode</span>(<span class="pl-s1">outputs</span>)
<span class="pl-en">print</span>(<span class="pl-s1">response</span>[<span class="pl-c1">0</span>])
<span class="pl-c">#&lt;|endoftext|&gt;Hi，could you please introduce yourself？&lt;|endoftext|&gt;Hello! My name is Taiyi,.....&lt;|endoftext|&gt;</span></pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们提供了两个对话测试代码。您可以使用 中的代码</font></font><code>dialogue_one_trun.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来测试单轮 QA 对话，或使用 中的示例代码来</font></font><code>dialogue_multi_trun.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试多轮对话 QA。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：为了保证快速的推理速度，我们建议使用4090 GPU。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整体表现</font></font></h2><a id="user-content-overall-performance" class="anchor" aria-label="永久链接：整体表现" href="#overall-performance"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<tbody><tr>
  <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务类型</font></font></th>
  <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据集</font></font></th>
  <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙</font></font></th>
  <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聊天GPT3.5</font></font></th>
  <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">索塔</font></font></th>  
</tr>
<tr>
  <td rowspan="5"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NER(微型-F1)
  </font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BC5CDR-化学</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">80.2</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">60.3</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">93.3（PubMedBERT）</font></font></td>  
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BC5CDR-迪斯</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">69.1</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">51.8</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">85.6（PubMedBERT）</font></font></td>  
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">切德纳</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">79.9</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">36.5</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">92.4（BioBERT）</font></font></td>  
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NCBI疾病</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">73.1</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">50.5</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">87.8（PubMedBERT）</font></font></td>  
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CMeEE-开发</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">65.7</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">47.0</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">74.0(C蓝)</font></font></td>  
</tr>
<tr>
  <td rowspan="2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RE(微型-F1)
  </font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BC5CDR</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">37.5</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">14.2</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">45.0(生物GPT)</font></font></td>  
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CMeIE-dev</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">43.2</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">30.6</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">54.9(C蓝)</font></font></td>  
</tr>
<tr>
  <td rowspan="3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TC(微型-F1)
  </font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BC7LitCovid</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">84.0</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">63.9</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">91.8（生物形成剂）</font></font></td>  
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HOC</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">80.0</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">51.2</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">82.3（PubMedBERT）</font></font></td>  
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KUAKE_QIC-dev</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">77.4</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">48.5</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">85.9(C蓝)</font></font></td>  
</tr>
<tr>
  <td rowspan="3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">质量保证（准确度）
  </font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公共医学质量保证</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">54.4</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">76.5</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">55.8（PubMedBERT）</font></font></td>  
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">美国医师执照考试</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">37.1</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">51.3</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">36.7（BioBERT-大）</font></font></td>  
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">医学质量保证-MCMLE</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">64.8</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">58.2</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">70.1(RoBERTA-大)</font></font></td>  
</tr>
<tr>
  <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全部
  </font></font></td><td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AVE</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">64.8</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">49.3</font></font></td>
  <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">73.5</font></font></td>  
</tr>
</tbody></table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">限制和未来的工作</font></font></h2><a id="user-content-limitation-and-future-work" class="anchor" aria-label="永久链接：限制和未来的工作" href="#limitation-and-future-work"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">局限性</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目的目标是探索生物医学领域大模型的中英双语自然语言处理能力。但目前太乙模型还存在一些必须考虑的缺点：</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">误解：与所有主要语言模型一样，存在误解或曲解的风险，特别是在处理生物医学领域的专业术语或复杂概念时。在这种情况下，我们的模型可能会提供不准确的答案或解释。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">幻觉：大型语言模型有时会对给定输入产生无意义或完全不相关的响应。当用户不熟悉讨论主题时，这种“幻觉”可能尤其成问题，因为他们可能无法轻松识别模型输出中的错误。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">信息有限：尽管我们致力于成为生物医学领域的综合语言模型，但模型的知识仍然有限，可能无法涵盖每个领域或专业的所有方面。用户应注意模型中的信息可能并不全面，在需要深入或专业知识时请谨慎使用。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">偏差：模型的训练数据可能包含偏差，这可能会反映在模型的响应中。我们努力减少偏见，但无法完全消除它。用户应谨慎处理模型响应中潜在的偏差问题。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有限的长多轮对话能力：由于我们团队当前的计算限制，我们在训练期间可以设置的最大令牌长度为1024。因此，我们当前的模型在相对较短的对话（大约5轮）中最具竞争力。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有限的主题切换能力：由于当前信息和计算资源的限制，我们的模型在涵盖多个主题的大跨度的多轮对话中可能表现出不稳定。因此，用户在与太乙对话时，应尽量保持对话主题的一致性。</font></font></p>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注：太乙模型旨在提供信息和知识，但不应替代医疗专业人员的建议或诊断。任何涉及个人健康的决定都应咨询专业医务人员。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">未来的工作</font></font></strong></p>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源数据和技术稿件：整理完善数据资源和模型训练技术稿件，未来将开源发布。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">持续预训练：由于当前计算资源限制，当前版本的太乙主要进行指令数据微调，并没有使用海量生物医学资源来持续预训练。未来，该项目将探索利用生物医学领域的大型模型库资源来进一步进行预训练。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强化学习提高性能：该项目将探索如何使用强化学习方法进一步提高模型的性能并调整人类意图。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">增强可解释性：与一般领域相比，生物医学领域要求模型预测结果具有更高的可解释性。未来，我们将探索太乙在各种BioNLP任务上的可解释方法。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全性增强：虽然本项目增加了训练的安全数据，但生物医学领域的模型安全性仍然不足。我们将继续探索如何利用生物医学知识库来增强模型安全性。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">......</font></font></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发团队</font></font></h2><a id="user-content-development-team" class="anchor" aria-label="永久链接：开发团队" href="#development-team"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><a href="http://ir.dlut.edu.cn/" rel="nofollow"><font style="vertical-align: inherit;">太一由大连理工大学信息检索研究实验室（DUTIR）</font></a><font style="vertical-align: inherit;">开发</font></font><a href="http://ir.dlut.edu.cn/" rel="nofollow"><font style="vertical-align: inherit;"></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监事：</font></font><a href="http://faculty.dlut.edu.cn/luoling/en/index.htm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">罗凌</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、杨志豪、王健、孙媛媛、林鸿飞</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">学生成员：宁金中、赵英文、丁泽元、陈鹏、付伟儒、韩勤宇、徐光涛、邱云志、潘鼎浩、李吉如、王志军、李浩、冯文多、屠森波、刘玉琪</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></h2><a id="user-content-acknowledgements" class="anchor" aria-label="永久链接：致谢" href="#acknowledgements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目的工作受到以下开源项目和技术的启发和协助。我们谨向这些项目的开发者和贡献者表示感谢，包括但不限于：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Qwen：</font></font><a href="https://github.com/QwenLM/Qwen"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/QwenLM/Qwen</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">萤火虫：</font></font><a href="https://github.com/yangjianxin1/Firefly"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/yangjianxin1/Firefly</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BigBIO：</font></font><a href="https://github.com/bigscience-workshop/biomedical"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/bigscience-workshop/biomedical</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提示CBLUE：</font></font><a href="https://github.com/michael-wzhu/PromptCBLUE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/michael-wzhu/PromptCBLUE</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">太乙标志由ERNIE Bot合成</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免责声明</font></font></h2><a id="user-content-disclaimer" class="anchor" aria-label="永久链接：免责声明" href="#disclaimer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本项目相关资源仅供学术研究用途，严禁用于商业用途。本仓库源代码的使用遵循开源许可协议</font></font><a href="https://github.com/DUTIR-BioNLP/Taiyi-LLM/blob/main/LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache 2.0</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。用户在使用过程中，请仔细阅读并遵守以下声明：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请确保您输入的内容不侵犯他人权益，不涉及不良信息，不含有任何涉及政治、暴力、色情的内容，所有输入内容合法合规。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请确认并注意，所有使用太乙模型生成的内容均由人工智能模型生成，生成的内容并不完全理性。本项目不保证生成内容的准确性、完整性、功能性，也不承担任何法律责任。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本模型中任何违反法律法规、公序良俗的回应，均不代表本项目的态度、观点或立场。本项目将不断完善模型反应，使其更加符合社会伦理和道德规范。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于模型输出的任何内容，用户应自行承担风险和责任。本项目不承担任何法律责任，也不承担因使用相关资源和产出结果可能产生的任何损失。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本项目中出现的第三方链接或库只是为了方便起见，其内容和观点与本项目无关。用户使用时需自行区分，本项目不承担任何连带责任；</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果用户发现项目中存在重大错误，请向我们反馈，以帮助我们及时修复。</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用本项目即表示您已仔细阅读、理解并同意遵守上述免责声明。本项目保留修改本声明的权利，恕不另行通知任何人。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></h2><a id="user-content-citation" class="anchor" aria-label="永久链接：引文" href="#citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用该项目的存储库，请引用它。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@article{Taiyi,
  title="{Taiyi: A Bilingual Fine-Tuned Large Language Model for Diverse Biomedical Tasks}",
  author={Ling Luo, Jinzhong Ning, Yingwen Zhao, Zhijun Wang, Zeyuan Ding, Peng Chen, Weiru Fu, Qinyu Han, Guangtao Xu, Yunzhi Qiu, Dinghao Pan, Jiru Li, Hao Li, Wenduo Feng, Senbo Tu, Yuqi Liu, Zhihao Yang, Jian Wang, Yuanyuan Sun, Hongfei Lin},
  journal={Journal of the American Medical Informatics Association},
  year={2024},
  doi = {10.1093/jamia/ocae037},
  url = {https://doi.org/10.1093/jamia/ocae037},
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@article{Taiyi,
  title=&quot;{Taiyi: A Bilingual Fine-Tuned Large Language Model for Diverse Biomedical Tasks}&quot;,
  author={Ling Luo, Jinzhong Ning, Yingwen Zhao, Zhijun Wang, Zeyuan Ding, Peng Chen, Weiru Fu, Qinyu Han, Guangtao Xu, Yunzhi Qiu, Dinghao Pan, Jiru Li, Hao Li, Wenduo Feng, Senbo Tu, Yuqi Liu, Zhihao Yang, Jian Wang, Yuanyuan Sun, Hongfei Lin},
  journal={Journal of the American Medical Informatics Association},
  year={2024},
  doi = {10.1093/jamia/ocae037},
  url = {https://doi.org/10.1093/jamia/ocae037},
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">明星历史</font></font></h2><a id="user-content-star-history" class="anchor" aria-label="永久链接：明星历史" href="#star-history"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://star-history.com/#DUTIR-BioNLP/Taiyi-LLM&amp;Date" rel="nofollow"><img src="https://camo.githubusercontent.com/63f717bc1f0d24b0357e1b9944242099eaecbea074eae814e2d703b7a3bf507b/68747470733a2f2f6170692e737461722d686973746f72792e636f6d2f7376673f7265706f733d44555449522d42696f4e4c502f54616979692d4c4c4d26747970653d44617465" alt="明星历史图" data-canonical-src="https://api.star-history.com/svg?repos=DUTIR-BioNLP/Taiyi-LLM&amp;type=Date" style="max-width: 100%;"></a></p>
</article></div>
