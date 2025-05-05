# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Preface/section
本章探讨了大型语言模型（LLMs）在实现智能代理方面的关键作用。虽然LLMs在推理和生成方面取得了重大进展，但仍未完全展现出智能生物的所有能力。本文将LLMs视为智能代理的引擎，强调了构建完全智能代理的需求。在LLMs提供的基础上，设计和构建智能代理需要更多功能，如长期记忆、自主执行动作等。通过引入LLMs与代理之间的引擎-车辆类比，本章提出了一系列关键问题，挑战了当前技术在实现完全智能代理方面的局限性，并探讨了未来研究方向。本章分为四个部分，涵盖了个体代理的能力要求、代理的进化能力、代理社会和伦理责任等内容，旨在激励读者提出新问题并加入对智能代理领域的探索。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Preface/section/0/text
1. 如何将大型语言模型（LLMs）作为智能代理的引擎，与构建完全智能代理所需的其他功能相结合，以实现更接近人类智能的目标？  2. 在追求真正“智能”的系统时，除了LLMs展现的推理和生成能力，还需要哪些能力和特征来构建具有长期记忆、自主执行动作等功能的完全智能代理？  3. 如何利用LLMs与代理之间的引擎-车辆类比，挑战当前技术在实现完全智能代理方面的局限性，并探索未来智能代理领域的研究方向？
大型语言模型（LLMs）通过展示在自然语言和多模态理解以及推理和生成方面的前所未有能力，彻底改变了人工智能（AI）。这些模型在庞大数据集上训练，并展现出诸如推理、上下文学习甚至元规划等新兴能力。虽然这些模型代表了实现智能机器的重要进步，但它们本身尚未完全体现出智能生物的所有能力。自人工智能早期以来，AI研究人员一直在追求一个真正“智能”的系统，该系统能够学习、规划、推理、感知、交流、行动、记忆，并展示各种类似人类的能力和灵活性。这些被称为智能代理的存在应能够进行长期和短期思考，执行复杂动作，并与人类和其他代理进行互动。LLMs是实现智能代理的重要一步，但我们尚未达到这一目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Preface/section/1/text
1. 在构建完全智能代理时，基于LLMs的引擎-车辆类比中，如何平衡利用LLMs提供的基础功能与设计更多功能的挑战？    2. 在当前技术现状下，如何解决LLMs在生成复杂计划、保持长期记忆和自主执行动作等方面的局限性，以实现完全智能代理的目标？    3. 在探讨LLMs作为智能代理引擎的同时，如何推动智能代理领域的研究，以满足个体代理的能力要求、进化能力和社会伦理责任等方面的挑战？
本文全面概述了基于LLMs的智能代理的当前技术现状。过去，关于智能代理的研究论文和书籍层出不穷，同时也有大量关于LLMs的书籍涌现。然而，很少有综合涵盖两者的内容。虽然LLMs可以实现代理所需的重要功能，但它们仅提供了必须构建更多功能的基础。例如，虽然LLMs可以帮助生成旅行计划等计划，但它们尚不能为复杂和专业任务生成完全复杂的计划，也无法在没有幻觉的情况下保持长期记忆。此外，它们在自主执行现实世界动作方面的能力仍然有限。我们可以将LLMs视为引擎，而代理则是使用这些引擎构建的汽车、船舶和飞机。在这个视角下，我们自然而然地寻求通过充分利用LLMs提供的能力，设计和构建完全运转的智能代理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Preface/section/2/text
1. 基于当前的LLM技术，智能代理的能力有多少可以提供？有哪些功能尚无法实现？ 2. 除了LMs，还需要做什么才能拥有一个能够在物理世界中进行自主行动和互动的完整智能代理？ 3. 一旦我们拥有完全智能的基于LLM的代理，社会将会产生哪些影响，我们应该如何为这个未来做准备？
在LLMs与代理之间的引擎-车辆类比中，我们自然地会问：基于当前的LLM技术，智能代理的能力有多少可以提供？基于当前的LLM技术，有哪些功能尚无法实现？除了LMs，还需要做什么才能拥有一个能够在物理世界中进行自主行动和互动的完整智能代理？完全集成的基于LLM的代理面临哪些挑战？为了具备能够有效与人类合作的具有沟通能力的代理，需要哪些额外的发展？哪些领域对于基于LLM的代理来说是低 hanging fruit？一旦我们拥有完全智能的基于LLM的代理，社会将会产生哪些影响，我们应该如何为这个未来做准备？

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Preface/section/3/text
1. 如何通过将LLMs视为智能代理的引擎来挑战当前技术在实现完全智能代理方面的局限性？这种引擎-车辆类比如何启发我们思考智能代理的设计和构建？  2. 在探讨个体代理的要求时，如何将代理的能力与人类进行比较，特别是在感知和行动能力方面？这种比较有助于我们理解智能代理在哪些方面需要进一步发展？  3. 代理的进化能力对智能工具的影响是怎样的？探讨代理的进化能力如何影响代理在复杂任务和工作流管理系统中的表现，有助于我们更好地理解智能代理的发展方向吗？
这些问题不仅超越了扩展当前LLMs和代理的工程实践，还提出了潜在的未来研究方向。我们邀请了来自人工智能领域的前沿研究人员，涵盖了LLM开发到代理设计，以全面解决这些问题。该书分为四个部分。第一部分阐述了个体代理的要求，将它们的能力与人类进行比较，包括感知和行动能力。第二部分探讨了代理的进化能力及其对智能工具（如工作流管理系统）的影响。第三部分讨论了代理社会，强调它们的协作和集体行动能力，第四部分涉及伦理和社会方面，包括代理的安全性和责任。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Preface/section/4/text
1. 如何利用大型语言模型（LLMs）作为智能代理的引擎，来构建具有长期记忆和自主执行动作等功能的完全智能代理系统？ 2. 在构建完全智能代理的过程中，如何克服当前技术在推理和生成能力上的局限性，以实现更接近智能生物的代理系统？ 3. 面向研究人员、学生和决策者等受众群体，如何激励他们提出新问题并加入对智能代理领域的探索，推动人工智能与人类共存的未来社会的发展？
本书旨在面向研究人员、学生、决策者和实践者。受众包括对人工智能、大型语言模型(LLMs)和代理感兴趣的非人工智能领域读者，以及对人类与人工智能共存的未来社会感兴趣的个人。读者群可能包括本科生、研究生、研究人员和行业从业者。本书旨在不仅回答读者对人工智能和代理的问题，还激励他们提出新问题。最终，我们希望能激励更多人加入我们的努力，探索这片富饶的研究领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/section
本章介绍了智能代理的兴起与发展、人脑与代理的比较以及模块化且受大脑启发的智能代理框架。智能代理的演进历程展示了从任务执行者到具有广泛推理和适应能力的合作者的转变，特别是大型语言模型的出现重新定义了代理的角色。比较人类认知和AI系统凸显了发展有益、伦理和安全的智能体的重要性。框架的设计受大脑启发，强调了感知-认知-行动循环，包括记忆、世界模型、情感和目标等核心组件。本调查还探讨了代理的自我增强能力、协作系统以及构建安全可靠的人工智能系统的挑战，为智能代理的全面发展提供了重要视角。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/section/0/text
1. 人工智能代理的兴起与发展如何展示了从任务执行者到具有广泛推理和适应能力的合作者的转变？ 2. 在人类大脑与人工智能代理的比较中，为什么发展有益、伦理和安全的智能体变得至关重要？ 3. 在模块化和脑启发式人工智能代理框架中，为什么强调感知-认知-行动循环以及包括记忆、世界模型、情感和目标等核心组件？
1.1 人工智能代理的兴起与发展 12
1.2 人类大脑与人工智能代理的并行比较 13
1.2.1 大脑功能区域与人工智能的相似之处 14
1.3 模块化和脑启发式人工智能代理框架 16
1.3.1 代理循环中的核心概念和符号 18
1.3.2 生物启发 21
1.3.3 与现有理论的联系 21

1.4 导览本调查 22

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.1 The Rise and Development of AI Agents/section
人工智能代理的崛起与发展是现代人工智能领域的基石，代表了系统感知环境、做出决策并采取行动的能力。代理的演变历程从早期对自治性和互动性的探索开始，到20世纪80年代罗德尼·布鲁克斯提出的包含架构，强调了代理的灵活性和可扩展性。大型语言模型(LLMs)的出现重新定义了代理的角色，使其从狭义任务执行者转变为具有广泛泛化、推理和适应能力的积极合作者。LLMs赋予代理语言理解与可操作能力的集成，使其能够自主查询数据库、思考使用外部工具的方式，并在多领域进行推理。LLMs的泛化能力使代理能够处理各种任务，从数据分析到实时协作问题解决，而无需大量特定任务训练。由LLMs驱动的代理在人类和机器之间充当智能中介者，将人类意图与机器精度融合，实现无缝的工作流程整合。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.1 The Rise and Development of AI Agents/section/0/text
1. 代理概念的演变如何体现了人工智能领域从早期的符号系统走向更强调自治性、适应性和真实世界互动的转变？  2. 如何解释大型语言模型(LLMs)的出现如何重新定义了代理的角色，并使其具备了广泛泛化、推理和适应能力，从而使代理成为智能中介者？  3. 代理范式的出现如何推动了理论人工智能构想和实际应用之间的桥梁，促进了对智能系统在动态复杂环境中运作的理解？
“代理（agent）”的概念是现代人工智能的基石，代表了一个系统感知其环境，做出决策，并采取行动以实现特定目标。这一概念在20世纪中叶在人工智能领域得到正式确立，但其根源可以追溯到早期对智能系统中自治性和互动性的探索。其中最广泛引用的定义之一，由[3]提出，将代理描述为“任何可以被视为通过传感器感知其环境并通过执行器对其环境进行作用的东西”。该定义强调了代理的双重性质，既是观察者又是执行者，能够动态适应周围环境而不是遵循静态规则。它概括了人工智能从仅仅计算系统到与环境互动的系统的转变。代理的历史发展与人工智能本身的演变相辅相成。早期的符号系统，如纽厄尔和西蒙的通用问题求解器[4]，试图通过将任务分解为逻辑步骤来复制人类解决问题的过程。然而，这些系统受限于对结构化环境和预定义逻辑的依赖。代理范式的出现是对这些限制的回应，侧重于自治性、适应性和真实世界的互动。罗德尼·布鲁克斯（Rodney Brooks）在20世纪80年代提出的包含架构（subsumption architecture）就是这种转变的典范，引入了能够在机器人领域实时做出基于行为的响应的代理[5]。与早期方法不同，这些代理无需对其环境进行详尽建模，展示了更灵活、可扩展的设计。代理自那时起已成为人工智能各个子领域中的多才多艺的框架。在机器人领域，它们实现了自主导航和操作；在软件领域，它们构成了用于模拟和协调的多代理系统的基础[6]。通过将感知、推理和行动整合到一个连贯的结构中，代理范式一直作为理论人工智能构想和实际应用之间的桥梁，推动我们对智能系统如何在动态复杂的环境中运作的理解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.1 The Rise and Development of AI Agents/section/1/text
1. 大型语言模型(LLMs)如何重新定义了代理的能力，改变了它们在人工智能中的角色，并为其应用开辟了新的视野？ 2. 由LLMs驱动的代理相较于过去的代理系统，具有哪些优势和特点，使其能够处理自然语言、跨越复杂领域进行推理，并以出色的流畅度适应新情况？ 3. 从被动处理者到积极合作者的转变，代理如何能够解决多步挑战并以类似人类问题解决方式与环境互动？
大型语言模型(LLMs)的出现重新定义了代理的能力，改变了它们在人工智能中的角色，并为它们的应用开辟了新的视野。代理曾经局限于执行狭义任务或遵循严格基于规则的框架，现在利用像OpenAI的ChatGPT[7]、DeepSeek AI的DeepSeek[8]、Anthropic的Claude[9]、阿里巴巴的QWen[10]和Meta的LLaMA[11]等模型的广泛泛化、推理和适应能力。这些由LLM驱动的代理已经从静态系统发展为能够处理自然语言、跨越复杂领域进行推理，并以出色的流畅度适应新情况的动态实体。这些代理不再仅仅是输入的被动处理者，它们已经成为能够解决多步挑战并以类似人类问题解决方式与环境互动的积极合作者。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.1 The Rise and Development of AI Agents/section/2/text
1. LLM如何通过集成语言理解和可操作能力，使得代理能够在何种情况下自主查询数据库、思考外部工具的使用方式，并执行精确的动作以实现特定目标？    2. LLM在少样本学习和零样本学习中的泛化能力是如何改变代理的适应性，使其能够处理各种任务而无需大量特定任务训练的？   3. 在人类和机器之间充当智能中介者的LLM驱动代理，如何实现无缝整合人类意图与机器精度，以应对日益复杂的工作流程？
LLM时代的一个关键进步在于将语言理解与可操作能力无缝集成。现代LLM配备了函数调用API，使代理能够识别何时需要外部工具或系统，思考它们的使用方式，并执行精确的动作以实现特定目标。例如，由ChatGPT驱动的代理可以自主查询数据库，检索相关信息，并将其用于提供可操作的见解，同时保持对更广泛任务的上下文意识。这种抽象推理和具体执行的动态组合使代理能够弥合认知理解与现实行动之间的差距。此外，LLM在少样本学习和零样本学习中的泛化能力已经彻底改变了代理的适应性，使它们能够处理各种各样的任务——从数据分析和创意内容生成到实时协作问题解决，而无需进行大量的特定任务训练。这种适应性，再加上它们的对话流畅性，使得由LLM驱动的代理在人类和机器之间成为智能的中介者，在日益复杂的工作流程中无缝地将人类意图与机器精度整合在一起。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/section
在人脑与人工智能代理之间的并行比较中，大型语言模型（LLMs）的快速融入智能代理架构推动了人工智能的发展，凸显了人类认知与人工智能系统之间的根本差异。人类智能具有高效的生物硬件、意识和情感体验，而基于LLM的代理在能源效率、意识和学习方法等方面存在明显差异。通过比较人类认知和AI系统，强调了发展有益、符合伦理和安全的智能体的重要性。未来的研究方向包括提高能源效率、模拟情感体验、实现持续学习和促进创造性思维，以构建更具弹性、负责任的人工智能系统，确保技术与社会价值保持一致。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/section/0/text
1. 基于大型语言模型的智能代理与人类认知之间的根本差异主要体现在哪些方面？ 2. 除了表1.1中提到的维度，人类智能和基于LLM的代理在哪些微妙特征上存在差异？ 3. 为了构建更具弹性和负责任的人工智能系统，未来研究应该关注哪些方面的发展？
大型语言模型（LLMs）快速融入智能代理架构不仅推动了人工智能的发展，也凸显了人工智能系统与人类认知之间的根本差异。正如表1.1简要说明的那样，基于LLM的代理在诸如基础“硬件”、意识、学习方法、创造力和能源效率等维度上与人类认知存在显著差异。然而，需要强调的是，这种比较仅提供了一个高层次的快照，而非详尽的描绘。人类智能具有许多此处未涵盖的微妙特征，而AI代理也展示出超越这种简明比较的独特特征。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/section/1/text
1. 在人类智能与基于LLM的代理之间的能源效率差异中，除了计算能力需求外，还有哪些因素可能导致这种性能差距？  2. 如何在不完全复制人类意识的前提下，利用情感体验和主观状态来引导人工智能研究朝着更加符合、可信赖和对社会有益的方向发展？  3. 在人类学习的互动性、环境相关性和受社会、文化影响等特点与LLM代理的静态、离线训练之间存在的差异中，如何通过终身学习、个性化适应和交互微调等方法来弥合这一差距，使人工智能更好地模拟人类的适应能力和响应能力？
人类智能运行在展现出非凡能源效率的生物硬件——大脑上，这使得人类能够以极低的代谢成本进行终身学习、推理和适应性决策。相比之下，当前的人工智能系统需要大量的计算能力，导致在进行相似认知任务时能源消耗显著增加。认识到这种性能差距强调了能源效率作为未来人工智能研究的一个关键领域。

在意识和情感体验方面，基于LLM的代理缺乏人类认知固有的真实主观状态和自我意识。虽然在人工智能中完全复制类似人类的意识既可能不是必要的，也不是可取的，但是欣赏情感和主观体验在人类推理、动机、伦理判断和社会互动中发挥的重要作用，可以引导研究朝着创造更加符合、可信赖和对社会有益的人工智能方向发展。

人类学习是连续的、互动的、与环境相关的，深受社会、文化和经验因素的影响。相反，LLM代理主要经历静态的、离线的批量训练，具有有限的持续适应能力。尽管通过指导调整和从人类反馈中进行强化学习（RLHF）等研究工作，LLM代理仍然无法达到类似人类的灵活性。通过采用终身学习、个性化适应和交互微调等方法来弥合这一差距代表了一个有前途的研究方向，使人工智能能够更好地模拟人类的适应能力和响应能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/section/2/text
1. 如何区分人类创造力和基于LLM的“统计创造力”，以及这种区别对于开发更具深度和独创性的AI代理的意义是什么？ 2. 在构建更具深度创造过程的AI代理时，如何整合丰富的语境理解、情感状态模拟和经验基础，以弥补基于LLM的创造力的不足？ 3. 为了促进创造性思维和开发更具弹性、负责任的人工智能系统，如何平衡基于统计重组的创造力和个人经历、情感洞察的创造力在AI代理中的应用？
人类的创造力源自个人经历、情感洞察和跨领域联想的丰富互动。相比之下，基于LLM的创造力主要通过训练数据的统计重组产生——“统计创造力”缺乏深度、独创性和情感共鸣。这种区别突显了通过整合更丰富的语境理解、模拟情感状态和经验基础来开发更深层次创造过程的AI代理的机遇。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/section/3/text
1. 人类大脑经过演化所获得的效率、适应性和创造力与AI系统的快速发展相比，如何揭示了人类认知与AI系统之间的基本类比和根本差异？    2. 在人类智慧与AI系统之间的比较中，如何可以利用人类智慧中的灵感来增强AI的能力，从而使其在各领域为人类带来更多益处？  3. 时间尺度上人类大脑演化的数百万年与AI系统的近80年发展相比，如何可以通过对比两者获得有意义的见解，指导AI代理技术的进步？
考虑时间尺度，人类大脑经过数百万年的演化，在自然选择和环境互动中实现了卓越的效率、适应性和创造力。与之形成鲜明对比的是，自早期计算机问世以来的大约80年间，AI代理经历了快速而相对较短的发展。因此，对比人类认知和AI系统是非常有价值的，它揭示了基本类比和根本差异，提供了有意义的见解，可以指导AI代理技术的进步。最终，从人类智慧中汲取灵感可以增强AI的能力，使其在医疗保健、教育、可持续发展等各种领域造福人类。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/section/4/table
1. 在表1.1中，人脑和大型语言模型代理在哪些方面存在明显的差异？ 2. 未来研究方向中提到的提高能源效率、模拟情感体验、实现持续学习和促进创造性思维，如何有助于构建更具弹性、负责任的人工智能系统？
表1.1：人脑与大型语言模型代理之间的简明高层次比较。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section
本节深入探讨了人脑功能与人工智能之间的相似性，特别关注了大型语言模型（LLMs）和AI代理。通过对人脑的功能区域进行系统检查，揭示了AI研究的三个不同层次：Level 1 (L1)已发展良好，Level 2 (L2)有改进空间，而Level 3 (L3)尚未深入研究。各脑功能区域如额叶、顶叶、枕叶、颞叶、小脑和脑干在人工智能中的对应发展水平和挑战被详细探讨。通过比较人类认知和人工智能的差距，强调了开发有益、符合伦理和安全的智能体的重要性。最终目标是创造更具弹性、负责任的人工智能系统，强调以人为中心的设计，促进技术和社会进步，确保人工智能技术与人类价值观保持一致。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/0/text
1. 人脑功能与人工智能之间的相似性如何影响了当前大型语言模型（LLMs）和AI代理的发展和应用？  2. 在当前的神经科学框架下，如何系统地检查人脑的六个主要功能区域（如额叶、小脑和脑干）与人工智能中的对应关系，以揭示AI研究的不同层次（L1、L2、L3）？  3. 为了创造更具弹性、负责任的人工智能系统，如何强调以人为中心的设计，促进技术和社会进步，并确保人工智能技术与人类价值观保持一致？
理解人脑功能与人工智能（AI）之间的相似之处，不仅揭示了AI的优势和当前限制，特别是大型语言模型（LLMs）和AI代理。根据当前的神经科学，人脑主要由六个功能区域组成，如额叶、小脑和脑干，如图1.1所示。在这项工作中，我们进一步系统地检查了现有AI与主要脑区域及其主要功能的对应关系。从宏观角度来看，AI研究的状态可以分为三个不同的层次：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/1/text
1. Level 1 (L1)在人工智能中的发展水平如何体现了对高阶认知功能的成功模拟？   2. 在人工智能领域，为什么额叶的自我意识和抑制控制方面的探索相对较少？   3. 如何利用生物系统中的专业化和整合核心原则来指导更具凝聚力的人工智能代理架构？
在当前的人工智能中，Level 1 (L1)已经得到很好的发展。Level 2 (L2)已经有一定的探索，取得了部分进展，但还有进一步改进的空间。Level 3 (L3)很少被探索；有很大的研究空间。

图1.1显示了大脑功能区域的高层视觉图及其对应的人工智能发展水平。我们旨在强调观察到的生物系统中的专业化和整合核心原则如何指导更具凝聚力的代理架构。现在我们将详细检查每个大脑功能区域及相关的人工智能发展。 

额叶：执行控制与认知额叶，特别是前额叶皮层，对于高阶认知非常重要，如计划（L2）、决策（L2）、逻辑推理（L2）、工作记忆（L2）、自我意识（L3）、认知灵活性（L3）和抑制控制（L3）[13]。人工智能在规划和决策方面取得了显著进展，在明确定义的领域内展示了这一点，例如AlphaGo [14]。变压器使用类似于人类工作记忆的注意机制[15]，但在人类的灵活性和稳健性方面仍有不足。对于人工智能中真正的自我意识和抑制控制的探索仍然很少，并且由于潜在的道德和安全影响，建议谨慎对待。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/2/figure
1. 在人脑功能与人工智能研究中，哪些大脑区域的对应发展水平已经达到Level 1（L1）？这些区域的研究成果有哪些？  2. 针对Level 3（L3）尚未深入研究的大脑功能区域，我们应该如何提高人工智能在这些领域的探索水平？
图1.l：按主要大脑区域分组的关键人类大脑功能的示意图，根据它们在人工智能研究中的当前探索水平进行注释。该图突出了人工智能朝着更全面、脑启发式能力发展的现有成就、差距和潜在机会。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/3/text
1. 人类顶叶在空间处理与多感官整合方面的功能如何促进注意力、空间定向和感觉运动协调？人工智能在这些领域的研究存在哪些挑战和限制？ 2. 人工智能在解决类似于顶叶功能的挑战时采用了哪些技术，例如同时定位与地图构建（SLAM）？人工智能在实现无缝和实时多感官整合方面与人类存在哪些差距？ 3. 在人工智能领域，为什么详细的触觉知觉（L3）仍然鲜为人知？这种知觉在机器人技术和假肢应用中有怎样的潜力和重要性？
顶叶：空间处理与多感官整合 顶叶整合多感官输入，促进注意力（L2）、空间定向（L2）和感觉运动协调（L2）[16]。在机器人学和计算机视觉中，人工智能研究解决类似的挑战，采用同时定位与地图构建（SLAM）等技术。然而，人工智能仍然缺乏人类所见到的无缝和实时整合。此外，详细的触觉知觉（L3）仍然鲜为人知，并且在机器人技术和假肢应用方面具有相当大的潜力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/4/text
1. 在人工智能领域，枕叶负责视知觉处理，人工智能在基本视觉识别任务上表现出色，但在高级功能方面仍具挑战性。如何才能进一步提高人工智能系统在抽象视觉推理和语境场景理解等方面的表现？  2. 颞叶在促进听觉处理、语言理解、记忆形成和语义理解方面发挥作用，人工智能在语言和听觉处理上取得了显著进展。然而，人工智能系统在强大的情节记忆和终身学习能力方面仍存在限制。如何解决人工智能系统遇到的灾难性遗忘等问题，以实现更强大的终身学习能力？
枕叶：视觉处理
枕叶专门负责视知觉（L1），通过分层结构高效地处理视觉刺激[13]。人工智能在基本视觉识别任务上表现出色，利用深度神经网络和视觉转换器实现了与人类水平或更高水平的性能[15]。然而，高级功能，如语境场景理解（L2）和抽象视觉推理，仍然具有挑战性，发展程度仅属中等。

颞叶：语言、记忆和听觉处理
颞叶促进听觉处理（L1）、语言理解（L1）、记忆形成（L2）和语义理解（L2）[16]。人工智能在语言和听觉处理方面取得了显著进展，体现在能够实现接近人类语音识别和语言生成的大型语言模型（LLMs）上。然而，强大的情节记忆和终身学习能力仍然有限，人工智能系统经常遇到像灾难性遗忘这样的问题。将语义理解扎根于多模态体验仍然是一个活跃的研究领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/5/text
1. 小脑在人工智能中的发展水平主要体现在哪些方面？这些方面存在怎样的挑战和限制？ 2. 人工智能技术在模拟人类灵巧性方面取得了哪些成就？目前在实时自适应控制方面还存在哪些挑战？ 3. 小脑的认知功能在人工智能领域中扮演着怎样的角色？未来在这一领域还有哪些需要深入探索的方面？
小脑：协调和运动学习
小脑主要支持运动协调（L2）、精细技能学习（L2）和适应性错误修正（L2），并在认知时间和预测建模（认知时间，L3）中扮演新兴角色[13]。基于人工智能的机器人技术在模拟类人灵巧性方面取得了有限的成功。实时自适应控制仍然具有挑战性，尽管当前在强化学习和元学习方面的研究显示出有希望的初步结果。小脑的认知功能代表了一个尚未被充分探索但有前景的前沿领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/6/text
1. 在人工智能系统中，为什么脑干的自主调节和快速反射控制被认为处于较低的研究层次（Level 3），而不同于基本的反射性反应（Level 1）？    2. 人工智能中自主调节和动态唤醒状态的复杂性为何仍然未被深入探索？这种复杂性在人类认知和人工智能之间的基本差异中发挥了怎样的作用？  3. 在构建更具弹性、负责任的人工智能系统时，为什么需要关注脑干的功能，特别是自主调节和反射控制？这种关注如何有助于确保人工智能技术与人类价值观保持一致？
脑干：自主调节和反射控制
脑干管理基本的维持生命的自主功能（L3）和快速的反射性反应（L1），如基本的运动反射[13]。人工智能包括设计好的反射性反应，比如自动驾驶汽车中的自动制动，通常是预先定义的而非学习得来。相比之下，在人工智能中自主调节和动态唤醒状态的复杂性仍然大部分未被探索，由于生物和人工系统之间的基本差异，它们的相关性可能受到限制。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/7/text
1. 在人工智能中，边缘系统如情绪处理、共情和动机驱动的不足如何影响其在模拟人类认知方面的表现？   2. 人工智能中的强化学习算法如何应对情绪理解、真正的共情和内在动机状态等边缘系统功能的不足？   3. 作者提到的情绪操纵的伦理关切如何引发了对人工智能发展中谨慎和负责探索的必要性？
边缘系统：情绪、共情和动机
边缘系统由杏仁核和海马组成，主管情绪处理（L3）、奖励机制（L2）、共情（L3）、应激调节（L3）和动机驱动（L3）[13]。人工智能的强化学习算法模拟基于奖励的学习，但情绪理解的微妙差异、真正的共情和内在动机状态仍然显著不足。对于情绪操纵的伦理关切突显了对于谨慎和负责的探索的必要性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/8/text
1. 如何在开发人工智能系统时平衡复制人类认知与创新发展的关系，以实现对社会有益、符合伦理、安全和有益的智能体的目标？ 2. 在比较人类认知和人工智能系统的差距时，哪些方面值得重点关注以推动人工智能技术的创新发展？ 3. 如何通过整合人类认知的有益方面，如高效处理、终身适应性学习、情感基础和创造力，超越人类的局限，促进更有能力、更具弹性和更负责任的人工智能系统的创建？
架桥脑样功能与构建有益人工智能至今，我们见证了人类大脑与机器智能之间的差距。然而，目标并不一定是在人工智能系统内复制人类认知的每一个方面。相反，我们的总体目标应该是开发对社会有用、符合伦理、安全和有益的智能体。通过比较人类和人工智能，我们突出了现有的差距，并阐明了创新的有希望方向。这种比较视角使我们能够有选择地整合人类认知的有益方面，比如高效处理、终身适应性学习、情感基础和丰富的创造力，同时超越人类的局限进行创新。最终，这种方法旨在促进更有能力、更具弹性和更负责任的人工智能系统的创建。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/9/text
1. 在混合人工智能社会中，人类角色的不断变化如何影响人工智能的发展和应用？ 2. 为什么人工智能的目标应该是增强和赋能人类能力，而不是完全取代人类角色？ 3. 为什么人类监督、可解释性和对人类价值观的尊重对于开发强大的人工智能系统至关重要？
此外，考虑人类在混合人工智能社会中的不断变化角色至关重要。人工智能的目标不应是完全取代人类角色，而应是增强和赋能人类能力，在AI擅长的领域，如处理海量数据、进行快速计算和自动化重复任务方面，补充人类技能和判断。人类监督和可解释性对于确保强大的AI系统保持可控性并与人类价值观和伦理标准保持一致至关重要。因此，核心目标必须是开发透明、可解释且对人类指导响应灵活的人工智能技术。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.2 A Parallel Comparison between Human Brain and AI Agents/1.2.1 Brain Functionality by Region and AI Parallels/section/10/text
1. 人为中心的人工智能设计如何确保技术进步在受控、可靠的框架内进行，同时增强人类的生产力、创造力和决策能力？    2. 在实现可持续、公平和繁荣未来的过程中，人类智能和人工智能能力如何进行整合，以确保技术与社会价值观的一致性？  3. 人工智能生态系统中将人类置于中心的优势是什么，以及如何利用这一优势促进技术和社会进步，同时保护人类的自主权和尊严？
以人为中心的人工智能设计强调协作、安全和社会责任，确保技术进步以受控、可靠的方式进行。通过将人类置于人工智能生态系统的中心，我们可以利用人工智能的潜力，增强人类的生产力、创造力和决策能力，促进技术和社会进步，而不损害人类的自主权或尊严。最终，对人类智能和人工智能能力进行深思熟虑的整合，可以为一个可持续、公平和繁荣的未来铺平道路。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/section
本节介绍了一个模块化且灵感源自大脑的人工智能代理框架。当前人工智能代理设计存在临时性问题，缺乏统一框架整合认知和功能组件。受人脑协调专业化启发，提出从大脑中汲取灵感，系统地分析和设计代理框架。神经科学揭示了大脑的并行处理、分层认知、注意力机制、奖励整合和目标设定等原则，为AI代理设计提供参考。框架包括感知-认知-行动循环，强调记忆、世界模型、情感、目标、奖励和学习之间的相互作用。生物启发的代理模型涵盖记忆、世界模型、情感、目标、奖励和推理等模块，构建了复杂智能行为的理论基础。通过与现有理论的关联，如感知-认知-行动循环、心智社会理论、内外视角和贝叶斯大脑框架，框架展现了生物可信性和通用性，为实现智能行为提供了灵活性和支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/section/0/text
1. 当前的LLM代理设计存在哪些临时性问题？如何解释这些问题与人脑中专业化协调的差异？   2. 人脑中的专业化协调如何影响复杂刺激的适应性反应？这种协调与当前基于LLM的代理设计有何异同之处？   3. 为什么需要从人脑中汲取灵感来设计代理框架？通过将专门组件紧密集成的方式实现通用智能如何提供加强当前基于LLM的代理的蓝图？
LLM时代的一个核心问题是缺乏一个统一的框架，该框架整合了先进代理所需的丰富认知和功能组件。虽然LLMs提供了出色的语言推理能力，但许多当前的代理设计仍然是临时的 - 它们以一种零碎的方式整合了感知、记忆或规划等模块，未能逼近生物系统（如人脑）中所见的良好协调的专业化。与当前的LM代理不同，人脑通过不同但相互连接的区域无缝平衡感知、记忆、推理和行动，促进对复杂刺激的适应性反应。相比之下，由LLM驱动的代理在需要跨领域或多模态集成的任务时往往遇到困难，突出了需要一种更全面的方法，类似于大脑的功能多样性。受到这些相似之处的启发，我们的调查主张从人脑中汲取灵感，系统地分析和设计代理框架。这一观点表明，生物系统通过将专门组件（用于感知、推理、行动等）紧密集成的方式实现了通用智能 - 这种方法可以作为加强当前基于LLM的代理的蓝图。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/section/1/text
1. 大脑中的理性电路和情绪电路在决策过程中的作用是怎样的，它们如何相互影响并引导行为？ 2. 在记忆形成和奖励信号传递中，大脑的海马体、皮质机制以及多巴胺的作用是如何相互协调的？ 3. 基于神经科学的启示，如何将记忆、奖励、情感等生物学原则应用于人工智能代理的设计中，以实现智能行为的灵活性和支持？
神经科学研究揭示，大脑利用理性电路（例如，新皮层，促使深思熟虑和规划）和情绪电路（例如，边缘系统）来引导决策。记忆形成涉及海马体和皮质机制，而奖励信号，通过多巴胺和其他神经调节途径介导，强化行为和学习。这些生物学见解启发了AI代理的几项设计原则，包括但不限于：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/section/2/table
1. 在修订后的智能代理框架中，学习和推理功能是如何分离的？这种分离对整体认知过程有何影响？ 2. 如何利用大脑的并行处理、分层认知、注意力机制、奖励整合和目标设定等原则，来设计一个具有生物可信性和通用性的智能代理框架？
表1.2: 修订后的智能代理框架符号总结，突出整体认知过程中的学习和推理功能的分离。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/section/3/text
1. 大脑中的并行处理如何影响视听整合，AI代理又如何利用并行处理来实现连贯理解？ 2. 皮质和皮质下区域之间的相互作用如何促进人类的推理、规划和情绪调节？AI代理可以如何借鉴这种分层和分布式认知来提升智能行为？ 3. 人类的注意力机制如何基于上下文、目标和情绪来处理感官数据？AI代理如何通过调节感知的学习注意力策略来模仿这一过程？
·并行、多模式处理：大脑通过专门的皮质区域并行处理视觉、听觉和其他感官输入，并在联想区域中将它们整合。同样，AI代理受益于对不同传感器流的并行处理，在后续阶段将它们融合以实现连贯理解。·分层和分布式认知：推理、规划、情绪调节和运动控制涉及皮质和皮质下区域之间的相互作用。类似地，AI代理可以采用模块化架构，其中子系统专门用于理性推断、情绪评估和记忆。·注意机制：人类的注意力基于上下文、目标和情绪优先处理感官数据。AI代理可以通过调节感知的学习注意力策略来复制这一过程，根据内部状态动态调整焦点。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/section/4/text
1. 情感如何在人工智能代理中发挥作用，以及奖励如何与情感整合，对于代理的决策和学习过程有何重要性？ 2. 人类的前额叶皮质在目标设定和规划行动序列中发挥着怎样的作用？AI代理如何能够模拟这种能力，以实现有效的目标管理和适应性行动？ 3. 在人工智能代理中，奖励驱动的可塑性如何促进习惯形成和技能习得？这对于代理的强化学习有何重要性，以及如何应用于实现智能行为？
·奖励和情感整合：情绪不仅仅是噪音，而是决策中不可或缺的一部分，调节优先级，增强警惕，并引导学习。以奖励为驱动的可塑性促进习惯形成和技能习得，这一概念对于AI代理中的强化学习至关重要。·目标设定和工具使用：人类的前额叶皮质擅长设定抽象目标和规划行动序列，包括工具使用。同样，AI代理需要强大的目标管理系统和适应性行动方案，由外部奖励和内在动机驱动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/section/5/text
1. 基于大脑启发的代理框架如何区别于直接复制生物机制的设计方法，以及这种区别对于代理框架的灵活性和可信度有何影响？  2. 在基于感知-认知-行动循环的统一代理架构中，如何通过奖励信号和学习过程实现对代理行为的丰富塑造，以及这种方法如何确保各个子系统之间的透明性和相互作用？  3. 该代理框架如何将认知形式化为通用的推理机制，同时将规划和决策建立为特定“心理行为”的具体行动，并如何与已有理论进行关联以展现其普适性和生物可信度？
这些原则构成了我们提出的基于大脑启发的代理框架的基础，其中生物机制作为灵感的来源而不是直接复制。

在接下来的章节中，我们概述了我们框架的关键概念，介绍了一个基于感知-认知-行动循环的统一代理架构，通过奖励信号和学习过程进行丰富。每个子系统都被仔细定义和相互连接，以确保记忆、世界模型、情绪、目标、奖励和学习之间的相互作用的透明性。我们将认知形式化为一种通用的推理机制，规划和决策被构建为塑造行为的特定“心理行为”的具体行动。与已建立的理论，如明斯基的“心智社会”[17]、布扎基的内外透视[18]和贝叶斯主动推断[19]的联系被探讨，以突显该框架的普适性和生物可信度。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/section/6/figure
1. 在图1.2中，智能代理循环的不同模块之间是如何相互作用的？ 2. 图1.2中提到的代理社会是如何与智能代理循环框架相互关联的？
图1.2：我们描述智能代理循环和代理社会的一般框架概述。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.1 Core Concepts and Notations in the Agent Loop/section
在代理循环中，我们的架构操作在社会、环境和代理三个概念层面。代理被分解为感知、认知和行动三个主要子系统，其中认知包括关键的子模块：记忆、世界模型、情感状态、目标、奖励、学习和推理过程。特别是在认知中，规划和决策作为推理产生的特殊行为。注意力主要集中在感知和认知领域。通过引入符号表1.2，我们构建了代理循环，为进一步探讨提供了基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.1 Core Concepts and Notations in the Agent Loop/section/0/text
1. 认知中的规划和决策如何与推理过程相关联，以促进代理在环境中的有效操作？ 2. 为什么在代理循环中，注意力主要集中在感知和认知领域，而不是行动领域？ 3. 符号表1.2在代理循环中的作用是什么，以及它是如何为进一步探讨提供基础的？
我们的架构在三个概念层面操作：社会、环境和代理。然后，代理被分解为三个主要子系统：感知、认知和行动。在认知中，我们确定了关键的子模块：记忆、世界模型、情感状态、目标、奖励、学习和推理过程（包括“规划”和“决策”作为推理产生的特殊行为）。注意力主要在感知和认知中处理。在介绍正式循环之前，我们在表1.2中总结了我们的符号。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.1 Core Concepts and Notations in the Agent Loop/section/1/text
1. 代理循环中的符号表1.2如何有助于我们理解和构建代理的认知和决策过程？ 2. 在代理循环中，为什么认知被分解为记忆、世界模型、情感状态、目标、奖励、学习和推理过程这些关键子模块？这种分解有何意义？ 3. 代理循环中的规划和决策如何与推理过程相关联？规划和决策在代理循环中扮演着怎样的角色？
接下来，基于表1.2中的符号，我们提出了我们的代理循环。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.2 Biological Inspirations/section
本节介绍了生物启发的智能代理模型，强调了从人类大脑中汲取灵感的重要性。首先，讨论了记忆模块，其中$M_{t}^{\mathrm{mem}}$类比于海马体和新皮层，用于捕捉多尺度学习。其次，介绍了世界模型$M_{t}^{\mathrm{wm}}$，类比于皮质作为预测机器，不断更新内部表示以反映环境动态。情绪组件$M_{t}^{\mathrm{{emo}}}$被引入以模拟情绪对注意力、学习速率和决策门槛的影响。接着，讨论了目标与奖励模块，包括$M_{t}^{\mathrm{goal}}$和$M_{t}^{\mathrm{rew}}$，用于存储目标和编码奖励信号，实现目标形成和基于奖励的反馈循环。最后，描述了推理、规划和决策模块，涵盖了高阶认知过程的执行，如逻辑推理和规划。这些模块共同构成了生物启发的智能代理框架，为实现复杂智能行为提供了理论基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.2 Biological Inspirations/section/0/text
1. 讨论记忆模块$M_{t}^{\mathrm{mem}}$如何类比于海马体和新皮层，以捕捉多尺度学习，并解释这种类比对于智能代理模型的重要性是什么？  2. 在智能代理模型中，记忆组件$M_{t}^{\mathrm{mem}}$的设计灵感来源于人类大脑的海马体和新皮层。请探讨这种生物启发设计如何影响了代理模型的灵活性和学习能力？  3. 在人类大脑中，海马体和新皮层分别负责管理情节记忆和存储语义知识。如何通过将这些功能引入智能代理模型的记忆组件$M_{t}^{\mathrm{mem}}$来实现多尺度学习和知识存储？
尽管我们的智能代理模型在根本上是计算化的，但每个子模块都从人类大脑中经过深入研究的生物学对应物中汲取灵感。下面，我们讨论这些类比，强调神经科学基础以及AI实现所提供的灵活性。

记忆（海马体和新皮层）。几十年的神经科学研究将海马体与情节记忆形成联系起来，而皮层区域则被认为存储语义和程序知识。在人类中，这些记忆子系统合作管理短期编码和长期巩固。我们的记忆组件$M_{t}^{\mathrm{mem}}$ 同样旨在通过存储最近的经验和知识来捕捉多尺度学习。这可以通过神经网络权重（长期）或显式缓冲区（短期）来实现，从而反映海马皮质相互作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.2 Biological Inspirations/section/1/text
1. 为什么在生物启发的智能代理模型中，世界模型$M_{t}^{\mathrm{wm}}被类比为皮质作为一个预测机器，不断更新内部表示以反映环境动态的重要性？  2. 在认知神经科学中，如何解释皮质作为一个预测机器运作的理论，以及这种理论如何与生物启发的智能代理模型中的世界模型$M_{t}^{\mathrm{wm}}相联系？  3. 生物启发的智能代理框架中的世界模型$M_{t}^{\mathrm{wm}}是如何通过维护内部表示来反映环境随时间演变的方式，并在每次新观察和相关奖励或情绪提示时得以完善的？
世界模型（预测处理）。认知神经科学中一个重要理论认为，皮质作为一个预测机器运作，不断将传入的感官数据与生成的期望进行比较。世界模型$M_{t}^{\mathrm{wm}}$通过维护一个内部表示来反映环境随时间演变的方式。正如皮质回路整合多感官数据以更新这些内部模型一样，我们的框架允许$M_{t}^{\mathrm{wm}}$在每次新观察和相关奖励或情绪提示时得以完善，提供了对环境动态的贝叶斯或自由能视角。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.2 Biological Inspirations/section/2/text
1. 情绪组件在生物启发的智能代理模型中的作用是什么，如何通过调节注意力、学习速率和决策门槛来影响代理的行为？  2. 在模型中引入情绪组件$M_{t}^{\mathrm{{emo}}}$的意义是什么，它是如何捕捉内部价值或唤醒状态对代理行为的影响的？  3. 情绪在智能代理中的作用如何体现了适应性启发式的概念？它是如何帮助代理优先考虑紧急目标或快速回应感知到的威胁的？
情绪（边缘系统）。情绪，由杏仁核、下丘脑和边缘系统等结构介导，显著调节注意力、学习速率和决策门槛[24,25]。通过引入一个情绪组件$M_{t}^{\mathrm{{emo}}}$，我们的模型捕捉了内部价值或唤醒状态如何转移代理的关注和行为。虽然计算“情绪”既不完全类似于生物影响，也不是意识感受，但它们可以引导适应性启发式，比如优先考虑紧急目标或快速回应感知到的威胁。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.2 Biological Inspirations/section/3/text
1. 前额叶和皮质下环路在智能代理中的作用是如何相互协调的，以实现目标形成和基于奖励的适应之间的连续反馈循环？  2. 在智能代理中，多巴胺通路如何推动塑造动机和习得习惯的强化信号，与存储目标和编码奖励信号的模块如何相互作用以实现智能行为的提升？  3. 目标与奖励模块在生物启发的智能代理框架中的作用是如何促进计划的行动序列、工具使用和社交互动的？
目标与奖励（前额叶和皮层下环路）。人类擅长制定抽象的、长期的目标，这种能力通常与前额叶皮质功能相关联。与此同时，皮质下环路——特别是多巴胺通路——推动着塑造动机和习得习惯的强化信号。我们的智能体包括$M_{t}^{\mathrm{goal}}$用于存储目标和$M_{t}^{\mathrm{rew}}$用于编码奖励信号，从而实现目标形成和基于奖励的适应之间的连续反馈循环。这种机制允许计划的行动序列、工具使用以及更加微妙的社交互动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.2 Biological Inspirations/section/4/text
1. 在生物启发的智能代理框架中，为什么强调推理、规划和决策这些高阶认知过程的重要性？这些过程如何与记忆、情绪、奖励等模块相互作用，促进复杂智能行为的实现？  2. 在智能体框架中，推理子功能如何整合来自记忆、感觉输入、情绪和奖励途径的信息，以执行逻辑推理、规划和执行控制等高阶认知过程？这种整合如何类比于人类前额叶皮质的功能？  3. 在智能代理模型中，如何通过区分规划和即时决策来模拟智能体如何权衡结果、模拟未来场景并选择执行行动方案？这种模拟与人类前额叶回路中观察到的灵活编排有何相似之处？
推理、规划和决策（前额叶皮质）。最后，人类前额叶皮质整合来自记忆、感觉输入、情绪和奖励途径的信息，执行高阶认知过程，如逻辑推理、规划和执行控制。在我们的智能体框架中，这些能力被推理子功能所包含，通过PlanFn和Decide等模块选择和执行行动（无论是物理行动还是纯粹的思维）。通过区分规划和即时决策，我们捕捉了智能体如何模拟未来场景、权衡结果，然后承诺采取行动方案，类似于前额叶回路中观察到的灵活编排。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.3 Connections to Existing Theories/section
在1.3.3节中，我们将现有理论与人工智能、认知科学和神经科学中的重要理论进行了关联。首先，我们扩展了经典的感知-认知-行动循环，包括明确的注意力机制、学习和情感，以及奖励信号。其次，我们将明斯基的“心智社会”理论应用到子模块中，强调了记忆、预测、情感评估和目标设定等关键功能的分布。此外，我们支持了Buzsaki的内外视角，强调大脑积极构建和更新感知的重要性。我们的框架还可被看作是部分可观察马尔可夫决策过程（POMDP）的泛化，通过内部状态的演化和更广泛的推理子过程实现更灵活的决策。最后，我们采用主动推理与贝叶斯大脑框架，强调了代理通过更新内部生成模型减少预测误差的重要性。这些关联将生物可信性与普适性相结合，为实现智能行为提供了灵活性和通用性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.3 Connections to Existing Theories/section/0/text
1. 我们的架构如何与人工智能、认知科学和神经科学中的重要理论相一致，具体体现在哪些方面？ 2. 在明斯基的“心智社会”理论中，我们的子模块是如何回应并分布关键功能的？这种分布如何促进了智能行为的实现？ 3. 如何理解我们的框架被看作是部分可观察马尔可夫决策过程（POMDP）的泛化，以及通过内部状态的演化和更广泛的推理子过程实现更灵活决策的概念？
除了这些明确的神经生物学相似之外，我们的架构与人工智能、认知科学和神经科学中的几个重要理论相一致。

经典的感知-认知-行动循环。我们扩展了传统的感知-思考-行动循环，其中包括明确的注意力机制（在P中）、学习和情感（在C中），以及持续一段时间的奖励信号。这种明确性使得分析代理的内部状态和先前行动如何塑造后续感知和认知变得更容易。

明斯基的“心智社会”。明斯基认为，智能来自于心智中的一组专门化的“代理”。我们的子模块 - $\cdot\mathrm{C}_{\mathrm{mem}}$ $\mathrm{C}_{\mathrm{wm}}$ $\mathrm{C}_{\mathrm{emo}}$ $\mathrm{C_{goal}}$ goal，C $\mathrm{C}_{\mathrm{rew}}$ - 回应了这种分解，将关键功能（如记忆、预测、情感评估、目标设定等）分布在相互作用的独立组件之间。在更广泛的“社会”背景下，每个代理（或子代理）可以像明斯基的内部机构一样协调合作或竞争。最近关于基于自然语言的心智社会的研究支持了使用原始心智社会理论来表示代理系统，并且可以在代理之间整合社会结构和经济模型。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.3 Connections to Existing Theories/section/1/text
1. 在Buzsaki的内外视角中，大脑积极构建和更新感知如何影响代理对环境的采样和解释方式？  2. 我们的框架如何将部分可观察马尔可夫决策过程（POMDP）进行泛化，从而实现更灵活的决策机制？  3. 为什么在我们的框架中，奖励信号被放置在代理的心智状态中，而不是作为单一外部定义的目标？
Buzsaki的内外视角。神经科学家们认为，大脑积极构建和更新其感知，而不仅仅是接收输入。在我们的模型中，$M_{t-1}$，包括情绪状态、奖励信号和目标，直接影响感知地图P。这支持了内外立场，即一个代理的内部背景驱动其对环境进行采样和解释的方式，而不是被动地对其做出反应。

部分可观察马尔可夫决策过程（POMDP）。我们的框架可以被看作是经典部分可观察马尔可夫决策过程（POMDP）的泛化。首先，虽然POMDP规定了一个概率转移函数 $\textstyle P(s_{t+1}\mid s_{t},a_{t})$ 在（可能是有限的）状态空间上，我们保留了一个环境转移T，而不将其限制为纯粹的概率性或有限形式，允许任意甚至确定性的映射。其次，在标准POMDP设置中，奖励通常被定义为$(s_{t},a_{t})$的标量函数（可能随时间打折）。相比之下，我们将奖励信号放置在代理的心智状态$(M_{t}^{\mathrm{rew}})$中，让它们依赖于目标、情绪和世界模型，并与之共同演化，而不是强制执行单一外部定义的目标。第三，虽然POMDP代理通常通过最大化预期回报（值函数）来选择行动，我们的推理子过程更广泛。它考虑记忆、情绪和其他心智状态因素，适应启发式或社会驱动的决策，而不仅仅是基于价值的选择。最后，POMDP并没有明确定义认知子模块，如记忆或情感，这些必须合并为一个单一的“信念状态”。在我们的框架中，每个子组件（记忆、世界模型、情感、目标、奖励）都被明确建模和更新，反映了对认知的生物启发观点。因此，尽管我们的方法作为一种特例恢复了POMDP的表述（通过强制执行概率性T、标量奖励和最小心智状态），但它允许更丰富的环境转移、内部状态和决策机制。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.3 A Modular and Brain-Inspired AI Agent Framework/1.3.3 Connections to Existing Theories/section/2/text
1. 主动推理与贝叶斯大脑框架如何帮助代理减少预测误差，从而实现智能行为的灵活性和通用性？  2. 在生物可信性与普适性的框架下，如何将记忆、情感、目标和奖励等关键功能通过不同人工智能范式实现，以保持系统的灵活性？  3. 代理如何通过不断更新内部生成模型，并选择符合预测结果的行动，来实现与新数据对齐，从而减少惊奇？
主动推理与贝叶斯大脑。主动推理是由Buzsaki提出的统一框架，表明代理不断更新内部生成模型，以最小化预测误差（或“自由能量”）。我们使用的$M^{\mathrm{wm}}$和$M^{\mathrm{rew}}$，连同规划和决策模块，可以用贝叶斯术语来解释。代理试图通过将其世界模型与新数据对齐，并选择符合预测（或期望）结果的行动来减少惊奇。

生物可信性与普适性。虽然大脑回路与代理子模块之间的映射是在高层次上进行的，但它提供了一种既具有生物启发又模块化不可知的方法。记忆、情感、目标和奖励可以通过各种人工智能范式来实现，包括符号方法、神经网络或混合方法，从而保持了灵活性。通过将神经科学、认知科学和人工智能的关键思想整合在一起，我们得到了一个通用框架，捕捉了智能行为的基本特性，而不过度约束实施细节。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.4 Navigating This Survey/section
本调查旨在探索智能代理的模块化设计、自我增强、协作系统和安全性构建。第一部分介绍了智能代理的认知、感知和操作模块，强调记忆、世界建模和奖励处理等核心组件。第二部分关注代理的自我增强能力，包括自适应学习和持续知识整合。第三部分研究代理在多代理系统中的协作与进化，探讨其应用于各领域的潜力。最后一部分讨论了构建安全、可靠的人工智能系统的挑战，提出内在和外在安全威胁的分类框架，并探讨了未来发展方向，如超对齐技术和安全扩展法则。整体而言，本调查旨在为智能代理的发展提供全面视角，促进其与人类社会的有机结合。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.4 Navigating This Survey/section/0/text
1. 通过比较生物认知与计算框架，如何可以识别智能代理研究中的协同作用、差距和创新机会？  2. 在智能代理研究中，如何通过搭建不同学科之间的桥梁，展现出独特的视角并释放其全部潜力？  3. 在人工智能领域下一波进展中，为何需要借鉴认知科学、神经科学等学科的启发，以推动智能代理的全面、模块化发展？
本调查旨在提供对智能代理进行全面、模块化和跨学科审查，借鉴认知科学、神经科学和其他学科的启发，引导人工智能领域下一波进展。尽管许多现有调查为智能代理研究的各个方面提供了有价值的见解，但我们在表1.3中详细比较了它们的焦点。我们的工作通过系统比较生物认知与计算框架，以识别协同作用、差距和创新机会，从而展现出独特的视角。通过搭建这些领域之间的桥梁，我们旨在不仅突出智能代理的优势所在，还要指出需要取得重大进展以释放其全部潜力的地方。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.4 Navigating This Survey/section/1/table
1. 在现有评论摘要中，智能代理的模块化设计方面的研究重点是什么？哪些是次要或较小的焦点？     2. 对于智能代理安全性构建的现有评论摘要，内在和外在安全威胁的分类框架是如何被讨论的？未来发展方向中的超对齐技术和安全扩展法则又扮演着怎样的角色？
表1.3：具有不同焦点的现有评论摘要。·表示主要焦点，而$\scriptscriptstyle\mathrm{~o~}$表示次要或较小焦点。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.4 Navigating This Survey/section/2/text
1. 代理的认知系统中的记忆、世界建模和奖励处理等核心组件在模块化设计中的作用如何？这些组件当前的进展、局限性和研究挑战是什么？  2. 代理的自我增强能力包括哪些方面，如自适应学习、自我反思和持续知识整合等，与人类技能增长和完善的能力有何类似之处？  3. 在构建安全和有益的人工智能系统时，内在和外在的安全威胁是如何影响代理体系结构内部和与外部环境互动的？未来发展方向中的超对齐技术和安全扩展法则如何应对这些安全挑战？
该调查分为四个关键部分：

· 第一部分：智能代理的模块化设计，介绍了代理的核心模块，包括认知模块，作为代理的“大脑”；用于解释感官输入的感知系统；以及用于与外部世界交互的行动系统。在认知系统中，我们进一步讨论了记忆、世界建模、情感、目标和奖励系统，分析它们的当前进展、局限性和研究挑战。

· 第二部分：智能代理的自我增强，我们将焦点转向代理体自我进化和优化的能力。我们探讨了像自适应学习、自我反思和基于反馈的改进这样的机制，受到人类随时间增长和完善技能的能力的启发。本部分还讨论了动态记忆系统和持续知识整合的重要性，以使代理在不断变化的环境中保持相关和有效。

· 第三部分：协作和进化智能系统，我们研究代理如何与彼此和环境互动以解决复杂的大规模问题。我们讨论多代理系统，在机器人、医疗系统和科学发现等领域的应用，突出它们的应用。本部分探讨了多代理系统的拓扑结构和代理协议，追溯了从静态到动态框架的沟通和协作的演变。我们将代理与人类协作范式相结合，研究互动模式如何塑造智能的共同进化，以及多代理系统如何在各种协作环境中调整其决策，通过集体智慧解决复杂挑战。

· 最后，在第四部分：构建安全和有益的人工智能中，我们全面分析了基于LLM的代理的安全格局。我们引入了一个将威胁分类为内在或外在的框架。内在的脆弱性源于代理体系结构内部：核心LLM“大脑”，以及使代理与世界互动的感知和行动模块。外在风险源自代理与记忆系统、其他代理和更广泛环境的互动。本部分不仅形式化和分析了这些脆弱性，详细说明了诸如越狱和提示注入等具体攻击向量，还审查了一系列防御机制。此外，我们探讨了未来的发展方向，包括超对齐技术和人工智能安全的扩展法则——能力和风险之间的相互作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/1 Introduction 12/1.4 Navigating This Survey/section/3/text
1. 如何将认知科学见解与计算设计原则相结合，为研究人员设计智能代理提供基础资源？这种结合如何促进代理的强大高效、适应性强、道德性和与人类社会复杂性的契合？  2. 在智能代理的发展中，如何实现对当前状态的整体视角，以及如何通过展望性路线图推动其未来发展？这种综合视角和前瞻性规划对代理技术的演进有何意义？  3. 为什么强调智能代理的发展应该注重其与人类社会的有机结合？在这种有机结合中，代理的道德性和适应性如何得以提升，以满足社会的复杂性需求？
通过将这些线索编织在一起，我们的调查旨在提供对智能代理当前状态的整体视角，并为它们的发展提供展望性路线图。我们独特地关注将认知科学见解与计算设计原则相结合，将这项调查定位为研究人员设计代理的基础资源，这些代理不仅强大高效，而且适应性强、具有道德性，并且与人类社会的复杂性深度契合。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/section
学习是智能代理将经验转化为知识的核心过程，涵盖感知、推理和世界理解。人类和LLM代理在学习过程中展现互补优势，后者通过数据驱动学习和参数更新实现无监督学习和上下文适应。学习空间和学习目标作为核心内容，探讨了代理内部学习方法和适应复杂任务环境的能力优化。推理在代理设计中扮演关键角色，包括结构化推理和非结构化推理两种方法，跨越不同环境并通过环境提供信息驱动推理。规划作为认知能力的重要组成部分，通过任务分解和外部知识整合提高规划效率，为代理的发展提供关键启示。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1  Learning 25/section
2.1.1 学习空间 27 2.1.2 学习目标 29 2.2 推理 31 2.2.1 结构化推理 32 2.2.2 非结构化推理 34 2.2.3 规划 36

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1  Learning 25/section/0/text
1. 学习空间如何影响学习过程中的信息获取和整合？ 2. 在学习目标的设定中，如何确保目标的明确性和可衡量性？ 3. 结构化推理与非结构化推理在推理过程中有何异同之处，各自的优势和局限性是什么？
2.1.1 学习空间 27
2.1.2 学习目标 29
2.2 推理 31
2.2.1 结构化推理 32
2.2.2 非结构化推理 34
2.2.3 规划 36

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/section
学习代表着智能代理将经验转化为知识的关键过程，涵盖增强感知理解、改进推理能力和发展世界理解。人类学习通过大脑神经网络在多个空间和目标上运作，从快速编码到技能发展。LLM代理通过数据驱动学习和参数更新机制实现类似的过程，展现无监督学习和上下文适应能力。比较人类与LLM学习揭示了互补优势，为代理研究指明方向。学习空间核心内容探讨了代理内部学习方法，包括全面心智状态学习、后续训练技术和强化学习。学习目标核心内容则强调代理通过不断学习和优化感知、推理和世界理解能力来适应复杂任务环境。这些研究为智能代理的发展提供了深入理解和发展方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/section/0/text
1. 智能代理如何通过学习将经验转化为知识，并在其心智状态中实现全面更新和特定认知组件的细化？ 2. 在学习过程中，智能代理如何展现增强感知理解、改进推理能力和发展更丰富的世界理解的能力？  3. 人类学习与LLM代理学习在将经验转化为知识的过程中存在哪些互补优势，以及这些优势如何指导智能代理研究的发展方向？
学习代表着智能代理在其心智状态中将经验转化为知识的基本过程。这种转化跨越不同的认知空间，从对整个心智状态的全面更新到特定认知组件的细化。学习的范围涵盖了为不同目标提供支持的显著能力：增强感知理解、改进推理能力和发展更丰富的世界理解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/section/1/figure
1. 图2.1中的认知系统的分类示意图中，学习和推理范式之间是否存在怎样的关系和互动？ 2. 在学习和推理范式中，LLM代理与人类学习的核心差异在哪里，以及这种差异对代理研究有何启示？
图2.1：认知系统的分类示意图，包括学习和推理范式。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/section/2/text
1. 人类学习中的大脑适应性神经网络如何在多个空间和目标上协同工作，从而实现快速编码、监督学习、强化学习和无监督模式提取？  2. 在人类学习过程中，特定神经回路如何通过定向适应来实现专业化技能发展和知识获取？这种定向适应如何在不同时间尺度上发挥作用，同时受到注意力、情绪和社会环境等因素的影响？  3. 人类学习中的大脑神经网络是如何在整体系统中协调学习，从海马体到小脑、基底神经节和大脑皮层区域，实现不同学习功能的综合运作？
人类学习通过大脑适应性神经网络在多个空间和目标上运作。大脑通过综合系统协调整个网络上的学习：海马体促进情节经验的快速编码，小脑支持精确运动技能的监督学习，基底神经节通过多巴胺奖励信号实现强化学习，大脑皮层区域促进无监督模式提取。在更专注的层面上，特定神经回路可以经历定向适应，从而实现专业化技能发展和知识获取。这些系统在不同时间尺度上协同工作，范围从即时响应到终身发展，同时受到注意力、情绪和社会环境等因素的影响。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/section/3/text
1. LLM代理如何在其心智状态空间中实现类似于人类学习的过程，以及这种学习方式与传统监督学习的区别是什么？  2. 人类学习和LLM代理在何种层面上展示了互补优势，以及它们在获取知识和适应新任务时的相似之处和差异是如何体现的？  3. LLM代理如何利用其注意力窗口内的上下文来适应新任务，而无需进行参数更改？这种学习方式如何反映了人类工作记忆的某些方面，又通过何种根本不同的机制运作？
虽然在体系结构上存在根本差异，但LLM代理在其心智状态空间中实现类似的学习过程。在综合层面上，它们通过在大规模数据集上进行预训练来获取广泛知识，展示一种形式的无监督学习。在更专注的层面上，它们通过参数更新机制（如监督微调和强化学习）来完善特定能力。独特的是，它们还展示了在上下文中学习的能力，通过利用其注意力窗口内的上下文来适应新任务，而无需参数更改：这种能力反映了人类工作记忆的某些方面，但通过根本不同的机制运作。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/section/4/text
1. 人类学习系统和LLM代理在处理大规模数据集方面的优势分别是什么，它们如何互补并为智能代理研究提供指导？ 2. 在学习过程中，为什么需要首先关注学习发生的心智状态空间，然后才是具体的学习目标？这种顺序对于智能代理的发展有何重要意义？ 3. 人类学习系统在情感系统整合方面表现出显著特征，而LLM代理在表示形式知识和跨领域综合信息方面具有独特能力。这两者的不同优势如何影响智能代理的学习能力和应用领域？
人类和人工学习系统之间的比较为开发更具能力和适应性的代理提供了宝贵的见解。人类学习在效率、情境化和与情感系统的整合方面表现出显著特征，而基于LLM的方法则在处理大规模数据集、表示形式知识和跨领域综合信息方面具有独特能力。这些互补的优势为研究提供了富有成效的方向。在探索学习的基础时，我们首先研究学习发生的心智状态空间，然后分析推动学习过程的具体目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/section/5/table
1. 不同状态修改学习方法总结表中，哪些方法被标记为主要影响，而哪些被标记为次要或无直接影响？     2. 在表2.1中，有哪些状态修改学习方法展示了主要影响，这些方法如何有助于代理通过不断学习和优化来适应复杂任务环境？
表2.1：不同状态修改学习方法总结。$\bullet$表示主要影响，而$\scriptscriptstyle\mathrm{~o~}$表示次要或无直接影响。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.1 Learning Space/section
在LLM代理的学习空间中，代理的学习方法呈现了一种数据驱动的结构化范式，与人类的探索性、情感驱动学习形成对比。学习发生在包括模型参数和心智状态的内部空间中，后者包括记忆、世界模型、情感状态、目标和奖励信号等组件。全面的心智状态学习通过对基础模型进行修改来增强代理的能力，如预训练获取广泛的世界知识。后续训练技术如监督微调和低秩调整有助于获得领域特定知识和逻辑推理能力。强化学习在推动代理的推理能力方面表现出潜力，例如通过强化微调和群体相对策略优化。部分心智状态学习则专注于特定组件的学习，如情境学习和通过环境交互积累经验数据的方法。这些学习方法使代理能够在不同状态下适应新任务，提高认知能力，并改进世界理解和奖励模型，为代理模型的发展指明了方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.1 Learning Space/section/0/text
1. LLM代理中的数据驱动学习方法与人类的探索性、情感驱动学习相比具有何种优势和劣势？ 2. 在代理的学习过程中，如何通过对心智状态的全面学习来增强代理的能力？这种学习方法有哪些应用价值？ 3. 强化学习在提升代理的推理能力方面展现出了怎样的潜力？与监督微调和低秩调整等后续训练技术相比，强化学习有何特点和优势？
LLM代理中的学习方法代表了一种结构化的、数据驱动的范式，与人类观察到的探索性、情感驱动的学习形成对比。虽然人类学习通常涉及积极的好奇心、动机和情感强化，但基于LLM的代理通常通过更正式的过程学习，例如在训练期间的参数更新或在探索过程中的结构化记忆形成。当前的代理架构尝试通过实施模拟人类学习方面的机制，同时利用计算系统的优势来弥合这一差距。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.1 Learning Space/section/1/text
1. 智能代理内部的学习空间中，基本模型参数 $\theta$ 和心智状态 $M$ 之间的相互作用如何影响代理的学习能力和局限性？  2. 在智能代理的内部空间中，为何需要将心智状态定义为一个包含模型参数和不同组件的元组 ${\mathcal{T}}=(\theta,M)$，以支持代理的学习和适应能力？  3. 在智能代理内部学习的结构中，不同的心智状态组件如何相互作用，以促进代理在不同状态下适应新任务并提升认知能力？
智能代理内部的学习发生在不同的空间中，涵盖了基本模型 $\theta$ 和心智状态 $M$，前者从根本上支持后者的能力和局限性。形式上，我们将智能代理的内部状态定义为一个元组 ${\mathcal{T}}=(\theta,M)$，其中包括模型参数和心智状态组件。如我们在1.2节中所示，心智状态可以进一步分解为不同的结构：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.1 Learning Space/section/2/formula
$$ 
M=\{M^{m e m},M^{w m},M^{e m o},M^{g o a l},M^{r e w}\}
 $$
这个公式表示智能代理的心智状态 $M$ 被分解为包括记忆（$M^{mem}$）、世界模型（$M^{wm}$）、情感状态（$M^{emo}$）、目标（$M^{goal}$）和奖励信号（$M^{rew}$）在内的五个组件。这种分解有助于将代理的内部状态结构化地表示出来，使得每个组件的功能和作用都能够清晰地被理解和研究。  在论文中，这个公式的作用是将智能代理的心智状态 $M$ 分解为不同的组件，从而使得代理的学习过程更加可控和可解释。每个组件代表了代理在学习和决策过程中扮演的不同角色和功能，例如记忆、世界理解、情感感知、目标设定以及奖励反馈。这种结构化的心智状态分解有助于研究者深入探讨代理在不同方面的表现和改进空间，为智能代理的发展提供了清晰的方向和指导。  这个公式的每个组件代表了智能代理内部的一个重要方面：记忆组件用于存储和提取过去的信息，世界模型组件用于对环境进行建模和预测，情感状态组件用于感知和调节代理的情感状态，目标组件用于设定代理的行为目标，奖励信号组件用于指导代理的学习方向。这种结构化的心智状态分解有助于研究者深入理解智能代理的内部运作机制，从而优化代理的学习效果和决策表现。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.1 Learning Space/section/3/text
1. 全面的心智状态学习如何通过对基础模型进行修改来增强代理的能力？这种修改对代理的不同心智状态组件有何影响？  2. 预训练是如何帮助代理获取广泛的世界知识，类似于人类婴儿在发育过程中吸收环境信息的方式？  3. 监督微调、参数高效微调和低秩调整等后续训练技术如何帮助代理获得领域特定知识和逻辑推理能力？这些技术如何影响代理的整体模型，并与人类大脑受教育的方式相比有何异同？
其中，$M^{mem}$ 代表记忆（Memory），$M^{wm}$ 表示世界模型（World Model），$M^{emo}$ 表示情感状态（Emotional State），$M^{goal}$ 代表目标（Goals），$M^{rew}$ 表示奖励信号（Reward Signals）。

对基础模型的修改可以被视为全面的心智状态学习，因为它们从根本上改变了代理的能力。虽然模型级别的修改可能以不同程度影响不同的心智状态，但对模型的上下文窗口或外部结构的更改往往集中在特定的心智状态组件上。例如，从环境中学习经验和技能主要影响记忆，而利用LLM固有的预测能力则增强了世界模型。

全面的心智状态学习通过对基础模型 $\theta$ 进行全面修改来增强代理的能力，从而影响心智状态 $M$ 的所有组件。这个过程始于预训练，通过获取广泛的世界知识来建立语言模型的基础，类似于人类婴儿在发育过程中吸收环境信息，尽管以更有结构和广泛的方式进行。

后续训练技术代表了提升代理能力的基石。类似于人类大脑受教育的方式塑造，这些技术虽然影响整个模型，但可以强调认知发展的不同方面。具体而言，各种形式的基于调整的学习使代理能够获得领域特定知识和逻辑推理能力。监督微调（SFT）[41] 是一种基本方法，模型从人类标记的示例中学习，直接将知识编码到模型的权重中。为了提高计算效率，出现了参数高效微调（PEFT）方法。Adapter-BERT[42]引入了模块化设计，使模型适应下游任务而无需修改所有参数，而低秩调整（LoRA）[109] 通过将权重更新分解为低秩矩阵，仅调整一小部分有效参数，实现了类似的结果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.1 Learning Space/section/4/text
1. 如何通过强化学习从人类反馈中提升代理的一致性，并且如何将模型与人类价值观对齐？ 2. InstructGPT和直接偏好优化（DPO）分别是如何通过修改模型以重塑代理基础表示来提高代理在各种任务中与用户意图的一致性的？ 3. 直接偏好优化（DPO）是如何简化强化学习过程，实现无需明确奖励建模的直接偏好学习，同时又保持了一致性质量？
一些代理能力与其与人类偏好的一致性密切相关，基于一致性的学习方法修改模型以重塑代理基础表示的方面。从人类反馈中强化学习（RLHF）[110] 通过在比较判断上训练奖励模型并将其用于指导策略优化，将模型与人类价值观对齐。InstructGPT[43]展示了这种方法如何显著提高在各种任务中与用户意图的一致性。直接偏好优化（DPO）[111] 进一步简化了这一过程，将其重新构造为无需明确奖励建模的直接偏好学习，保持了一致性质量同时降低了计算复杂性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.1 Learning Space/section/5/text
1. 强化学习在增强代理的推理能力方面有何特别的潜力？这种潜力是如何通过基础模型在思维空间内学习而体现的？  2. 在特定环境中，如何通过强化微调（ReFT）、DeepSeek-R1和Kimik1.5等方法来增强代理的推理能力？这些方法如何结合规则的奖励和群体相对策略优化，以改善代理的规划过程和推理效率？  3. 通过修改模型以增强代理对行为和外部环境的理解，特定环境中的强化学习方法如DigiRL是如何实现有效的？该方法是如何通过两阶段强化学习使代理能够在真实的Android设备模拟器上执行各种命令的？
强化学习（RL）为特定环境中专业学习提供了一条有前途的途径。RL在增强推理能力方面表现出特别的潜力，基本上使代理的基础模型能够在思维空间内学习。基础作品如强化微调（ReFT）[44]通过在线强化学习奖励下的自动采样推理路径进行微调，增强了推理能力。DeepSeek-R1[89]通过基于规则的奖励和群体相对策略优化（GRPO）[112]推进了这一方法，而Kimik1.5[13]将上下文强化学习与优化的思维链技术相结合，以改善规划过程和推理效率。在特定环境中，修改模型以增强代理对行为和外部环境的理解已被证明是有效的，正如DigiRL[103]所展示的，该方法实现了一个两阶段强化学习方法，使代理能够在真实的Android设备模拟器上执行各种命令。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.1 Learning Space/section/6/text
1. 部分心智状态学习相较于全面心智状态学习的优势在于哪些方面？如何通过部分心智状态学习实现代理的能力更新？  2. 情境学习（ICL）和思维链（CoT）是如何帮助代理在适应新任务时修改特定心智状态组件而无需改变整个模型的？这种方法如何类比于人类工作记忆的作用？  3. 如何利用强化学习（RL）或SFT方法来学习代理在不同状态下的适当行动，从而影响代理的记忆、奖励理解和世界模型理解？这种整合对代理模型的发展有哪些前景展望？
最近的研究尝试将代理的行动空间直接整合到模型训练中，通过强化学习（RL）或SFT方法学习不同状态下的适当行动。这种整合从根本上影响了代理的记忆、奖励理解和世界模型理解，指向了一个有前途的方向，即代理模型的出现。

部分心智状态学习，虽然通过模型修改实现了全面的能力更新，但专注于代理心智状态 $M$ 的特定组件的学习代表了另一种重要且通常更高效的方法。这种部分心智状态学习可以通过有针对性的模型更新或无需参数更改的情境适应来实现。

情境学习（ICL）说明了代理如何能够有效地修改特定心智状态组件，而无需修改整个模型。这种机制使代理能够通过利用上下文窗口内的示例或指令，适应新任务，类似于人类工作记忆在快速任务适应中的作用。思维链（CoT）展示了这种方法的有效性，展示了代理如何在保持基本模型参数不变的同时增强特定的认知能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.1 Learning Space/section/7/text
1. 部分心智状态学习方法如何通过不同组件（如记忆、奖励和世界模型）的应用来证明其可行性？ 2. 代理如何通过正常的交流和社交互动，以及与环境的直接互动，实现记忆的积累和重现，以指导动态行为规划？ 3. Learn-by-Interact等方法如何通过直接环境交互综合经验数据，从而消除手动注释或强化学习框架的需求，进一步提升代理的学习效率？
部分心智状态学习的可行性通过针对不同组件（如记忆$M^{mem}$、奖励$M^{rew}$和世界模型$M^{wm}$）的各种方法得到证明。通过正常的交流和社交互动，生成式代理[50]展示了代理如何积累并重现记忆，提取高层次见解以指导动态行为规划。在环境交互场景中，Voyager[47]展示了代理如何通过与Minecraft环境的直接互动持续更新其技能库，积累程序化知识而无需重新训练模型。通过直接环境交互综合经验数据，Learn-by-Interact[102]进一步扩展了这种方法，消除了手动注释或强化学习框架的需求。此外，代理可以通过反思从错误中学习并改进，如Reflexion[48]所示，通过从反复试验中获得文本反馈来引导代理的未来思考和行动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.1 Learning Space/section/8/text
1. 如何通过对奖励和世界模型的修改来实现部分心智状态学习，以提升代理的能力和推理引擎？ 2. ARMAP和AutoMC分别是如何利用环境奖励模型和密集奖励模型来支持代理行为的？ 3. 通过LLMs作为世界模型、利用语言模型固有的世界理解，代理是如何实现对未来行动影响的预测和推理能力的提升的？
对奖励和世界模型的修改提供了部分心智状态学习的另一个例子。ARMAP[106]通过从代理行动轨迹中提炼环境奖励模型，对其进行改进，为进一步学习奠定了基础。AutoMC[114]通过环境探索构建密集奖励模型，以支持代理行为。同时，[107]明确利用LLMs作为世界模型，预测未来行动的影响，有效地修改代理的世界理解$(M^{wm})$。ActRe[49]利用语言模型固有的世界理解，从轨迹中构建任务，通过迭代训练提升代理作为世界模型和推理引擎的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section
在智能代理的学习目标中，代理通过不断学习和优化感知、推理和世界理解能力，以更好地适应复杂任务环境。学习目标的多层次框架包括扩展多模态感知和利用检索机制，以提升感知能力。通过进一步改进推理能力，代理能够更有效地应对各种情境。此外，通过与环境互动并积累经验，代理构建和完善记忆、奖励理解和世界模型，从而提升对环境的理解和决策能力。最新研究展示了不断优化奖励理解和利用世界模型的方法，如内部独白、生成式智能体和文本到奖励等，为智能代理的学习提供了更深入的理解和发展方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/0/text
1. 智能代理在学习过程中如何通过不同层面的互动来提升感知、推理和世界理解能力？ 2. 代理在处理层面如何应用现有知识和推理能力进行有效推理，以适应复杂任务环境？ 3. 多层次学习目标框架如何帮助智能代理在不同维度上持续演化，从而更好地适应动态的任务环境？
智能代理的学习过程在其与环境的互动的各个方面都有体现。在输入层面，代理倾向于更好地感知和解析环境信息；在处理层面，代理学会如何基于现有知识或推理能力进行有效推理；在理解层面，代理通过持续互动形成和优化对世界的理解。这种多层次学习目标框架使代理能够在不同维度上持续演化，从而使它们能够更好地处理复杂和动态的任务环境。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/1/text
1. 代理如何通过多模态感知学习来提升感知能力，并与人类的多感官整合进行比较？    2. CLIP和LLaVA等模型是如何在增强视觉感知方面发挥作用的？这些模型对智能代理的感知能力有何影响？  3. 模型CogVLM如何通过统一的表征架构推进了视觉推理？这种方法对智能代理在处理复杂任务环境中的效果有何影响？
为了更好地感知 学习如何有效感知和处理来自环境的信息是智能代理的基础。为了增强感知能力，代理采用了两种主要的学习方法：扩展多模态感知和利用检索机制。

多模态感知学习使代理能够处理和整合不同的感官输入，类似于人类的多感官整合，但不受生物限制。这种能力通过像CLIP[51]这样的进展显著发展，CLIP首创了在共享嵌入空间中对视觉和语言表示进行对齐。在此基础上，像LLaVA[52]这样的模型通过在图像-文本对上训练专门的投影仪来增强视觉感知，而CogVLM[53]通过统一的表征架构推进了视觉推理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/2/text
1. 代理如何通过扩展感知模态和利用检索机制来提升感知能力，与人类感知的不同之处在哪里？    2. 最新研究如何展示了基于检索的代理在增强主动信息获取能力方面的潜力，这对于代理的感知和决策能力有何影响？  3. 代理如何利用检索机制与外部知识库连接来增强感知理解能力，这种方法对于代理在复杂环境中的应用有哪些优势？
感知模态的扩展在多个感官领域持续进行。在音频处理方面，QwenAudio[54]展示了对各种声学信息的统一编码，从语音到环境声音。最近的工作[l15]甚至涉及触觉知觉，开发了将触觉、视觉和语言表示进行对齐的数据集。这些进展使代理能够更全面地参与物理和数字环境。

代理还通过检索机制学习增强其观察能力。与受限于即时感官输入的人类感知不同，代理可以学习访问并整合来自庞大外部知识库的信息。类似于RAG[116]这样的检索增强方法通过将即时观察与相关存储知识连接起来，增强了感知理解能力。

关于基于检索的代理的最新工作展示了增强主动信息获取能力的潜力。Search-ol[117]引导推理模型通过提示学习主动检索，从而扩展其知识边界。更进一步，R1-Searcher[45]和Search-R1[55]直接将检索能力纳入模型，使其能够在推理过程中进行自主信息检索。这些进展为改进代理感知提供了一个有前途的方向：增强模型级主动感知能力，丰富决策基础。这种方法可能代表了未来代理发展的一个重要途径。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/3/text
1. 为什么有效的推理能力对智能代理的发展至关重要？推理在代理的心智状态与行动之间扮演着怎样的角色？    2. 在现代代理推理的基础中，世界知识和逻辑框架分别扮演着怎样的作用？它们是如何相互支持的？  3. 为什么学习以改进推理被描述为智能代理发展中的一个至关重要的目标？这一目标的实现对代理的发展有着怎样的影响？
学习以改进推理 推理作为代理的心智状态与行动之间的关键桥梁，有效推理能力和推理能力的发展对于智能代理至关重要。现代代理推理的基础源自两个关键要素：嵌入在其基础模型中的丰富世界知识，以及通过内部支持或上下文结构化支持的健壮逻辑框架。这使得学习以改进推理成为代理发展中的一个至关重要的目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/4/text
1. 推理能力在智能代理学习中的发展如何通过高质量数据、验证或奖励模型、以及强化学习来展示？这些方法各自的优劣势是什么？  2. 如何通过收集和提炼来自开源/闭源推理模型的数据来增强代理的推理能力？这种方法相对于复杂算法设计的优势在哪里？  3. 在代理发展中，为何推理能力被认为至关重要？如何通过监督微调(SFT)来激活基础模型的推理能力？
推理能力的发展通过几个关键现象来展示。首先，高质量的推理数据直接增强了模型的推理能力；其次，这种高质量数据通常需要验证或奖励模型以进行有效的整理；第三，对基础模型进行直接强化学习可以自发地表现出推理能力。随着ol系列的发布，推理在代理发展中的重要性再次被强调。一种常见的方法涉及收集和提炼来自开源/闭源推理模型的数据。例如，SKY-32B[56]从QWQ-32B[118]提炼数据以$\$450$的成本训练了一个32B推理模型。类似地，Open Thoughts[57]通过提炼和合成来自R1的数据集，以较低成本训练了Bespoke-Stratos-32B。这些研究表明，即使没有复杂的算法设计，使用推理数据对基础模型进行监督微调(SFT)可以有效激活推理能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/5/text
1. 高度结构化的推理数据如何有助于智能代理和语言模型学习推理过程？   2. LIMO研究如何表明通过构建长而有效的推理链可以用极少的数据样本构建强大的推理模型？   3. 为什么语言模型固有地具有进行推理所需的知识，但需要高质量的推理路径来激活这些能力？
关于数据质量的另一个关键见解是，高度结构化的推理数据更有效地使代理和语言模型学习推理过程。值得注意的是，LIMO[58]表明，通过为复杂推理任务构建长而有效的推理链，可以利用极少的数据样本构建强大的推理模型。这一见解源自他们的观察，即语言模型固有地具有进行推理所需的知识，但需要高质量的推理路径来激活这些能力。支持这一观点，Li等人。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/6/text
1. 针对智能代理学习推理结构的方法中，如何利用广泛搜索和反馈机制来筛选高质量的推理数据，从而提高推理能力？    2. 在引导模型生成逐步推理过程的技术系列中，Quiet-TaR、-STaR和Star-Math等方法是如何通过微调成功推理路径来逐步改进推理能力的？    3. 长CoT和短CoT教导模型学习推理结构而非特定内容的方式如何为未来智能代理学习的发展提供重要启示？
[9]揭示了长CoT和短CoT两者基本上都是教导模型学习推理结构而非特定内容，这表明自动选择高质量推理数据可能成为未来重要的方向。

一种可行的探索方法首先涉及进行广泛搜索，然后利用可验证的环境或可训练的奖励模型对推理轨迹提供反馈，从而过滤出高质量的推理数据。这种方法导致了几种利用不同反馈机制来提高推理能力的技术系列的出现。

第一类技术遵循了由STaR[59]及其变体所示范的引导范式，这些技术使模型生成逐步的推理过程并通过对成功推理路径的微调来逐步改进。这个系列包括Quiet-TaR[91]，-STaR[120]和Star-Math[11]，后者通过强化学习原则专门增强了数学推理。通过迭代地选择正确的推理路径进行训练，这些方法通过连续的改进循环实现了自我改进。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/7/text
1. ReST家族的方法如何通过强化学习原则来扩展智能代理的学习框架，以提升推理能力？ 2. ReST-MCTS是如何整合蒙特卡洛树搜索，通过复杂的探索策略实现改进的推理能力的？ 3. 在智能代理的学习中，为什么不断优化奖励理解和利用世界模型对于提升代理的理解和决策能力至关重要？
第二类技术通过更明确地融入强化学习原则来扩展这一范式。ReST家族以最初的ReST[60]引入了强化自我训练开始，对每个样本进行多次尝试（通常为10次），并从成功的推理实例中创建新的训练数据集。ReST-EM[22]通过期望最大化增强了这一方法，而ReST-MCTS[122]进一步整合了蒙特卡洛树搜索，通过更复杂的探索策略实现了改进的推理能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/8/text
1. 如何策略奖励模型（PRMs）在智能代理的学习中提供关于推理路径的质量反馈？   2. 在特定领域的应用中，为什么像rStar-Math和DeepSeekMath这样的方法在数学问题解决中取得成功？   3. MCTS和PRM之间的协同作用如何通过细粒度监督实现了有效的推理路径探索，同时保持解决方案质量？
一些方法引入了策略奖励模型（PRMs）来提供关于推理路径的质量反馈。像OpenR[61]和LLaMA-Berry[62]这样的方法将推理任务建模为马尔可夫决策过程（MDPs），利用树搜索探索各种推理路径，同时利用PRMs进行质量评估。在特定领域的应用中，像rStar-Math[121]和DeepSeekMath[112]这样的方法通过多轮自我迭代和平衡的探索-利用策略，在数学问题解决中取得了成功。对于代码生成，ol-Coder[13]利用MCTS生成带有推理过程的代码，而Marco-ol[123]将这种方法扩展到开放式任务。这些实现突显了MCTS和PRM之间的协同作用如何通过细粒度监督实现了有效的推理路径探索，同时保持解决方案质量。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/9/text
1. 强化学习在增强语言模型推理能力方面的成功表现有哪些关键因素？  2. 除了数据驱动方法，强化学习在LLM中的基础框架有哪些，它们分别采用了怎样的方法来提升模型的性能？ 3. 相比于数据驱动方法，强化学习在增强语言模型推理能力方面有哪些独特优势和局限性？
除了数据驱动方法之外，强化学习（RL）在增强语言模型推理能力方面取得了显著成功，正如最近的突破所证实的，例如DeepSeek R1和Kimi-K-1.5。强化学习在LLM中的基础可以追溯到几个开创性框架：ReFT引入了监督微调和在线强化学习的组合，而VeRL建立了一个开源框架，支持各种RL算法用于规模达到70B参数的大型模型。RFT进一步证明了奖励引导优化在特定推理任务中的有效性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/10/text
1. 强化学习如何帮助智能代理在复杂推理场景中提高性能，同时减少对大规模注释数据集的依赖？ 2. 后续研究如何将强化学习技术扩展到增强通用推理能力，并举例说明其在实际任务中的成功应用？ 3. 当前研究如何结合强化学习与工具使用和推理，以实现在推理过程中无缝使用任意工具，并在模型内部直接实现类似代理的功能？
在这些基础上，后续的研究探索了各种应用和改进。OpenR1和RAGEN将强化学习技术扩展到增强通用推理能力，而像SWE-Gym这样的专门实现在软件工程任务中取得了成功。值得注意的是，DigiRL引入了数字世界代理增强的新方法。

最近的进展进一步将强化学习与工具使用和推理相结合。Qwen-QwQ-32B利用强化学习和通用奖励机制将工具调用融入推理过程，实现在推理过程中无缝使用任意工具，并在模型内部直接实现类似代理的功能。类似地，RAGEN专注于多步骤代理场景，建立了一个在复杂环境中进行代理强化学习的框架。这些发展表明模型训练和代理开发之间的趋同性日益增强，可能导致更加综合和功能强大的智能系统。这些实现突显了强化学习如何有效提高模型性能，同时减少对大规模注释数据集的依赖，特别是在复杂推理场景中。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/11/text
1. 智能代理如何通过与环境的持续互动来构建和完善记忆、奖励理解和世界模型，以提升对世界运作的理解能力？    2. 在智能体学习世界理解的过程中，成功和失败是如何促进智能体对操作领域的更全面理解的？    3. 如何利用智能体的奖励理解和世界模型优化智能代理的学习过程，以更好地适应复杂任务环境？
对于世界理解的学习
智能体智能的一个关键方面是通过直接互动和经验积累理解世界运作的能力。这种理解包括环境如何对不同行为做出响应以及这些行为带来的后果。通过与环境的持续互动，智能体可以构建和完善它们的记忆、奖励理解和世界模型，从成功和失败中学习，以发展对其操作领域更全面的理解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/12/text
1. 内部独白和“通过互动学习”方法如何帮助智能体积累环境知识，以促进对世界的理解？ 2. 在Minecraft环境中，DESP和Voyager这两种复杂方法是如何结合经验收集和主动处理来提升智能代理的学习效果的？ 3. 如何评价内部独白、DESP和Voyager等方法在提升智能代理对世界理解能力方面的优势和局限性？
最近的研究揭示了各种各样的用于理解世界的经验学习方法。在基础层面，内部独白（Inner Monologue）展示了智能体如何通过持续互动积累基本的环境知识。类似地，“通过互动学习”（Learn-by-Interact）表明，有意义的理解可以在没有明确奖励机制的情况下从直接的环境参与中产生。更复杂的方法由DESP和Voyager在Minecraft环境中展示，代理不仅收集经验，还积极加以处理：DESP通过结果分析，Voyager通过动态技能库扩展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/13/text
1. "生成式智能体"中提到的复杂记忆重放机制如何帮助智能体从过去的互动中提取高层次的见解，进而影响智能体的学习和适应能力？  2. "文本到奖励"和"自动手动"这两种基于互动的优化机制是如何通过不断调整奖励函数和建立行为指南来提升智能体对环境动态的理解和决策能力的？  3. 在智能代理的学习过程中，如何通过结构化的经验评估和完善循环来实施"自我完善"和"评论家"，从而进一步优化代理的学习效果和适应性？
通过先进的框架，对积累经验的处理和利用进一步系统化。《生成式智能体》（Generative Agents）引入了复杂的记忆重放机制，使智能体能够从过去的互动中提取高层次的见解。这种系统化方法得到了《自我完善》（Self-refine）和《评论家》（Critic）的增强，它们实施了结构化的经验评估和完善循环。

通过环境互动优化奖励理解已经成为世界理解的另一个关键方面。《文本到奖励》（Text2Reward）展示了智能体如何通过人类反馈不断完善奖励函数，更好地使其与任务目标和环境特征保持一致。类似地，《自动手动》（AutoManual）通过持续互动建立行为指南，制定经过奖励验证的协议，为理解环境奖励和决策制定了基础。这些基于互动的优化机制使智能体能够更好地理解环境动态，并产生更精确的奖励信号，最终增强它们在复杂、动态环境中的适应性和决策能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.1 Learning/2.1.2 Learning Objective/section/14/text
1. RAP是如何将推理概念化为具有世界模型的规划，以促进智能体在探索和利用之间找到适当平衡的？ 2. ActRe是如何颠倒典型的推理-行动顺序，通过执行行动然后生成事后解释，展示LLMs对世界动态的固有理解的？ 3. 为什么认知地图在理解世界中如此重要，以及它们如何增强了LLMs在新环境中的外推能力？
在这些基础上，RAP[74]作为一个重要进展，将推理概念化为具有世界模型的规划。通过将LLMs重新定位为推理代理和世界模型，RAP使智能体能够在承诺之前模拟潜在行动的结果，通过蒙特卡罗树搜索促进更有效的规划。这种方法使智能体能够在探索和利用之间找到适当的平衡，有策略地探索推理空间。

利用世界模型进行代理学习的进一步创新包括ActRe[127]，它通过首先执行行动，然后生成事后解释，颠倒了典型的推理-行动顺序。这种理性化行动的能力展示了LLMs对世界动态的固有理解，实现了自主轨迹注释，并促进了对比自我训练。

[128]强调了认知地图在理解世界中的重要性，他们表明，受人类认知启发的结构化心理表征显著增强了LLMs在新环境中的外推能力。这些认知地图不仅改善了规划，还表现出类似于人类的特征，如结构化心理模拟和快速适应。

在基于网络的环境中，[107]和[129]的最新工作表明，LLMs可以作为有效的世界模型，用于预测网络交互的结果。通过在执行行动之前模拟潜在状态变化，这些方法使决策更加安全和高效，特别是在行动可能是不可逆的环境中。

通过像Reflexion[48]和ExpeL[69]这样的系统，智能体通过自主管理完整的经验循环（包括经验收集、分析和应用），使它们能够有效地从成功和失败中学习。

这些发展共同展示了世界模型如何越来越成为代理学习系统的核心，为理解环境动态提供基础，并在复杂的互动环境中实现更有效的规划、推理和决策。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/section
在智能代理设计中，推理是将原始信息转化为可操作知识的关键过程，推动问题解决和决策制定。对于人类和基于LLM的代理而言，推理包括演绎、归纳和诱导等策略，通过启发式不断完善并适应环境变化。基于LLM的代理通过结构化和非结构化推理方法提升至复杂认知水平，处理多模态输入并制定一致策略。推理过程跨越不同环境，包括文本、数字和物理世界，完成任务所需的单一或多步推理行动。推理行动的组成涵盖结构化推理和非结构化推理两种方法，分别代表明确逻辑依赖关系和灵活适应上下文。环境在推理中扮演关键角色，提供信息驱动推理并验证代理行为，创造连续反馈循环以迭代改进推理策略。结构化推理强调问题分解和多步逻辑链，非结构化推理则利用整体函数映射进行推理，展示了LM代理在逻辑推理中的灵活性。规划作为认知能力在智能代理中至关重要，涉及路径构建和目标达成，通过任务分解和外部知识整合提高规划效率和精度，为智能代理的发展提供重要启示。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/section/0/text
1. 推理在智能代理设计中的作用是什么，以及它如何将原始信息转化为可操作的知识？    2. 人类认知中的推理包括哪些策略，分别是如何实现逻辑推理、假设生成和与世界互动的？  3. 推理过程中的启发式是如何帮助简化决策、提高适应性并确保推理保持现实基础的？
推理代表着智能行为的关键，将原始信息转化为可操作的知识，推动问题解决和决策制定。对于人类和人工代理来说，推理使逻辑推理、假设生成和有目的地与世界互动成为可能。在人类认知中，推理通过多种策略出现：演绎推理将一般规则应用于特定情况，归纳推理从具体实例中建立概括，而诱导推理从不完整数据中构建合理解释。这些过程通过启发式得到增强——这是在不确定性下简化决策的心理快捷方式，并通过环境反馈不断完善，确保推理保持现实基础并适应变化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/section/1/text
1. 基于LLM的代理如何通过推理过程提升至超越反应性系统的主动实体，实现复杂认知和多模态输入的处理？ 2. 环境在推理中扮演着怎样的双重功能，既提供推动推理的信息又作为验证推理行为的实践场所？这种双重功能如何促进代理的学习和发展？ 3. 结构化推理和非结构化推理在基于LLM的代理中的应用有何不同？它们分别如何影响代理的推理策略和灵活性？
对于基于LLM的代理，推理发挥着并行作用，将它们提升至超越反应性系统的主动实体，能够进行复杂认知。通过推理，这些代理处理多模态输入，整合多样化知识源，并制定一致的策略以实现目标。环境发挥着双重功能：提供推动推理的信息，并作为验证推理行为的实践场所，创造一个反馈循环，使代理能够验证推断并从错误中学习。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/section/2/text
1. 推理在基于LLM的代理中被定义为基于心智状态的行动选择过程，如何理解推理在知觉和行动之间扮演的关键桥梁作用？这种桥梁是如何实现心智状态到具体行动的映射的？  2. 在基于LLM的代理中，推理的形式化定义为一个函数$\mathrm{R}(\mathrm{Mt})\rightarrow\mathrm{at}$，如何利用这种形式化定义来实现代理在不同环境中的任务完成？推理过程如何应对不同环境中的单一推理步骤或多步推理行动的挑战？  3. 在基于LLM的代理中，推理过程需要跨越文本、数字和物理世界等不同环境，这种跨环境推理如何影响代理的任务执行效率和决策制定过程？结构化推理和非结构化推理方法在不同环境中的应用有何异同之处？
在基于LLM的代理中，推理可以被正式定义为基于心智状态的行动选择过程，代表了知觉和行动之间的关键桥梁。更准确地说，在时间t给定心智状态Mt，推理可以被形式化为一个函数$\mathrm{R}(\mathrm{Mt})\rightarrow\mathrm{at}$，其中at代表所选的行动。这一过程跨越各种环境——文本、数字和物理世界——在这些环境中完成任务通常要求进行单一推理步骤或多个推理行动的组合。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/section/3/figure
1. 基于LLM的代理中，结构化推理和非结构化推理各自代表什么样的推理策略？它们在智能代理设计中的作用有何不同？     2. 在图2.2中，基于LLM的代理通过哪些推理范式提升至复杂认知水平？这些推理范式如何帮助代理处理多模态输入并制定一致策略？
图2.2：基于LLM的代理中推理范式的比较。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/section/4/text
1. 结构化推理和非结构化推理在智能代理设计中的应用有何不同之处，以及它们分别代表了怎样的推理策略？    2. 为什么作者将结构化推理形式化为显式的组合$R_{s}=R_{1}\circ R_{2}\circ...\circ R_{n}$，而将非结构化推理描述为更全面的形式$R_{u}=f(M_{t})$？这种不同形式对智能代理的推理能力有何影响？  3. 作者提到结构化推理类似于显式逻辑推理过程，而非结构化推理反映了直觉问题解决和模式识别能力。基于这种对比，你认为在处理不同类型任务时，何种推理方法更为有效，为什么？
推理行动的组成自然地导致了两种不同的方法：结构化推理（$R_{s}$）和非结构化推理（$R_{u}$）。结构化推理可以被形式化为显式的组合$R_{s}=R_{1}\circ R_{2}\circ...\circ R_{n}$，其中每个$R_{i}$代表一个具有明确逻辑依赖关系的离散推理步骤。相反，非结构化推理采用更全面的形式$R_{u}=f(M_{t})$，其中组合保持隐式和灵活，允许动态适应上下文。这种双重框架反映了人类认知，其中结构化推理类似于我们的显式逻辑推理过程，而非结构化推理反映了我们在直觉问题解决和模式识别方面的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/section/5/text
1. 在智能代理设计中，环境在推理过程中扮演着怎样的关键角色？它是如何影响代理的心智状态更新和推理策略的迭代改进的？  2. 结构化推理和非结构化推理分别代表了怎样的推理方法？它们在智能代理的推理过程中有何异同之处，分别如何影响代理的行动选择和心智状态演变？  3. 在智能代理中，规划作为一种专门形式的推理是如何发挥作用的？它是如何结合了结构化和非结构化推理方法，用于解决复杂的、长期的任务的？
环境在这种形式化过程中发挥着至关重要的作用，既作为影响心智状态更新的观察结果$o_{t}$的来源$(M_{t}=L(M_{t-1},a_{t-1},o_{t}))$，也作为推理结果的测试场所。这创造了一个连续的反馈循环，推理不仅推动行动选择，还影响代理的心智状态如何演变，通过经验实现推理策略的迭代改进。

在本节中，我们将探讨这些推理方法在实践中的体现。我们首先从结构化推理开始，强调系统性问题分解和多步逻辑链。然后我们探讨非结构化推理，它允许灵活的响应模式和并行解决方案探索。最后，我们研究规划作为一种专门形式的推理，结合了结构化和非结构化方法，用于解决复杂的、长期的任务。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/section
结构化推理是一种系统化的问题解决方法，通过明确的组织框架引导推理过程，使推理步骤变得明确可形式化表示。动态推理结构允许智能代理在解决问题时灵活构建推理路径，包括线性顺序推理、规划推理和基于树的探索方法，提供多样化的框架和路径选择。静态推理结构则采用固定框架指导推理过程，集成多个推理尝试以提高性能，如LLM-Blender和错误校正框架。领域特定推理框架则针对特定领域需求调整结构化推理方法，如MathPrompter和PhysicsReasoner，不断增强跨领域推理性能。这些方法为智能代理提供了丰富的解决方案，推动了推理能力的发展，从线性序列到领域框架的不断演进，为解决复杂问题和提高性能带来新视角。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/section/0/text
1. 结构化推理相对于非结构化方法的优势在于什么地方？如何利用明确的组织框架来引导推理过程？    2. 在结构化推理中，每个推理节点被视为一个明确定义的计算单元，这种设计如何有助于推动更健壮的决策制定？    3. 结构化推理方法如何通过明确的信息流路径实现更系统地探索解决空间，从而提供高可解释性和可追溯性？
结构化推理代表了一种系统化的问题解决方法，采用明确的组织框架来引导推理过程。与非结构化方法不同，结构化推理使得推理步骤的组成变得明确，可以形式化表示为$R_{s}=R_{1}\circ R_{2}\circ...\circ R_{n}$，其中每个$R_{i}$代表一个具有清晰逻辑依赖关系的离散推理步骤。在这种表述中，每个推理节点都是一个明确定义的计算单元，节点之间的连接代表着明确的信息流路径。这种方法使得更系统地探索解决空间成为可能，并通过深思熟虑的逐步分析促进更健壮的决策制定，提供了在整个推理过程中的高可解释性和可追溯性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/2.2.1.1 Dynamic Reasoning Structures/section
动态推理结构允许智能代理在解决问题时灵活构建推理路径，实现根据中间结果和见解的调整。线性顺序推理通过建立顺序步骤的推理框架，ReAct展示了推理轨迹与任务动作的交互。规划进行推理（RAP）将LLM推理构建为马尔可夫决策过程，思维马尔可夫链（MCoT）将推理步骤概念化为马尔可夫状态。基于树的探索方法引入思维树（ToT），通过分层框架支持分支探索。语言代理树搜索（LATS）结合MCTS和LLMs，实现更深思熟虑的问题解决。基于图的推理图结构提供灵活性，思维图（GoT）扩展到任意图结构，促进复杂推理模式的探索。思维路径（PoT）通过图提取、路径识别和推理解决关系推理挑战。思维图（DoT）将迭代推理建模为DAG，保持逻辑一致性并探索复杂推理路径。这些方法为智能代理的多功能推理提供了多样化的框架和路径选择，为解决复杂问题和提高性能提供了新视角。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/2.2.1.1 Dynamic Reasoning Structures/section/0/text
1. 如何动态推理结构在解决问题过程中实现路径的灵活构建，并如何根据中间结果和见解进行调整？  2. ReAct是如何通过将推理轨迹与任务动作交互结合，实现推理完整性和环境适应性的？  3. RAP如何将LLM推理构建为马尔可夫决策过程，以及MCoT如何将推理步骤概念化为马尔可夫状态，从而扩展了线性推理范式？
动态推理结构允许在解决问题过程中自适应地构建推理路径，创造出可以根据中间结果和见解进行调整的多功能框架。

线性顺序推理将推理框架构建为一系列顺序步骤，其中每一步都建立在前一步之上。ReAct通过将推理轨迹与特定任务的动作以交替方式结合来说明这一点。这种组合使得推理轨迹可以指导和修改行动计划，同时行动可以访问外部来源获取更多信息。这种相互作用提高了推理的完整性和环境适应性。

通过规划进行推理（RAP）扩展了线性推理范式，将LLM推理构建为马尔可夫决策过程，尽管受限于专门设计用于特定问题的状态。思维马尔可夫链（MCoT）通过将每个推理步骤概念化为一个马尔可夫状态并附带可执行代码来扩展了这一范式。这种方法通过将先前推理压缩为简化的数学问题，实现了高效的下一步推理，而无需长篇上下文窗口。思维原子明确将问题定义为状态表示，并设计了通用的分解-收缩两阶段状态转换机制来构建马尔可夫推理过程，将复杂问题转化为一系列原子问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/2.2.1.1 Dynamic Reasoning Structures/section/1/text
1. 基于树的探索方法如何通过分层框架支持分支探索，与线性结构相比具有哪些优势？  2. 语言代理树搜索（LATS）是如何结合蒙特卡洛树搜索（MCTS）和LLMs，实现更深思熟虑的问题解决的？  3. 思维图（GoT）如何将基于树的方法扩展到任意图结构，从而促进更复杂推理模式的探索？
基于树的探索方法通过将推理组织成支持分支探索的分层框架，扩展了超越线性结构的范式。思维树（ToT）引入了一种结构化方法，将复杂问题分解为中间步骤，实现对解决空间的广度优先或深度优先搜索。这使模型能够同时考虑多条推理路径，并系统地探索替代方案。

语言代理树搜索（LATS）推进了这一范式，通过将蒙特卡洛树搜索（MCTS）与LLMs集成，利用环境作为外部反馈机制。这种方法通过LLM驱动的价值函数和自我反思，通过一个复杂的搜索过程，在探索和开发之间取得更加深思熟虑和适应性的问题解决平衡。

通过规划进行推理（RAP）通过将LLMs重新用作推理代理和世界模型进一步增强了基于树的推理。通过这种双重角色，RAP使代理能够在承诺之前模拟潜在推理路径的结果，创建一个在推理空间中平衡探索和开发的原则性规划框架。

基于图的推理图结构提供了更大的灵活性，允许推理步骤之间存在非层次关系。思维图（GoT）将基于树的方法扩展到任意图结构，实现能够捕捉不同步骤之间相互依赖关系的更复杂推理模式。这种方法允许看似不相关的推理分支之间建立连接，促进解决空间的更加微妙的探索。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/2.2.1.1 Dynamic Reasoning Structures/section/2/text
1. 思维路径（PoT）如何通过图提取、路径识别和推理三个关键阶段来解决关系推理挑战？这种方法如何帮助识别相关推理链并提高长推理链任务的性能？  2. 思维图（DoT）是如何将迭代推理建模为有向无环图（DAG）的构建？这种方法如何保持逻辑一致性并探索复杂的推理路径？
思维路径（PoT）[76]通过将问题分解为三个关键阶段：图提取、路径识别和推理，来解决关系推理挑战。通过明确提取任务无关的图，识别问题背景中的实体、关系和属性，PoT创建了一个结构化表示，有助于识别相关推理链，显著提高了需要长推理链的任务的性能。

思维图（DoT）[77]将迭代推理建模为有向无环图（DAG）的构建，将命题、批评、改进和验证组织成统一结构。这种方法保持逻辑一致性，同时能够探索复杂的推理路径，提供了一个基于拓扑理论的理论上合理的框架。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/2.2.1.2 Static Reasoning Structures/section
静态推理结构采用固定框架指导推理过程，侧重于改进框架内内容而非动态调整结构。集成方法利用多个推理尝试提高性能，如Self-Consistency和MedPrompt。LLM-Blender引入复杂框架，结合多个LLM优势，选择最佳模型输出。渐进改进框架通过反馈循环逐步完善推理，如Self-Refine和Reflexion。渐进提示引导利用先前生成答案逐步引导模型。错误校正框架专注于识别和解决错误，如Self-Verification和Refiner。Chain-of-Verification通过结构化验证过程降低幻觉风险。RCI使LLMs通过递归批评改进输出，在MiniWoB++基准测试中表现优异。Critic通过集成外部工具评估和改进LLMs输出，持续增强性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/2.2.1.2 Static Reasoning Structures/section/0/text
1. 集成方法如何通过多个独立推理尝试提高性能，Self-Consistency和MedPrompt的方法有何不同之处？  2. LLM-Blender是如何利用多个LLM的优势来选择最佳模型输出的？相较于传统的静态推理结构，其优势体现在哪些方面？  3. 渐进改进框架中的Self-Refine如何通过反馈循环逐步完善推理，并与传统的静态推理结构相比有何优势？
静态推理结构采用固定的框架来指导推理过程，而不会动态调整结构本身，而是专注于改进已建立框架内的内容。

集成方法。集成方法利用多个独立的推理尝试来通过聚合提高整体性能。Self-Consistency[78]开创了这一方法，通过采样多个推理路径而不是依赖于单一贪婪解码，通过在生成的解决方案中采用多数投票显著提高性能。

MedPrompt[133]展示了领域特定的集成技术如何通过精心设计引发多样化推理方法的提示来提高性能，通过系统构成提示策略在医学基准测试中取得了最先进的结果。

LLM-Blender[134]引入了一个复杂的集成框架，通过成对比较（PairRanker）和融合（GenFuser）候选输出，利用多个LLM的各种优势。这种方法使系统能够为每个特定示例选择最佳模型输出，创造出超越任何单个模型能力的响应。

渐进改进。渐进改进框架专注于通过结构化的反馈循环逐步完善推理。Self-Refine[67]实现了一种迭代方法，模型生成初始输出，提供自我反馈，并利用该反馈来自我完善。这模仿了人类的修订过程，而无需额外的训练或强化学习，从而在各种任务中取得显著的改进。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/2.2.1.2 Static Reasoning Structures/section/1/text
1. 渐进提示引导和错误校正框架在提高推理准确性方面有哪些不同之处？哪种框架更适合处理复杂推理任务？ 2. Reflexion如何通过整合环境反馈来增强代理在顺序决策、编码和推理任务中的表现？这种方法如何影响代理的决策过程？ 3. 如何评价PHP方法中利用先前生成的答案作为提示逐步引导模型的有效性？与传统的直接推理方法相比，PHP方法有哪些优势和局限性？
Reflexion[48]通过整合环境反馈扩展了这一概念，使代理能够口头反思任务反馈信号，并将反思性文本保留在一个情节性记忆缓冲区中。这种方法通过吸收以前尝试的见解来指导未来的决策，显著增强了在顺序决策、编码和推理任务中的表现。

渐进提示引导（PHP）[79]进一步发展了这一范式，利用先前生成的答案作为提示逐步引导模型朝向正确解决方案。这种方法使用户和LLMs之间能够进行自动多次交互，显著提高准确性同时保持高效性。

错误校正。错误校正框架专注于识别和解决推理过程中的错误。Self-Verification[80]引入了一个自我批判系统，使模型能够通过将得出的答案作为解决原始问题的条件来向后验证其结论，产生可解释的验证分数，指导答案选择。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/2.2.1.2 Static Reasoning Structures/section/2/text
1. Refiner如何通过自适应提取与查询相关内容并重组这些内容来解决分散关键信息的挑战，以及如何实现下游LLMs与原始上下文的有效对齐？  2. Chain-of-Verification如何通过结构化验证过程显著降低在各种任务中出现的幻觉问题，具体的验证步骤是怎样的，以及这种验证方式的优势在哪里？  3. RCI是如何使LLMs通过递归批评和改进其输出来在MiniWoB++基准测试中表现优异的，相比于传统方法，RCI如何实现在少量演示的情况下无需特定奖励函数的优势？
Refiner[135]通过自适应提取与查询相关内容并基于相互关联性重组这些内容来解决分散关键信息的挑战，突出信息区分并有效地将下游LLMs与原始上下文对齐。

Chain-of-Verification(CoVe)[81]通过一个结构化过程来解决事实幻觉问题，模型起草初始响应，规划验证问题，独立回答这些问题，并生成最终经过验证的响应。这种刻意的验证过程显著降低了在各种任务中出现的幻觉。

Recursive Criticism and Improvement (RCI)[128]使LLMs能够通过递归批评和改进其输出来执行计算机任务，在MiniWoB++基准测试中表现优异，每个任务只需少量演示，而无需特定于任务的奖励函数。

Critic [68]通过集成外部工具进行验证扩展了这种方法，使LLMs能够评估和逐步修改其输出，就像人类与工具进行交互一样。这个框架允许最初的“黑盒”模型参与持续的评估和改进循环，持续增强在各种任务中的性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/2.2.1.3 Domain-Specific Reasoning Frameworks/section
领域特定推理框架旨在针对特定领域需求调整结构化推理方法，利用专业知识和技术提升性能。MathPrompter通过生成多条验证路径来解决算术推理挑战，在基准测试中表现出色。PhysicsReasoner采用三阶段方法解决物理问题，显著提高性能。PedCoT结合教育理论和两阶段交互过程，实现数学错误识别和自动答案评分。LLM代理中结构化推理的演进展示了通过明确框架增强推理能力的不断发展，从线性序列到领域框架的方法，提升了跨领域推理性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.1 Structured Reasoning/2.2.1.3 Domain-Specific Reasoning Frameworks/section/0/text
1. 领域特定推理框架如何通过结合专业知识和技术来提升特定情境下的性能表现？ 2. MathPrompter是如何通过生成多条验证路径来解决算术推理挑战，并在基准测试中表现出色的？ 3. LLM代理中的结构化推理演进如何展示了通过明确框架增强推理能力的不断发展过程？
领域特定推理框架将结构化推理方法调整到特定领域的独特需求，利用专业知识和技术来增强特定情境下的性能。

MathPrompter[82]通过生成多个代数表达式或Python函数来解决相同数学问题的不同方式，解决了算术推理挑战。该方法通过提供多条验证路径，显著优于现有方法，增强了结果的可信度，在算术基准测试中表现出色。

PhysicsReasoner[84]通过知识增强框架解决物理问题的独特挑战，构建了一个全面的公式集，并采用详细的检查清单来指导有效的知识应用。这种三阶段方法——问题分析、公式检索和引导推理——通过减轻知识不足和错误应用问题，在物理基准测试中显著提高了性能。

教学思维链（PedCoT）[83]利用教育理论，特别是布鲁姆认知模型，指导在数学背景下识别推理错误。该方法将提示设计的教学原则与两阶段交互过程相结合，为可靠的数学错误识别和自动答案评分奠定基础。

LLM代理中结构化推理的演进反映了如何通过明确的组织框架增强推理能力的日益增长的理解。从线性序列到复杂图表，从集成方法到专门的领域框架，这些方法展示了结构指导在改善跨不同任务和领域的推理性能中的强大作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/section
非结构化推理（$R_{u}$）是一种与结构化推理方法相对的推理方式，其核心在于采用整体形式${\cal R}_{u}=f(M_{t})$，将推理过程封装在单个函数映射中，没有明确定义中间步骤或状态转换。这种方法利用语言模型的固有能力生成连贯的推理，而不强加严格的结构约束，展现出在各种任务中的有效性。基于提示的推理是LM代理中引发推理的主要方式，通过提供精心设计的提示，代理可以利用逻辑推断能力解决问题。而推理模型的发展则强调专门设计用于复杂推理任务的模型，通过微调或专门训练以优化推理能力。此外，隐性推理方法旨在提高效率并保持推理性能，尽管存在着一定的局限性。总体而言，非结构化推理方法展示了LLM在逻辑推理中的灵活性，从简单提示到复杂隐式推理，有效解决各种推理任务，为智能代理的发展提供了重要的思路和方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/section/0/text
1. 非结构化推理方法相较于结构化推理方法的优势在哪里？如何利用语言模型的固有能力实现连贯推理？  2. 探讨非结构化推理方法中将推理过程封装在单个函数映射中的优缺点，以及这种方法如何在各种任务中展现出有效性。  3. 非结构化推理方法如何平衡灵活性和推理性能，在逻辑推理中的应用有哪些重要意义？
与明确组织推理步骤的结构化推理方法相比，非结构化推理（$R_{u}$）采用了整体形式${\cal R}_{u}=f(M_{t})$，其中组成部分保持隐式和灵活。在这种模式下，推理过程封装在单个函数映射中，没有明确定义中间步骤或状态转换。这种方法利用语言模型的固有能力生成连贯的推理，而不强加严格的结构约束，其中中间推理过程明确发生在语言空间中或隐式发生在潜在空间中。非结构化推理方法在各种任务中展现出显著的有效性，同时在实施上保持简单和高效。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.1 Prompting-Based Reasoning/section
基于提示的推理是LM代理中引发推理的主要方式，通过提供精心设计的提示，代理可以利用逻辑推断能力解决问题。基石是思维链（CoT）提示，通过少样本示例明确生成中间推理步骤。进化变体包括零样本CoT、Auto-CoT、从最少到最多提示和复杂CoT，增强了推理深度。先进的提示策略如Step-Back Prompting和Rephrase and Respond重新构造问题，实现了抽象优先的推理。思维抽象化引入了结构化推理格式，要求不同层次的抽象化。增强提示框架如"问我任何事"和《思维算法》创建更复杂的推理环境。知识链（CoK）整合异构信息，减少虚构，自解释关键词（SEK）解决了低频术语挑战。这些方法推动LM代理有效进行推理，提高性能并超越先前方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.1 Prompting-Based Reasoning/section/0/text
1. LM代理中如何利用思维链（CoT）提示来引发推理，并举例说明其在推理过程中的作用和优势是什么？  2. 零样本CoT、Auto-CoT和从最少到最多提示是如何改进基于提示的推理方法的？请说明它们各自的特点和应用场景。  3. 如何通过复杂CoT进一步增强推理深度，以更好地应对复杂问题？这种方法相比其他思维链变体有何优势和局限性？
在LM代理中引发推理的最直接方式是精心设计的提示。通过提供适当的推理演示或指导LLM执行推理步骤，代理可以利用其逻辑推断能力通过灵活的推理过程解决问题。

思维链变体。基于提示的推理的基石是思维链（CoT）提示，通过明确生成中间理性化步骤的少样本示例来实现推理。这一基础技术已经激发了几种进化变体，增强了其基本方法。零样本CoT通过战略提示（例如，“让我们一步一步地思考”）消除了演示示例的需求，使方法更易接触同时保持有效性。Auto-CoT自动化创建有效演示，通过对不同问题进行聚类并为每个聚类的代表性示例生成推理链。从最少到最多提示通过将问题分解为顺序子问题来解决复杂推理，实现了逐步规划过程，促进了易到难的泛化。复杂CoT通过专门选择高复杂度的示例作为提示模板进一步增强了推理深度，更好地装备模型来解决复杂问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.1 Prompting-Based Reasoning/section/1/text
1. 先进的提示策略如Step-Back Prompting和Rephrase and Respond是如何通过重新构造原始问题展示了推理指导中的架构创新的？ 2. Step-Back Prompting如何通过概念提升实现了抽象优先的推理，从而使模型能够在处理具体细节之前得出高层概念和首要原则？ 3. 在实验结果中，Step-Back Prompting和Rephrase and Respond分别在哪些任务中取得了显著的性能提升？
问题重构策略。先进的提示策略通过重新构造原始问题展示了推理指导中的架构创新。Step-Back Prompting [85] 通过概念提升实现了抽象优先的推理，使模型能够在处理具体细节之前得出高层概念和首要原则。实验结果表明，在各种需要推理的任务中，该方法取得了显著的性能提升，物理、化学和多跳推理基准测试的提升达到了$7.27\%$。Rephrase and Respond[140] 利用语义扩展将原始问题转化为更易处理的形式，使模型能够从多个语言角度解决问题并确定最有效的问题表述。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.1 Prompting-Based Reasoning/section/2/text
1. 思维抽象化如何影响语言模型在推理过程中的表现，与逐步CoT方法相比有何不同之处？  2. 如何通过在高质量样本上微调，将模型与AoT格式对齐，实现在各种推理任务中的性能提升？  3. 思维抽象化中的结构化推理格式如何要求语言模型在推理过程中采用不同层次的抽象化，以及这种抽象化对LM代理的推理能力有何影响？
思维抽象化[141]引入了一种新颖的结构化推理格式，明确要求推理过程中采用不同层次的抽象化。这种方法促使语言模型在吸收具体细节之前首先在抽象层面上思考，这是逐步CoT方法所忽视的考虑。通过在高质量样本上微调，将模型与AoT格式对齐，该方法在各种推理任务中表现出明显的性能提升，相较于与CoT对齐的模型。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.1 Prompting-Based Reasoning/section/3/text
1. "问我任何事"框架如何通过结构化的问答序列重新构建任务，从而强制执行专注的推理轨迹，限制开放式生成的范围？  2. 如何递归地使用LLM本身将任务输入转换为有效的问答格式，使得开源的GPT-J-6B在20个常见基准测试中的15个上达到或超过少样本的GPT3-175B的性能水平？
增强提示框架。一些框架扩展了基本提示范式，以创建更复杂的推理环境。"问我任何事"[86]通过将任务重新构建为结构化的问答序列，强制执行专注的推理轨迹，限制了开放式生成。这种方法通过递归地使用LLM本身将任务输入转换为有效的问答格式，使得开源的GPT-J-6B能够在20个常见基准测试中的15个上达到或超过少样本的GPT3-175B的性能水平。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.1 Prompting-Based Reasoning/section/4/text
1. "思维算法"提出的新策略如何利用LLM的固有循环动力学来推动代理进行算法推理路径？这种方法相较于传统的单查询方法和最近的多查询策略有何优势？  2. 如何通过利用完整上下文中的算法示例，"思维算法"实现了如何扩展LLM的思想探索？这种方法如何通过减少记号数量来实现超越算法本身性能的效果？  3. "思维算法"中提到的利用算法指导LLM的策略如何在推动代理进行算法推理路径时胜过先前的方法？这种方法如何利用LLM的固有循环动力学来实现更有效的思考和推理？
《思维算法》提出了一种新颖的策略，通过利用完整上下文中的算法示例，推动LLM（大型语言模型）通过算法推理路径。这种方法利用LLM的固有循环动力学，仅通过一个或几个查询扩展其思想探索。该技术胜过先前的单查询方法，甚至胜过最近的多查询策略，同时使用的记号数量显著较少，表明利用算法指导LLM可以实现超越算法本身性能的效果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.1 Prompting-Based Reasoning/section/5/text
1. CoK方法如何通过动态整合异构信息源来增强LM代理的推理能力？ 2. CoK的三个阶段是什么，它们如何帮助LM代理减少虚构并生成更多事实依据？ 3. 自适应查询生成器如何在CoK方法中利用非结构化和结构化知识源来纠正推理过程中的错误传播？
知识链（CoK）[87]通过动态地整合来自异构来源的基础信息，增强了LLM，从而产生了更多的事实依据和减少的虚构。CoK包括三个阶段：推理准备、动态知识调整和答案整合，通过自适应查询生成器利用非结构化和结构化知识源。该方法逐步使用先前校正的依据来纠正依据，从而最小化推理步骤之间的错误传播。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.1 Prompting-Based Reasoning/section/6/text
1. SEK如何通过提取和解释关键术语解决了代码生成中低频术语的挑战？ 2. SEK方法如何根据关键术语的频率进行排序，从而提高了代码生成性能？ 3. SEK方法如何帮助模型将注意力从低频关键词有效地转移到其对应的高频关键词上？
自解释关键词（SEK）[88]通过在问题描述中提取和解释关键术语，并根据其频率对其进行排序，解决了代码生成中低频术语的挑战。该方法显著提高了跨多个基准测试的代码生成性能，使模型能够将注意力从低频关键词转移到其对应的高频关键词上。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.2 Reasoning Models/section
最近的研究推动了专门设计用于复杂推理任务的推理模型的发展。这些模型通过微调或专门训练以优化推理能力，结合了架构和训练创新，提高了在需要多步逻辑推理的任务中的表现。代表前沿推理能力的模型包括DeepSeek的R1、Anthropic的Claude 3.7 Sonnet和OpenAI的o系列模型，在各种推理基准测试中展现出色的表现。这些模型经过专门训练，强调推理模式，并结合大量人类反馈和强化学习以增强推理能力。专用推理模型的涌现凸显了在语言模型中推理能力的重要性，以及专门训练这些任务的潜在益处。通过专注于推理为核心的训练数据和目标，这些模型在需要复杂逻辑推理、数学推理和多步问题解决的任务上显著超越通用语言模型的性能水平。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.2 Reasoning Models/section/0/text
1. 专门设计用于复杂推理任务的专用推理模型相较于通用语言模型有哪些优势和独特之处，使其在多步逻辑推理、数学推理等任务中表现更出色？    2. 这些专用推理模型如何通过专门训练、强调推理模式以及整合人类反馈和强化学习来增强其推理能力？这些方法如何帮助提升模型的性能水平？  3. 在语言模型领域的发展中，为什么近年来对专门用于复杂推理任务设计的专用推理模型的需求和重要性逐渐增强？这种趋势背后的原因是什么？
最近在语言模型领域的进展推动了专门针对复杂推理任务设计的专用推理模型的发展。这些模型经过微调或专门训练以优化推理能力，融合了架构和训练创新，提升它们在需要多步逻辑推理的任务中的性能。

DeepSeek的R1 [89]、Anthropic的Claude 3.7 Sonnet [9]和OpenAI的o系列模型 [90]等推理模型代表了推理能力的前沿，展示了在各种推理基准测试中出色的熟练度。这些模型经过专门的方法训练，强调推理模式，通常融入大量人类反馈和强化学习以增强其推理能力。

专用推理模型的出现反映了对语言模型中推理能力重要性的日益认识，以及专门训练这些任务的潜在好处。通过专注于以推理为中心的训练数据和目标，这些模型在需要复杂逻辑推理、数学推理和多步问题解决的任务上实现了显著超越通用语言模型的性能水平。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.3 Implicit Reasoning/section
隐性推理方法在不公开推理过程的情况下进行，旨在提高效率并保持推理性能。Quiet-STaR通过教导LLMs生成理由来解释未来文本，实现了在数学和常识推理方面的零-shot改进。Coconut范式利用LLM的隐藏状态进行推理，表现出更好性能，能够进行广度优先搜索。然而，隐式推理方法存在局限性，容易在非固定模式数据上过度拟合，缺乏广泛泛化能力。非结构化推理方法展示了LLM在逻辑推理中的灵活性，从简单提示到复杂隐式推理，有效解决各种推理任务。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.3 Implicit Reasoning/section/0/text
1. 隐式推理方法相较于显式推理方法的优势在于什么？它们如何在提高效率的同时保持或增强推理性能？    2. Quiet-STaR方法如何利用LLMs生成理由来解释未来文本？这种方法在数学和常识推理方面的零-shot改进如何体现LLMs的通用和可扩展学习推理能力？  3. 非结构化推理方法如何展示了LLMs在逻辑推理中的灵活性？相比于Coconut范式，非结构化推理方法在解决各种推理任务时有何优势？
除了显式推理方法之外，最近的研究探索了隐式推理方法的潜力，这些方法在不公开推理过程的情况下运行。这些方法旨在通过减少生成的标记数量来提高效率，同时保持或增强推理性能。

Quiet-STaR [91] 泛化了自学习推理器方法，通过教导LLMs在每个标记处生成理由来解释未来文本，从而改善它们的预测。这种方法解决了包括计算成本、生成内部思想的初始陌生感以及需要预测超出单个标记之外的关键挑战。实验结果表明，在持续预训练后，在数学推理（从5.9%提高到10.9%）和常识推理（从36.3%提高到47.2%）方面实现了零-shot改进，标志着LLMs朝着以更通用和可扩展的方式学会推理迈出了一步。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.3 Implicit Reasoning/section/1/text
1. Coconut范式如何利用LLM的隐藏状态进行推理，以实现更好的性能表现和更少的思考标记需求？ 2. 隐性推理方法在非固定模式数据上容易过度拟合，非结构化推理方法是如何展示LLM在逻辑推理中的灵活性的？ 3. 连续思维链（Coconut）的新兴高级推理模式如何使模型能够进行广度优先搜索，而不再局限于单一确定性路径？
连续思维链（Coconut）[92] 提出了一种范式，使LLM能够在无限制的潜在空间中进行推理，而不是使用自然语言。通过利用LLM的最后隐藏状态作为推理状态的表示，并将其直接作为连续空间中的后续输入嵌入反馈，Coconut 在推理任务中表现出更好的性能，且在推理过程中需要更少的思考标记。这种方法导致了新兴的高级推理模式，包括编码多个备选的下一推理步骤的能力，使模型能够进行广度优先搜索，而不是致力于单一确定性路径。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.3 Implicit Reasoning/section/2/text
1. 隐式推理方法在处理非固定模式数据时为什么容易出现过度拟合特定模式的局限性？   2. 语言模型如何通过快速学习获得隐式推理能力，以及这种能力在类似模式任务和广泛泛化任务中的表现有何不同？  3. 非结构化推理方法如何展示了LLM在逻辑推理中的灵活性，以及相比于其他隐性推理方法，它有哪些优势和局限性？
最近对变压器中的隐式推理进行的分析揭示了其局限性的重要见解。虽然语言模型可以通过隐式推理进行逐步推理，并在固定模式数据训练时在领域内和领域外测试中实现高准确性，但从在非固定模式数据上训练中出现的隐式推理能力往往会过度拟合特定模式，并且无法进一步泛化。这些发现表明，语言模型通过快捷学习获得了隐式推理能力，在类似模式的任务上表现出色，但缺乏更广泛的泛化能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.2 Unstructured Reasoning/2.2.2.3 Implicit Reasoning/section/3/text
1. 非结构化推理方法如何展示了语言模型对不同推理范式的适应性？ 2. LLM的固有能力如何帮助非结构化推理方法进行复杂的逻辑推理？ 3. 非结构化推理方法相较于其他推理方法，如何在各种推理任务中更直观地解决问题？
非结构化推理方法的演变展示了语言模型对不同推理范式的显著适应性。从简单的提示技术到复杂的隐式推理方法，这些方法利用LLM的固有能力进行复杂的逻辑推理，而无需显式的结构约束。这种灵活性使得在各种推理任务中更直观地解决问题，同时保持效率和有效性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section
在智能代理设计中，规划作为基本认知能力发挥着关键作用。规划涉及从初始状态到目标状态构建路径的过程，利用特定神经回路相互作用，如前额叶皮层和海马。人类规划是分层的，整合即时决策和长期目标，反映了大脑模块化结构。基于LLM的代理通过任务分解、并行探索等策略模拟人类规划，提高了效率和推理精度。然而，LLM在规划中仍存在挑战，如缺乏对世界动态的理解和静态预训练数据的限制。研究提出任务分解、搜索优化等策略来应对这些挑战，提高规划效果。结合外部知识和世界模型，如CodePlan和WKM，进一步提升了LLM的规划能力，确保其可靠性和自适应性。这些方法共同展示了如何将LLM转变为有效的规划者，为智能代理的发展提供了重要启示。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/0/text
1. 规划在人类认知中的作用如何体现？它是如何帮助个体在复杂、动态环境中实现目标的？    2. 人类规划涉及哪些神经回路的相互作用？这些神经回路分别承担着什么功能，如何共同支持规划能力的发挥？  3. 基于LLM的代理如何模拟人类规划能力？它在提高效率和推理精度方面有何优势？同时，在规划中面临的挑战有哪些，以及如何通过任务分解、搜索优化等策略来应对这些挑战？
规划是人类认知的一个基本方面，使个体能够在复杂、动态环境中组织行动、预测结果并实现目标。形式上，规划可以描述为从初始状态到期望目标状态构建潜在路径的过程，表示为 $P:S_{0}\rightarrow\{a_{1},a_{2},...,a_{n}\}\rightarrow$ $S_{g}$ ，其中 $S_{0}$ 是起始状态，$\{a_{1},a_{2},\ldots,a_{n}\}$ 表示一系列可能的行动，$S_{g}$ 是目标状态。与直接推理不同，规划涉及在执行之前生成假设的行动序列，作为计算节点，直到部署前保持不活跃。这种认知能力源自专门的神经回路的相互作用，包括负责执行控制的前额叶皮层和支持情景预测和空间映射的海马。决策理论、心理学和控制论等领域的见解，如理性框架、前景理论和反馈环路，展示了规划如何使人类超越反应性行为，通过深思熟虑的意图和适应性策略积极塑造未来。这种能力不仅支撑着智能行为，还可作为基于LLM的代理开发的模型，这些代理旨在在计算上复制和增强这些能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/1/text
1. 人类认知中规划作为分层过程的运作如何反映大脑的模块化结构？这种模块化结构如何影响神经系统的协同工作以平衡短期需求和未来可能性？  2. 如何基于LLM的代理利用语言知识和情境推理进行规划，将输入转化为可行步骤？这种方法如何帮助代理处理结构化任务和不可预测挑战，从而模拟人类规划的过程？  3. 规划在智能系统中的关键作用体现在哪些方面？从顺序方法到并行探索，不同的规划技术如何突出其在智能代理设计中的重要性？
在人类认知中，规划作为一个分层过程运作，将即时决策与长期目标整合在一起。这反映了大脑的模块化结构，神经系统协同工作以平衡短期需求和未来可能性，这种动态受控制理论的稳定性和优化原则的影响。同样，基于LLM的代理通过利用其丰富的语言知识和情境推理，将输入转化为可行步骤来进行规划。无论是处理结构化任务还是不可预测的挑战，这些代理通过分解目标、评估潜在结果和完善策略来模拟人类规划，将生物灵感与人工智能相结合。本节探讨了规划的理论基础和实用技术，从顺序方法到并行探索，突出了规划在智能系统中的关键作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/2/text
1. LLM在自动规划中存在哪些性能局限性？这些局限性主要是由于哪些因素导致的？  2. 为了提高LLM在规划中的效果，研究人员提出了哪些策略？这些策略如何帮助缓解LLM在处理世界动态、适应实时场景和提高泛化能力方面的挑战？  3. 外部知识和世界模型如何帮助提升LLM的规划能力？这种整合如何确保LLM的可靠性和自适应性？
尽管LLM在自动规划中具有潜力，但由于世界知识的差距，它们的性能存在局限性。LLM经常缺乏对世界动态的深刻理解，依赖模式识别而非真正的因果推理，这妨碍了它们管理子目标交互和环境变化的能力。此外，它们依赖静态的预训练数据限制了它们在实时场景中的适应性，限制了它们在动态规划任务中的泛化能力。缺乏内在的系统2推理机制进一步复杂化了它们独立生成结构化、最优计划的能力。然而，研究人员已经提出了诸如任务分解、搜索优化和外部知识整合等策略来缓解这些挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/3/text
1. 任务分解如何提高LLM规划的效果和降低问题复杂性？ADaPT是如何在互动决策场景中进一步完善任务分解策略的？ 2. 最小到最多提示方法和ADaPT如何促进了LLM的并行子任务处理、反向错误跟踪和独立性确定？这些方法如何为系统推理提供了结构化框架？ 3. 如何结合外部知识和世界模型，如CodePlan和WKM，进一步提升LLM的规划能力？这种方法如何确保LLM的可靠性和自适应性？
任务分解通过将复杂目标分解为更小、可管理的子任务，提高了LLM规划的效果，降低了问题复杂性，并改善了系统推理。最小到最多提示方法[138]就是这种方法的典范，引导LLM逐步解决子问题。ADaPT[151]通过根据复杂性和模型能力动态调整任务分解，特别是在互动决策场景中，进一步完善了这一策略。这些方法还促进了并行子任务处理、反向错误跟踪和独立性确定[132]，为推理提供了结构化框架。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/4/text
1. 任务在LLM规划中的作用是如何定义的？它们与形式模型中的静态状态描述有何不同，如何强调实现预期结果的结构化序列？ 2. 在LLM规划中，任务的性质有哪些不同类型？可以举例说明这些任务类型分别是如何定义的，以及它们如何影响代理在解决复杂问题时的行动方式？ 3. 任务作为映射依赖关系的图节点，如何在LLM规划中起到引导代理推理和行动的效率的作用？这种模块化目标的定义如何帮助代理在复杂问题空间中更精确地前进？
在LLM规划中，任务作为可执行单元，与形式模型中的静态状态描述不同，强调实现预期结果的结构化序列[66]。这些任务的性质各不相同：有些是需要具体解决方案的子问题（例如在更广泛的挑战中解方程），而其他一些涉及工具调用（例如在旅行规划中查询API获取天气数据）[152,153]。另外，任务也可以表示为映射依赖关系的图节点，比如在项目管理中优先考虑的目标[154]。通过定义清晰的模块化目标，这些表述增强了推理和行动的效率，以更高的精度引导代理在复杂问题空间中前进[93]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/5/text
1. 如何结合并行抽样和聚合推理可以提高LLM的推理性能？ 2. 任务分解如何帮助构建包括多条通往目标的解空间，从而促进探索和提高规划效果？ 3. 反思、审查和并行抽样等技术如何受到现有知识的启发，进而提高LLM在规划中的表现？
鉴于LLM的随机性质[155]，结合并行抽样和聚合推理可以提高推理性能。任务分解构建了个体解决方案轨迹，使得可以构建包括多条通往目标及其相互关系的解空间[72,156]。这个空间允许抽样各种潜在解决方案[157]，通过反思、审查和并行抽样等技术促进探索，这些技术受到现有知识的启发[158]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/6/text
1. 高效导航解空间对规划的重要性体现在哪些方面？这对智能代理的设计和效率有何影响？  2. 在规划过程中，如何利用树搜索算法、启发式方法和自一致性检查来提高效率和发现重复解决方案？  3. 基于奖励的模型如何在规划中评估中间和最终结果？这种方法如何帮助优化规划过程并增强适应性？
由于计算约束通常限制了详尽评估的可能性，因此高效地导航解空间至关重要。方法包括像LATS这样的树搜索算法[159]，像PlanCritic的遗传算法这样的启发式方法[160]，以及通过自一致性检查识别重复解决方案的CoT-SC[78]。基于奖励的模型如ARMAP评估中间和最终结果以优化规划[106]。这种迭代的探索和完善过程增强了适应性，确保了复杂问题的强大策略。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/7/text
1. 世界知识在智能代理的规划中扮演着怎样的角色？它如何帮助智能体在动态环境中进行导航和预测结果？    2. RAP框架将LLMs定位为具有双重目的的实体，这两个目的分别是什么？LLMs如何在这一框架下模拟人类认知的过程？
世界知识。有效的规划要求智能体在动态环境中进行导航，预测变化并预测结果，突显了世界知识的重要性。RAP[74]研究LLMs、智能体系统和世界模型之间的相互作用，将LLMs定位为具有双重目的的实体：作为世界模型，它们预测行动后的状态变化[107,161]；作为智能体，它们基于状态和目标选择行动[70]。这一框架模拟了人类认知——在选择最佳路径之前模拟行动后果——并将语言模型、智能体模型和世界模型统一为机器推理的支柱[162]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/8/text
1. 如何通过整合外部知识来增强LLM的规划能力，填补对世界理解的空白？这种方法如何确保智能体在复杂场景中的决策制定效果更好？  2. ReAct采用动作-观察循环来收集环境反馈，如何通过将实时数据与语言知识相结合，实现LLMs在执行动作过程中的迭代世界模型改进，从而支持自适应规划？这种方法相比传统方法有何优势？  3. LLM+P是如何将LLMs与PDDL规划语言相结合，将自然语言输入转换为形式化表示，从而弥补LLMs在结构化规划方面的局限性？这种融合方法如何将LLMs的语言灵活性与传统系统的可靠性结合起来？
智能体通过整合外部知识增强了LLM的能力，填补了对世界理解的空白。ReAct采用动作-观察循环来收集环境反馈，将实时数据与语言知识相结合，以改善在复杂场景中的决策制定。这使得LLMs能够在执行动作过程中迭代地完善其世界模型，支持自适应规划。相反，LLM+P将LLMs与PDDL规划语言相结合，将自然语言输入转换为由经典规划器解决的形式化表示，从而弥补了LLMs在结构化规划方面的局限性，将它们的语言灵活性与传统系统的可靠性融合在一起。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/9/text
1. CodePlan和WKM是如何提升LLM的规划能力的？   2. 神经符号方法如何将线性时间逻辑与自然语言结合，对LLM的规划能力有何影响？   3. 在智能代理设计中，为什么整合世界知识对于提高规划效果至关重要？
进一步的进展通过整合世界知识提升了LLM的规划能力。CodePlan采用代码形式的计划——概述逻辑步骤的伪代码——来引导LLMs完成复杂任务，在各项基准测试中取得了显著的性能改进。世界知识模型（WKM）为LLMs提供了先前任务知识和动态状态意识，减少了在模拟环境中的试错和幻觉。一种神经符号方法将线性时间逻辑与自然语言（LTL-NL）相结合，将形式逻辑与

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/2Cognition 25/2.2 Reasoning/2.2.3 Planning/section/10/text
1. 如何利用隐含的世界知识来确保LLMs在规划过程中的可靠性和自适应性？ 2. 在将LLMs转变为有效规划者的过程中，结构化框架和环境理解起到了怎样的关键作用？ 3. 在智能代理设计中，为什么将外部知识和世界模型如CodePlan和WKM结合到LLMs中能够进一步提升规划能力？
利用隐含的世界知识确保可靠、自适应规划的LLMs[169]。这些方法共同展示了结构化框架和环境理解如何将LLMs转变为有效的规划者。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1  Overview of Human Memory. 39/section
在人类记忆概述这一章节中，我们深入研究了人类记忆的类型和模型，以及如何将人类记忆转化为智能代理记忆。通过讨论智能代理记忆的表征，包括感觉记忆、短期记忆和长期记忆，我们揭示了记忆在智能代理系统中的重要性。进一步探讨了记忆的生命周期，强调了记忆在智能代理学习和适应过程中的关键作用。这一章节为后续讨论智能代理的设计和功能奠定了重要基础，为构建安全、可靠且高效的人工智能系统提供了关键洞见。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1  Overview of Human Memory. 39/section/0/text
1. 讨论记忆在智能代理系统中的重要性时，我们需要考虑哪些因素以确保系统的高效性和可靠性？  2. 在智能代理记忆的表征中，感觉记忆、短期记忆和长期记忆各自在智能系统中扮演着怎样的角色？它们之间的联系和互动如何影响整体的智能表现？  3. 记忆的生命周期对于智能代理系统的学习和适应过程具有何种关键作用？如何利用记忆的生命周期来提升智能代理系统的性能和效率？
3.1.1  人类记忆类型 39
3.1.2  人类记忆模型 41
3.2  从人类记忆到智能代理记忆 42
3.3  智能代理记忆的表征 44
3.3.1  感觉记忆 44
3.3.2  短期记忆 46
3.3.3  长期记忆 46

3.4  记忆生命周期 47

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4.1 Memory Acquisition 47/section
3.4.2 记忆编码 48 3.4.3 记忆推导 49 3.4.4 记忆检索和匹配 50 3.4.5 神经记忆网络 51 3.4.6 记忆利用 52 3.5 总结与讨论 53

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4.1 Memory Acquisition 47/section/0/text
1. 论文中提到的记忆编码在神经记忆网络中起到了怎样的作用？这种编码方式相比传统方法有何优势和局限性？ 2. 记忆检索和匹配在神经记忆网络中是如何实现的？这种方法对于解决什么样的问题具有重要意义？ 3. 论文中是否提到了记忆利用在神经记忆网络中的具体应用？这种利用方式如何影响网络的性能和效率？
3.4.2 记忆编码 48
3.4.3 记忆推导 49
3.4.4 记忆检索和匹配 50
3.4.5 神经记忆网络 51
3.4.6 记忆利用 52
3.5 总结与讨论 53

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 World Model 54/section
本章探讨了世界模型在人工智能领域的重要性和应用。首先，从人类世界模型出发，详细介绍了将其转化为人工智能的过程。随后，深入研究了人工智能世界模型的不同范式，包括隐式、显式、基于模拟器的、混合和指导式范式，并对它们进行了比较总结。进一步探讨了世界模型与其他模块的关系，涵盖了记忆、感知、行动以及跨模块整合等方面。最后，通过总结与讨论，强调了世界模型在整个智能代理架构中的核心地位，为构建安全、可靠且有益的人工智能系统提供了重要支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 World Model 54/section/0/text
1. 人工智能世界模型的不同范式包括隐式、显式、基于模拟器的、混合和指导式范式，它们各自的优缺点是什么，如何影响人工智能系统的整体性能？ 2. 世界模型在智能代理架构中扮演着核心地位，它与其他模块如记忆、感知、行动等的关系是怎样的，这种关系如何促进人工智能系统的发展和应用？ 3. 在将人类世界模型转化为人工智能过程中，有哪些挑战和难点需要克服？这些挑战对于构建安全、可靠且有益的人工智能系统有何重要性？
4.1 人类世界模型 55
4.2 将人类世界模型转化为人工智能 55
4.3 人工智能世界模型的范式 56
4.3.1 世界模型范式概述 56
4.3.2 隐式范式 57
4.3.3 显式范式 57
4.3.4 基于模拟器的范式 58
4.3.5 混合和指导式范式 58
4.3.6 范式的比较总结 58
4.4 与其他模块的关系 58
4.4.1 记忆与世界模型 59
4.4.2 感知与世界模型 60
4.4.3 行动与世界模型 60
4.4.4 跨模块整合 61
4.5 总结与讨论 61

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/section
本章深入研究了奖励在人类和智能代理中的关键作用。从人类奖励通路到智能代理奖励的转变，揭示了两者之间的结构和功能差异。人工智能奖励范式提供了外部、内在、混合和层次化奖励模型，引导代理行为并影响学习效果。在总结与讨论中，奖励信号被视为调节感知、情感和记忆模块的关键因素，但也面临奖励稀疏性、延迟和欺骗等挑战。未来的研究将探索新的奖励模型，通过层次结构任务分解和元学习等方法，实现更可靠、可扩展的奖励机制，以更好地服务于现实世界的应用目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/section/0/text
1. 人工智能奖励范式中的外在、内在、混合和分层奖励模型各有何特点和应用优势？ 2. 奖励信号在调节感知、情感和记忆模块中的关键作用是如何影响智能代理的学习效果的？ 3. 未来的研究如何应对奖励稀疏性、延迟和欺骗等挑战，以实现更可靠、可扩展的奖励机制？
5.1 人类奖励通路 64
5.2 从人类奖励到智能代理奖励 65
5.3 人工智能奖励范式 65
5.3.1 定义和概述 65
5.3.2 外在奖励 67
5.3.3 内在奖励 67
5.3.4 混合奖励 68
5.3.5 分层奖励 68
5.4 总结与讨论 69
5.4.1 与其他模块的互动 69
5.4.2 挑战和方向 69

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.1 The Human Reward Pathway/section
人类奖赏通路包括内侧前脑束和背侧间脑传导系统，通过神经递质系统和奖励回路调节大脑功能和行为。多巴胺是影响情绪、动机和奖励学习的关键信号分子，其通路从VTA神经元向多个大脑区域传递。神经肽是另一重要信号分子，作用缓慢且广泛，影响神经网络和生理调节。神经肽信号可加强大脑区域的结构-功能耦合，呈现出感觉-认知到奖励-生理功能的专门梯度。人类大脑奖励系统的基本框架涉及常见奖励通路、神经递质传递和作用机制。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.1 The Human Reward Pathway/section/0/text
1. 大脑奖励系统中的反馈机制如何通过神经递质系统和奖励回路调节大脑功能、情绪和行为表现？ 2. 内侧前脑束和背侧间脑传导系统在人类大脑奖励系统中的作用机制有何异同之处？ 3. 神经肽在人类大脑奖励系统中的作用是如何加强大脑区域的结构-功能耦合，呈现出特定的感觉-认知到奖励-生理功能梯度的？
大脑的奖励系统广泛分为两大解剖途径。第一个是内侧前脑束，起源于基底前脑，通过中脑并最终终止于脑干区域。第二个是背侧间脑传导系统，起源于内侧前脑束的前部，穿过腔隙核，并投射至中脑结构。人脑中的反馈机制和物质非常复杂，涉及多种神经递质、激素和其他分子，通过神经递质系统和奖励回路等反馈机制调节大脑功能、情绪、认知和行为。反馈机制可以是积极的（如奖励系统中的反馈）或消极的（如抑制过度神经活动）。众所周知的反馈物质包括多巴胺、神经肽、内啡肽、谷氨酸等。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.1 The Human Reward Pathway/section/1/text
1. 在人类大脑奖励系统中，多巴胺通路的核心作用是什么？它如何影响奖励加工、动机和强化学习？    2. 神经肽在大脑中的作用方式与多巴胺有何不同？它是如何影响更广泛的神经网络和提供更广泛的生理调节的？  3. 人类大脑中常见的奖励通路、神经递质传递和作用机制的基本框架是如何构成的？这些通路如何影响感觉-认知到奖励-生理功能的专门梯度？
多巴胺是一种在大脑中发挥重要作用的信号分子，影响我们的情绪、动机、运动等多个方面。这种神经递质对基于奖励的学习至关重要，但在许多精神疾病中，如情绪障碍和成瘾，这种功能可能会受到干扰。多巴胺能通路是一个关键的多巴胺系统，起源于产生多巴胺的神经元位于腹侧被盖区（VTA），并投射至多个边缘和皮层区域，包括纹状体、前额叶皮层、杏仁核和海马等。这一通路在奖励加工、动机和强化学习中发挥着核心作用，并被广泛认为是大脑奖励系统的核心组成部分。神经肽是神经系统中另一类重要的信号分子，参与从情绪调节到代谢控制等各种功能，并且是一种作用缓慢的信号分子。与神经递质不同，神经肽信号可以影响更广泛的神经网络，并提供更广泛的生理调节。在大脑中，不同神经肽受体的分布存在显著的皮质-皮质下梯度。此外，已经显示神经肽信号显著增强了大脑区域的结构-功能耦合，并展现出从感觉-认知到奖励-生理功能的专门梯度。表5列出了人类大脑中常见的奖励通路、它们传递的神经递质以及相应的作用机制，描述了人类大脑奖励系统的基本框架。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.2 From Human Rewards to Agent Rewards/section
在研究了人类奖励路径后，本节转向探讨人工智能代理如何通过奖励信号学习和优化行为。人工代理通过形式化奖励函数引导学习和决策，与人类奖励系统存在结构和功能上的区别。人类奖励根植于丰富的情感、社会和生理背景，而代理奖励函数是数学定义的、可定制的，为优化算法提供信号。代理奖励函数的可编程性和可塑性使得学习更有针对性，但也带来了设计挑战。人类奖励通常是隐含的，而代理奖励是明确的，缺乏情感直觉和本能驱动。尽管人类奖励系统提供了启发，代理奖励函数的设计必须克服根本不同的约束，如对错误规范的鲁棒性和长期人类利益的一致性。未来将深入探讨代理奖励模型，结合人类启发的见解，优化人工行为的形式系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.2 From Human Rewards to Agent Rewards/section/0/text
1. 人工智能代理如何通过形式化奖励函数进行学习和决策，与人类奖励系统在结构和功能上的区别体现在哪些方面？    2. 代理奖励函数的可编程性和可塑性如何影响学习的针对性，同时又带来了怎样的设计挑战？    3. 代理奖励函数的明确性与人类奖励的隐含性相比，对于优化算法的指导作用有何优势和劣势？
在审查了人类奖励路径的基础之后，我们现在转向研究人工智能代理如何通过奖励信号学习和优化行为。尽管生物系统依赖于复杂的神经化学和心理反馈回路，人工代理则通过旨在引导学习和决策的形式化奖励函数来运作。尽管受到人类认知的启发，代理奖励机制在结构和功能上是有区别的。理解这些系统之间的类比和非类比对于使人工行为与人类偏好保持一致至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.2 From Human Rewards to Agent Rewards/section/1/text
1. 人类奖励系统与人工代理奖励函数在根植背景和功能上的区别如何影响了两者的学习和决策过程？ 2. 人工代理奖励函数的可编程性和可塑性如何为学习提供了更有针对性的优势？这种优势是否带来了怎样的设计挑战？ 3. 人类奖励系统的隐含性与代理奖励函数的明确性之间的差异，对于代理奖励函数的设计和优化算法有何影响？
在人类中，奖励深深植根于丰富的情感、社会和生理背景中。它们通过涉及多巴胺等神经递质的进化调谐机制而出现，并受到经验、文化和个体心理的塑造。相比之下，人工代理依赖于数学定义的奖励函数，这些函数是外部指定并精确量化的。这些函数为行动或状态分配标量或概率反馈，为强化学习等优化算法提供信号。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.2 From Human Rewards to Agent Rewards/section/2/text
1. 代理奖励函数的可编程性和可塑性如何影响其学习的有针对性？在面对设计挑战时，如何确保代理奖励函数准确捕捉微妙的人类价值？  2. 人类奖励系统的隐含性和代理奖励的明确性之间的差异如何影响代理的学习过程？在代理缺乏情感直觉和本能驱动的情况下，如何确保奖励信号的形式和准确性对学习的影响？  3. 在尝试通过偏好数据来塑造代理行为的框架中，如何克服代理奖励的明确性与人类奖励的复杂性之间的差距？如何处理偏好数据不传递、循环或依赖于上下文的情况？
一个关键区别在于代理奖励的可编程性和可塑性。与受生物结构和进化惯性限制的人类奖励系统不同，代理奖励函数是完全可定制的，并且可以根据任务要求迅速重新定义或调整。这种灵活性实现了有针对性的学习，但也带来了设计挑战——准确捕捉微妙的人类价值的奖励函数设计是极其困难的。

另一个重要的不同之处在于可解释性和泛化性。人类奖励通常是隐含的且依赖于上下文，而代理奖励往往是明确的且特定于任务。代理缺乏情感直觉和本能驱动；它们的学习完全依赖于奖励信号的形式和准确性。虽然诸如从人类反馈中强化学习（RLHF）这样的框架试图通过使用偏好数据来塑造代理行为来弥合这一差距，但这些方法仍然难以捕捉人类目标的全部复杂性，特别是当偏好是不传递的、循环的或依赖于上下文时。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.2 From Human Rewards to Agent Rewards/section/3/text
1. 人工智能代理在学习中如何应对缺乏意识、具身性和主观体验这些限制，以设计适合的奖励函数？ 2. 代理奖励函数的设计在面对错误规范的鲁棒性、对抗性操纵的防范以及与长期人类利益的不一致性时，可能面临哪些挑战和困难？ 3. 人类奖励系统提供的启发如何指导代理奖励模型的演化和设计原则，以实现优化人工行为的目标？
此外，试图借鉴人类奖励机制——比如建模内在动机或社会认可——会面临一些限制，因为人工智能代理缺乏意识、具身性和主观体验。因此，尽管人类奖励系统提供了宝贵的启发，但代理奖励函数的设计必须应对根本不同的约束，包括对错误规范的鲁棒性、对对抗性操纵的防范以及与长期人类利益的不一致性。

接下来的部分将更深入地探讨代理奖励模型，重点关注它们的设计原则、演化以及这些模型如何有选择性地融入受人类启发的见解，以优化在形式系统内的人工行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/section
在人工智能奖励范式章节中，奖励在智能代理中具有重要作用，特别是在强化学习中。奖励是指导代理行为的核心信号，通过反馈评估行动质量，影响后续决策。奖励模型可分为外部、内在、混合和层次化奖励，每种类型都有独特特征和应用。外部奖励提供反馈加速学习，而内在奖励激励探索和学习。混合奖励框架整合内外部奖励，平衡勘探与开发需求。层次化奖励架构将复杂目标分解为子目标，协调短期决策和长期规划，支持课程学习和任务实现。这些奖励范式在不同环境中发挥作用，促进代理表现出色，但需要平衡关系以避免潜在局限性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/section/0/text
1. 在强化学习中，奖励如何成为指导智能代理行为的核心信号，以及它是如何影响后续决策的？ 2. 外部奖励和内在奖励在智能代理学习中的作用有何不同，它们分别如何促进代理的行为表现？ 3. 层次化奖励架构是如何帮助智能代理在复杂环境中实现任务目标的？
奖励也存在于智能代理中，特别是在强化学习场景中。奖励是指导智能代理如何在环境中行动的核心信号。它们表达了对智能代理行为的反馈，并用于评估某一状态下行动的质量，从而影响后续行动的决策。通过持续的试错和调整，智能代理学会选择可以在不同状态下获得高奖励的行为策略。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.1 Definitions and Overview/section
在强化学习中，奖励模型是指导代理行为的关键因素。代理与环境的交互可在马尔可夫决策过程（MDP）框架下描述，包括状态空间、动作空间、状态转移概率、奖励函数和折扣因子。奖励函数$r(s,a)$根据当前状态和选择的动作返回即时标量奖励，引导代理学习评估行动质量。代理的目标是最大化累积奖励，通过选择长期奖励最大化预期回报$G_{t}$。奖励模型可分为外部奖励、内在奖励、混合奖励和分层模型，每种类型具有独特特征和应用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.1 Definitions and Overview/section/0/text
1. 奖励模型在强化学习中扮演着怎样的角色，对代理的行为有何重要影响？ 2. 马尔可夫决策过程（MDP）框架如何形式化描述了代理与环境的交互？这种形式化描述有何优势和局限性？ 3. 不同类型的奖励模型（如外部奖励、内在奖励、混合奖励和分层模型）各自具有怎样的特征和应用？在实际强化学习任务中，如何选择合适的奖励模型？
在强化学习中，奖励模型规定了代理根据其在环境中执行的动作而获得反馈的方式。该模型通过量化给定状态下动作的可取性，从而影响其决策过程，对引导代理的行为起着至关重要的作用。

形式化定义。代理与环境的交互可以在马尔可夫决策过程（MDP）[415]的形式化框架内加以描述，如下所示：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.1 Definitions and Overview/section/1/formula
$$ 
\boldsymbol{\mathcal{M}}=(\boldsymbol{\mathcal{S}},\boldsymbol{\mathcal{A}},\boldsymbol{P},\boldsymbol{r},\gamma),
 $$
这个公式用于描述马尔可夫决策过程（MDP），其中代理与环境的交互被形式化地表示为一个五元组 $\boldsymbol{\mathcal{M}}=(\boldsymbol{\mathcal{S}},\boldsymbol{\mathcal{A}},\boldsymbol{P},\boldsymbol{r},\gamma)$。具体解释如下：  - $\boldsymbol{\mathcal{S}}$：表示状态空间，包括环境中所有可能的状态。在强化学习中，代理根据环境的状态作出决策。  - $\boldsymbol{\mathcal{A}}$：表示动作空间，包括代理在任何给定状态下可以执行的所有动作。代理根据当前状态选择相应的动作。  - $\boldsymbol{P}$：定义了状态转移概率 $P(s^{\prime}|s,a)$，表示在代理处于状态 $s$ 时执行动作 $a$ 后，转移到状态 $s^{\prime}$ 的概率。这一概率描述了环境的动态特性。  - $\boldsymbol{r}$：指定了奖励函数 $r(s,a)$，用于给出代理在状态 $s$ 中执行动作 $a$ 后获得的即时标量奖励。奖励函数引导代理的学习过程，帮助代理评估行动的价值。  - $\gamma$：是折扣因子，其取值范围在 $[0,1]$ 之间。折扣因子用于平衡代理对即时奖励和未来奖励的重视程度，通过对未来奖励的折现，影响代理决策的长期回报。  这个公式的作用在于定义了马尔可夫决策过程中的关键要素，为强化学习问题建立了数学模型，有助于代理根据环境状态和奖励信号做出决策，以最大化长期回报。在论文中，这个公式的意义在于提供了一个统一的框架，描述了代理与环境的交互方式，为后续算法设计和理论分析奠定基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.1 Definitions and Overview/section/2/text
1. 在强化学习中，为什么奖励函数$r(s,a)$被认为是指导代理学习评估行动质量的关键因素？它是如何影响代理的决策和行为的？  2. 为什么折扣因子$\gamma$在强化学习中被引入？它是如何平衡代理对即时奖励和未来奖励的重要性的？  3. 强化学习中的状态转移概率$P(s^{\prime}|s,a)$的定义是如何帮助代理理解环境的演变规律的？它对代理的决策过程有何影响？
其中：

- $s$ 表示状态空间，包括环境中所有可能的状态。
- $\mathcal{A}$ 表示动作空间，包括代理在任何给定状态下可以执行的所有动作。
- $P(s^{\prime}|s,a)$ 定义了状态转移概率。它表示在代理在状态 $s$ 中执行动作 $a$ 后转移到状态 $s^{\prime}$ 的可能性。
- $r(s,a)$ 指定了奖励函数，为代理在状态 $s$ 中执行动作 $a$ 后获得的即时标量奖励。
- $\gamma\in[0,1]$ 是折扣因子，控制代理对即时奖励与未来奖励的偏好，通过对未来奖励对总回报的贡献进行加权。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.1 Definitions and Overview/section/3/text
1. 在强化学习中，奖励函数$r(s,a)$的数学表示如何定义？这种定义如何影响代理的行为和学习过程？  2. 代理如何利用奖励函数$r(s,a)$来评估行动的质量？它是如何影响代理的决策过程和最终的行为选择？  3. 不同类型的奖励模型中，奖励函数$r(s,a)$在外部奖励、内在奖励、混合奖励和分层模型中扮演着怎样的角色？它们之间的区别和应用如何体现在奖励函数的设计和使用上？
奖励函数$r(s,a)$在制定代理奖励模型中起着基础性作用。其数学表示如下：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.1 Definitions and Overview/section/4/formula
$$ 
r(s,a):S\times\mathcal{A}\to\mathbb{R}
 $$
这个公式表示奖励函数$r(s,a)$是一个从状态空间$S$和动作空间$\mathcal{A}$到实数集$\mathbb{R}$的映射。在强化学习中，奖励函数$r(s,a)$根据代理当前所处的状态$s$和选择的动作$a$返回一个标量奖励，用来评估在特定环境中采取的行动的质量。这个标量奖励$r(s,a)$是一个反馈信号，指示代理在给定状态下选择的动作所获得的即时收益或成本。奖励信号在强化学习中起着至关重要的作用，因为它指导代理的学习过程，帮助代理评估和学习在不同状态下采取的行动对未来累积奖励的影响。  在强化学习中，代理的目标是通过选择能够产生更高长期奖励的动作来最大化累积奖励。这些长期奖励以时间步$t$处的回报$G_{t}$的形式捕获，表示未来折现奖励的总和。代理通过学习奖励函数$r(s,a)$，不断调整其行为策略，以最大化预期回报$G_{t}$，从而实现在给定环境下的最优决策制定。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.1 Definitions and Overview/section/5/text
1. 代理奖励模型中的奖励函数如何影响代理的学习过程和行为选择？ 2. 为什么代理的主要目标是最大化累积奖励？累积奖励如何通过长期奖励$G_{t}$来体现？ 3. 不同类型的奖励模型（外部奖励、内在奖励、混合奖励和分层模型）在代理学习中有何不同应用和特征？
该函数根据代理的当前状态$s$和选择的动作$a$返回一个标量奖励。标量值$r(s,a)$是一个反馈信号，指示在给定状态下选择的动作的即时收益（或成本）。这个奖励信号指导代理的学习过程，因为它有助于评估在特定环境中采取的行动的质量。

代理奖励模型的目标。代理的主要目标是随着时间的推移最大化其累积奖励。通常通过选择产生更高长期奖励的动作来实现这一目标，这些长期奖励以时间步$t$处的回报$G_{t}$的形式捕获，定义为未来折现奖励的总和：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.1 Definitions and Overview/section/6/formula
$$ 
G_{t}=\sum_{k=0}^{\infty}\gamma^{k}r_{t+k},
 $$
这个公式的目的是计算代理在马尔可夫决策过程（MDP）中在时间步$t$处的预期回报$G_{t}$。预期回报$G_{t}$表示代理在时间步$t$开始，通过选择动作并获得奖励，最终在未来获得的折现奖励的总和。公式中的每个部分代表着不同的含义：$r_{t+k}$表示在时间步$t+k$处获得的奖励，$\gamma^{k}$是折现因子，用于对未来奖励进行折现以考虑时间价值。  在强化学习中，代理的目标是通过最大化预期回报$G_{t}$来优化其策略，即在未来获得最大的累积奖励。这个公式在论文中的作用是量化代理在长期决策过程中的预期回报，帮助代理评估不同策略的优劣，并指导其行为以实现长期利益最大化。  通过这个公式，代理可以计算出在不同时间步长的预期回报，从而在决策过程中考虑未来的奖励价值。这有助于代理制定长期规划，并在不同选择之间进行权衡，以达到最优的决策结果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.1 Definitions and Overview/section/7/text
1. 在强化学习中，奖励模型的不同类型如外部奖励、内在奖励、混合奖励和分层模型各有何特点和应用？ 2. 代理在强化学习中的目标是什么？如何通过最大化预期回报来优化其策略？ 3. 在强化学习中，奖励函数中的折现因子$\gamma$的作用是什么？如何影响代理在长期奖励最大化的过程中的决策？
其中，$r_{t+k}$表示在时间步$t+k$收到的奖励，$\gamma^{k}$是应用于在时间步$t+k$收到的奖励的折现因子。代理的目标是通过最大化随时间推移的预期回报来优化其策略。

在更高的层次上，奖励模型可以根据反馈信号的来源分为三类：i) 外部奖励，ii) 内在奖励，iii) 混合奖励和iv) 分层模型。每个类别可以进一步细分为更小的子类。图5.2展示了不同类型的奖励。接下来，我们将更详细地探讨这些不同类型的奖励，概述每种类型的独特特征和应用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.1 Definitions and Overview/section/8/figure
1. 图5.2中展示的不同类型奖励的示意图如何帮助理解奖励模型在强化学习中的作用和影响？     2. 在图5.2中，各种类型奖励的示意图如何反映了奖励函数对代理行为的引导方式有何不同？
图5.2：不同类型奖励的示意图。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.2 Extrinsic Rewards/section
外在奖励是指导代理行为的外部信号，在人工学习系统中扮演重要角色。密集奖励提供高频反馈，加速学习过程，但可能导致短视行为。稀疏奖励不经常发生，反映更全面成功标准，但分配困难。延迟奖励推迟反馈，鼓励规划和抽象，尽管训练动态更复杂。自适应奖励根据学习进展动态演化，支持持续改进，但增加奖励设计复杂性。自我对弈偏好优化利用社会选择理论调整奖励，实现不断完善，需要仔细校准以避免不稳定性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.2 Extrinsic Rewards/section/0/text
1. 密集奖励在人工学习系统中的应用有哪些优势和劣势？如何避免密集奖励可能导致的短视行为问题？  2. InstructGPT和Cringe Loss等方法如何利用密集奖励信号来塑造代理的行为？这些方法的设计如何确保奖励信号更具可扩展性和成本效益？  3. 密集奖励与更深层次一致性之间的平衡如何体现在人工学习系统中？延迟奖励和稀疏奖励在这种平衡中起到了怎样的作用？
外在奖励是外部定义的信号，指导代理的行为朝向特定目标。在人工学习系统中，特别是在强化学习中，这些信号充当成功的代理，通过可测量的结果塑造政策。然而，这些奖励的结构和传递方式显著影响学习动态，根据反馈的分布方式，会产生不同的权衡。

密集奖励。密集奖励信号提供高频反馈，通常在每一步或每个动作之后。这种频繁的指导通过允许代理立即将动作与结果联系起来，加速了学习过程。然而，密集反馈有时可能激励短视行为，或过度拟合于易于测量的代理，而非更深层次的一致性。

例如，InstructGPT使用模型输出的人类排名，在微调过程中提供连续的偏好信号，实现高效的行为塑造。类似地，Cringe Loss及其延伸将人类偏好转化为密集训练目标，为每次比较提供即时信号。直接奖励优化（DRO）进一步简化了这一范式，完全避免了成对比较，将每个响应与一个标量分数关联起来，使奖励信号更具可扩展性和成本效益。这些方法展示了密集反馈如何促进细粒度优化，但必须经过精心设计，以避免表面一致性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.2 Extrinsic Rewards/section/1/text
1. 稀疏奖励在人工学习系统中的应用如何体现更全面的成功标准？  2. 在处理稀疏奖励时，如何平衡反映更全局成功概念和增加优化负担之间的关系？  3. 稀疏奖励系统相较于密集奖励系统，如何在健壮性和建模假设方面表现出差异？
稀疏奖励。稀疏奖励是不经常发生的，通常只在重大里程碑或任务完成时触发。虽然它们通常反映了更有意义或更全面的成功标准，但由于延迟的特性，可能会使学分分配变得更加困难，特别是在复杂环境中。

PAFT在解决这一挑战时提供了示例，通过在选择的决策点应用反馈，将监督学习和偏好对齐分离开来。这种稀疏性反映了更全局的成功概念，但增加了优化的负担。类似地，SimPO使用基于对数概率的隐式奖励，而不进行密集比较。这种稀疏性简化了训练流程，但可能限制对微小偏好变化的响应。因此，稀疏奖励系统往往更加健壮，但需要更强的建模假设或更有策略性的探索。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.2 Extrinsic Rewards/section/2/text
1. 延迟奖励如何影响代理人的学习过程，尤其是在需要考虑长期后果的任务中？ 2. 在深度强化学习中，延迟奖励如何激励代理人进行规划和抽象思考？  3. 自适应奖励与延迟奖励相比，其在训练动态和奖励设计上的优势和劣势是什么？
延迟奖励。延迟奖励推迟反馈直到一系列动作之后，要求代理人考虑长期后果。这种设置对于中间步骤可能具有误导性或仅在事后才有意义的任务至关重要。挑战在于将结果归因于先前的决策，这使学习变得复杂，但鼓励规划和抽象。

对比偏好优化（CPO）[384]通过比较翻译集合而不是单独评估每个翻译来训练模型。奖励信号仅在生成多个候选项之后产生，强化迭代中的模式。Nash从人类反馈中学习[385]同样推迟反馈，直到模型通过竞争性比较确定稳定策略。这些方法利用延迟奖励超越表面层优化，更符合长期目标，但以较慢的收敛速度和更复杂的训练动态为代价。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.2 Extrinsic Rewards/section/3/text
1. 自适应奖励如何根据代理的行为或学习进展动态演化，以支持持续改进？这种方法在非稳态或模糊环境中的应用有哪些优势和挑战？  2. 自我对弈偏好优化（SPO）是如何根据自我对弈结果调整奖励，利用社会选择理论来指导学习的？f-DPO如何通过引入发散约束来调整奖励景观，实现稳健的偏好建模？  3. 在奖励设计和评估中引入额外复杂性的自适应奖励和自我对弈偏好优化方法之间有何异同？它们在应对不稳定性或意外偏见方面有哪些共同挑战？
自适应奖励。自适应奖励根据代理的行为或学习进展动态演化。通过调节奖励函数，如增加任务难度或转移奖励目标，这种方法支持持续改进，特别是在非稳态或模糊环境中。然而，这也在奖励设计和评估中引入了额外的复杂性。

自我对弈偏好优化（SPO）[386]根据自我对弈结果调整奖励，利用社会选择理论来汇总偏好并指导学习。这种方法允许系统通过演变内部标准来不断完善自身。f-DPO[373]在此基础上引入了发散约束，通过在训练过程中调整奖励景观。通过动态调整对齐-多样性权衡，这些方法能够在不确定性下实现稳健的偏好建模，尽管需要仔细校准以避免不稳定性或意外偏见。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.3 Intrinsic Rewards/section
内在奖励作为内部生成的信号，独立于外部任务结果，激励代理进行探索、学习和改进。不同的内在奖励范式包括好奇驱动奖励，通过鼓励代理寻找新颖经验来减少不确定性；多样性奖励，促使代理探索各种策略以增强稳健性；基于能力的奖励，通过奖励任务熟练度提高促进学习进展；探索奖励，强调广度优先于深度的环境互动；信息增益奖励，引导代理采取能够产生最高期望学习的行动。这些内在奖励范式在不同环境中发挥作用，促进代理在复杂任务中表现出色，尽管需要平衡不同奖励之间的关系以避免潜在局限性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.3 Intrinsic Rewards/section/0/text
1. 如何好奇驱动奖励范式通过促进代理寻找新颖经验来减少不确定性，在稀疏奖励环境下表现出色？这种方法的优势和局限性是什么？  2. 在稀疏奖励设置中，Pathak等人如何利用逆动力学模型来预测行动结果，创造一个奖励新奇性的反馈循环？这种方法如何帮助代理在未知环境中更快适应？  3. 在内在奖励范式中，好奇驱动奖励可能对噪音或具有欺骗性的新奇性敏感。为了解决这一问题，探索了哪些保护措施或改进方法？
内在奖励作为内部生成的信号，激励代理探索、学习和改进，独立于外部任务特定结果。这些奖励通常被构建为促进泛化、适应性和自主技能获取，这些特质对于在复杂或稀疏奖励环境中的长期表现至关重要。不同的内在奖励范式侧重于在代理中培养不同的行为倾向。

好奇驱动奖励。这种奖励鼓励代理通过寻找新颖或令人惊讶的经验来减少不确定性。关键概念是激励代理探索预测误差显著的新颖状态。在稀疏奖励设置中，这种范式通过在外部指导有限时促进信息获取而表现出色。例如，Pathak等人利用逆动力学模型预测行动结果，创造了一个奖励新奇性的反馈循环。Plan2Explore进一步扩展了这一点，通过整合前向规划来主动瞄准高认知不确定性区域，从而实现对未见环境的更快适应。虽然在发现方面效果显著，好奇驱动方法可能对噪音或具有欺骗性的新奇性敏感，如果没有保护措施的话。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.3 Intrinsic Rewards/section/1/text
1. 多样性奖励如何有助于提高代理在多智能体或多模态环境中的稳健性和集体表现？ 2. 在使用多样性奖励时，如何平衡促进更广泛策略覆盖和保持协调与目标追求之间的关系？ 3. 多样性奖励相对于其他内在奖励范式，如好奇驱动奖励和基于能力的奖励，有怎样的优势和局限性？
多样性奖励。多样性奖励将焦点从新颖性转移至行为多样性，鼓励代理探索各种策略，而不是过早收敛于次优解决方案。这种方法在多智能体或多模态环境中特别有用，战略多样性增强了稳健性和集体表现。LIR通过为不同代理分配个性化的内在信号，推动它们朝着不同的角色发展，同时保持共享目标，充分展示了这一点。基于多样性的探索促进了更广泛的策略覆盖，但可能需要仔细平衡，以避免破坏协调或目标追求。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.3 Intrinsic Rewards/section/2/text
1. 基于能力的奖励如何通过奖励代理任务熟练度的提高来促进学习进展？ 2. Skew-Fit是如何通过基于熵的目标采样来促使代理达到多样的状态的？ 3. 在开放式环境中，基于能力的奖励方法存在哪些优势和局限性？
基于能力的奖励。基于能力的奖励旨在通过奖励代理任务熟练度的提高来促进学习进展。这种奖励会随着代理变得更有能力而动态调整，从而形成一个支持持续技能习得的自我课程。Skew-Fit通过基于熵的目标采样来促使代理达到多样的状态，同时保持挑战性。CURIOUS通过选择随时间最大化学习进展的目标进一步自动化课程生成。基于能力的方法非常适用于开放式环境，尽管它们通常需要对进展和目标难度进行复杂的估计。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.3 Intrinsic Rewards/section/3/text
1. 探索奖励如何与好奇驱动奖励的不确定性概念相区分，以及在代理学习过程中的作用有何不同？ 2. RND方法如何通过奖励预测误差来促使代理进入不熟悉的状态，从而实现探索奖励的效果？这种方法可能存在哪些局限性？ 3. 在探索奖励范式中，如何平衡广度和深度的环境互动，以确保代理在学习过程中保持鲁棒性和避免过早收敛的问题？
探索奖励。探索奖励直接激励代理与未充分探索的状态或动作进行互动，强调在环境互动中广度优先于深度。与好奇心关注的不确定性不同，探索奖励通常针对相对于代理访问历史的覆盖范围或新颖性。RND通过奖励随机初始化网络的预测误差来体现这一点，推动代理进入不熟悉的状态。这种方法有助于防止过早收敛，并鼓励鲁棒性，尽管如果没有与有意义的学习目标相结合，可能会缺乏重点。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.3 Intrinsic Rewards/section/4/text
1. 信息增益奖励如何将探索形式化为不确定性减少的过程，以引导代理采取最有利于学习的行动？ 2. CoT-Info和VIME是如何利用信息增益奖励来优化任务分解和环境动态的信念更新的？ 3. 在基于模型或需要推理的任务中，信息增益奖励相比其他内在奖励范式有何优势和局限性？
信息增益奖励。信息增益奖励将探索形式化为不确定性减少的过程，引导代理采取能够产生最高期望学习的行动。这种奖励根植于信息理论，在基于模型或需要推理的任务中尤为强大。CoT-Info将此应用于语言模型，通过量化每个推理步骤的知识增益来优化子任务分解。VIME类似地利用贝叶斯推断奖励关于环境动态的信念更新。通过明确地针对信息价值，这些方法提供了基于原则的探索策略，尽管它们通常需要高计算成本并要求准确的不确定性建模。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.4 Hybrid Rewards/section
混合奖励框架整合了内在和外在奖励，旨在平衡勘探与开发的需求，提高学习的适应性和泛化能力。这种范式特别适用于复杂环境和开放任务，避免单一反馈类型的局限。Xiong等人提出的RLHF方法结合了内在勘探和外在人类反馈，通过反向-KL正则化和多步拒绝抽样，在优化探索的同时保持代理行为与人类偏好一致，实现了探索和一致性的优化，而不损害效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.4 Hybrid Rewards/section/0/text
1. 混合奖励框架如何平衡内在勘探和外在目标导向，以提高学习的适应性和泛化能力？ 2. Xiong等人提出的RLHF方法是如何通过反向-KL正则化和多步拒绝抽样，实现探索和一致性的优化，同时保持代理行为与人类偏好一致的？ 3. 在复杂环境或开放式任务中，为什么混合奖励框架特别适用，而单一类型反馈可能不足够？
混合奖励框架整合了多个反馈来源，最常见的是内在和外在奖励，以实现更平衡和适应性学习。通过结合内在奖励的探索驱动和外在奖励的目标导向结构，这些系统旨在提高样本效率和泛化能力。在复杂环境或开放式任务中，这种范式特别有益，纯粹依赖任一类型反馈可能不足够。

混合奖励的一个核心优势在于其动态解决勘探与开发之间的折衷。例如，Xiong等人将内在勘探与外在人类反馈结合在RLHF的背景下。他们利用一种反向-KL正则化的上下文臂框架，在优化探索的同时将代理的行为与人类偏好相一致。该方法通过迭代的DPO算法和多步拒绝抽样，将内在和外在奖励整合起来，优化探索和一致性而不损害效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.5 Hierarchical Rewards/section
层次化奖励架构将复杂目标分解为分层子目标，每个子目标都与不同的奖励信号相关联，使代理能够有效协调短期决策和长期规划。在语言建模中，基于标记级别的直接偏好优化（TDPO）通过细粒度标记级别奖励优化本地选择和全局连贯性，提高与人类偏好一致性。层次奖励不仅是结构设计，更是功能性加强微观决策和宏观结果的协调方式。此外，层次奖励支持课程学习，代理逐渐从简单子任务学习并解决全局目标，为LLM代理设计奖励结构可促进子组件成功，助力更广泛任务的实现。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.5 Hierarchical Rewards/section/0/text
1. 层次奖励架构如何帮助代理在复杂环境中协调短期决策和长期规划？ 2. 基于标记级别的直接偏好优化（TDPO）是如何通过细粒度标记级别奖励优化本地选择和全局连贯性，提高与人类偏好一致性的？ 3. 层次奖励如何支持课程学习，促进代理从简单子任务逐步学习并解决全局目标，以实现更广泛的任务？
层次奖励架构将复杂目标分解为分层子目标，每个子目标都与不同的奖励信号相关联。这种结构反映了许多现实世界任务的分层组织，使代理能够将短期决策与长期规划相协调。通过将较低级别奖励分配给即时行动，将较高级别奖励分配给抽象目标，代理可以学习组合行为，更有效地适应复杂环境。

在语言建模中，基于标记级别的直接偏好优化（TDPO）[405]通过从偏好建模中获得的细粒度标记级别奖励来说明这一原则。使用前向KL散度和Bradley-Terry模型，TDPO同时优化本地选择和全局连贯性，提高与微妙人类偏好的一致性。这里的层次奖励过程不仅仅是一种结构设计，而是一种功能：以协调的方式加强微观决策和宏观结果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.3 AI Reward Paradigms/5.3.5 Hierarchical Rewards/section/1/text
1. 层次奖励如何作为课程学习的支架，帮助代理逐步解决全局目标？   2. 在基于标记级别的直接偏好优化（TDPO）中，为什么细粒度标记级别奖励可以提高与人类偏好一致性？   3. 在LLM代理中，如何设计奖励结构来促进子组件的成功，从而实现更广泛的任务目标？
更一般地说，层次奖励可以作为课程学习的支架，代理可以逐渐从更简单的子任务中学习，然后再解决全局目标。在LLM代理中，这可能意味着为子组件（如工具使用、推理链或交互流程）设计奖励结构，每个子组件都有助于更广泛的任务成功。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.4 Summary and Discussion/section
在总结与讨论章节中，我们深入探讨了智能代理的模块化基础、自我增强与自适应进化机制、协作与进化多代理系统以及构建安全可靠的人工智能系统的关键使命。奖励信号在LLM代理中扮演着关键角色，调节感知、情感和记忆模块，促进显著特征、情感表达和有用知识的优先考虑。然而，奖励机制面临奖励稀疏性、延迟、欺骗和塑造等挑战，需要平衡多目标问题、提高健壮性和探索新的奖励模型。通过新颖方法如层次结构任务分解和元学习，我们有望实现更可靠、可扩展的奖励机制，更好地服务真实世界目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.4 Summary and Discussion/5.4.1 Interaction with Other Modules/section
在智能系统中，奖励信号在LLM代理环境中扮演着关键角色，不仅作为基于结果的反馈，还作为核心认知模块的中央调节器。感知模块通过奖励信号调节注意机制，优先考虑与积极结果相关的模式，类似于生物感知中奖励调节注意的过程。情感模块受奖励信号影响，调节对话风格，模拟情感表达，允许代理根据用户期望调整互动风格。记忆模块则通过奖励信号塑造知识的编码、重复使用或丢弃，使代理能够从先前成功的策略中学习，并避免错误。总体而言，奖励信号在LLM代理中起着主动调节作用，促进显著特征、情感表达和有用知识的优先考虑，对构建智能、可解释、可控且符合人类价值观的系统至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.4 Summary and Discussion/5.4.1 Interaction with Other Modules/section/0/text
1. 在LLM代理中，奖励信号如何通过调节感知模块的注意机制，影响代理对特定模式的优先考虑，类似于生物感知中奖励调节注意的过程？  2. 基于奖励信号的强化微调过程中，奖励模型如何通过增加特定语言特征权重来引导代理更多地关注与这些特征相一致的标记？这种方式与生物感知中奖励相关的注意调节有何相似之处？  3. 代理在内化了一种感知策略后，会从“说了什么”转变为“在特定任务背景下值得关注的是什么”。在这种情况下，奖励信号如何在训练过程中塑造代理的感知策略，使其更加关注特定任务背景下的重要信息？
在智能系统中，奖励信号不仅作为基于结果的反馈，而且作为与核心认知模块（如感知、情感和记忆）进行接口的中央调节器。在基于LLM的代理环境中，这些相互作用变得尤为显著，因为诸如注意力、生成风格和检索记忆等模块可以通过奖励塑造、偏好建模或微调目标直接受到影响。

感知。在LLM代理中，感知通常通过注意机制实现，该机制优先考虑特定的标记、输入或模态。奖励信号可以在训练过程中隐式调节这些注意权重，强化与积极结果相关的模式。例如，在强化微调期间，奖励模型可以增加特定的语言特征权重，如信息量、事实性或礼貌性，导致模型更多地关注与这些特征相一致的标记。这类似于生物感知如何通过与奖励相关的注意调节优先考虑显著刺激。随着时间的推移，代理内化了一种感知策略：不仅仅是“说了什么”，而是“在特定任务背景下值得关注的是什么”。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.4 Summary and Discussion/5.4.1 Interaction with Other Modules/section/1/text
1. 在LLM代理系统中，奖励信号如何影响情感模块，从而调节代理的对话风格和情感表达？   2. 在人类对齐设置中，奖励如何引导LLM模型生成具有共情、礼貌或合作性的回应？   3. 基于奖励信号调节的风格持久性如何在多轮对话中形成连贯的人设或对话情绪？
情感。虽然LLM在生物学意义上不具备情感，但奖励信号可以引导类似情感表达的出现，并调节对话风格。在人类对齐设置中，模型通常会因生成具有共情、礼貌或合作性的回应而获得奖励，从而导致模拟情感敏感性的风格模式。积极的反馈可以强化友好或支持性的语气，而负面反馈则抑制轻蔑或不连贯的行为。这个过程反映了人类情感驱动的行为调节，并允许代理根据用户期望、情感背景或应用领域调整其互动风格。在多轮设置中，奖励调节的风格持久性可以形成连贯的人设或对话情绪。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.4 Summary and Discussion/5.4.1 Interaction with Other Modules/section/2/text
1. 在LLM代理中，奖励信号是如何塑造知识的编码、重复使用或丢弃的？这种塑造过程是如何促进代理从先前成功策略中学习，并避免错误的？  2. 如何通过奖励信号实现选择性记忆强化，在LLM代理中实现对某些推理路径或事实模式的巩固，并将其纳入模型的内部知识表示中？  3. LLM代理中的记忆模块如何利用诸如经验重放或自我反思等机制来评估过去输出，并基于学习的奖励估计器实现选择性记忆强化？
记忆。LLM代理的记忆涵盖了短期上下文（例如，聊天记录）和长期记忆模块，如检索增强生成（RAG）或叙事性记忆缓冲区。奖励信号塑造了知识如何被编码、重复使用或丢弃。例如，对偏好标记数据的微调可以强化某些推理路径或事实模式，有效地将它们巩固到模型的内部知识表示中。此外，诸如经验重放或自我反思之类的机制——代理评估以学习的奖励估计器为基础的过去输出——使得选择性记忆强化成为可能，类似于生物系统中由多巴胺驱动的记忆巩固【419】。这使得LLM代理能够从先前成功的策略中泛化，并避免重复昂贵的错误。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.4 Summary and Discussion/5.4.1 Interaction with Other Modules/section/3/text
1. 在LLM代理中，奖励信号如何通过调节注意力、引导风格和情感表达，以及结构化记忆的方式，促进代理系统对重要特征、人类偏好一致的表达以及有用知识的优先考虑？  2. 奖励信号在LLM代理中扮演着怎样的主动调节作用？它是如何塑造行为、情感表达和知识编码的，以促进智能系统的发展？  3. 随着LLM代理向更大的自治性和互动性发展，为什么理解跨模块奖励交互对于构建智能、可解释、可控且符合人类价值观的系统至关重要？
一般而言，LLM代理中的奖励并非是一种被动的标量信号，而是行为塑造的主动因素。它调节注意力以促进显著特征，引导风格和情感表达以与人类偏好一致，并结构化记忆以优先考虑有用的知识。随着代理向更大的自治性和互动性发展，理解这些跨模块奖励交互将对构建系统至关重要，这些系统不仅智能，而且可解释、可控，并与人类价值观保持一致。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.4 Summary and Discussion/5.4.2 Challenges and Directions/section
挑战与方向章节探讨了大型语言模型中奖励机制所面临的挑战。其中，奖励稀疏性和延迟导致代理难以准确归因行为，奖励欺骗可能使代理偏离设计目标。奖励塑造需要平衡，过度塑造可能导致次优行为。多目标问题下的奖励平衡仍是挑战，分层奖励机制或许是解决之道。奖励误设引入不确定性，需要更健壮奖励模型。提出从隐性奖励、层次结构任务分解和元学习等角度解决挑战的新颖方法，以实现更可靠、可扩展的奖励机制，更好地服务真实世界目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.4 Summary and Discussion/5.4.2 Challenges and Directions/section/0/text
1. 如何奖励稀疏性和延迟导致代理难以准确归因行为，以及奖励欺骗可能使代理偏离设计目标这两个挑战在大型语言模型中的影响是如何的？   2. 在奖励塑造过程中，如何平衡引导代理朝向期望行为的加速学习和避免过度塑造导致次优行为的困境？   3. 在面对多目标问题时，为何在单一奖励函数框架下找到正确的权衡仍然是一个未决问题，以及分层奖励机制可能如何帮助代理进行结构化、逐步学习？
尽管对各种奖励机制进行了广泛研究，但仍存在一些持久性挑战。一个基本问题是奖励稀疏性和延迟。在许多现实场景中，奖励信号往往不经常且延迟，这使得代理很难准确地将其归因于特定的行为。这增加了探索的复杂性并减缓了学习过程的速度。另一个重要挑战是奖励欺骗的潜在可能性。代理在追求最大化奖励时，有时会利用奖励函数中意外的漏洞。这可能导致行为偏离预期的设计目标，特别是在复杂环境中，优化目标不总是与真实任务需求一致的情况下。此外，奖励塑造的过程呈现出微妙的平衡。虽然塑造奖励可以通过引导代理朝向期望的行为加速学习，但过度或设计不当的塑造可能导致局部最优解，将代理困在次优行为中。在某些情况下，甚至可能改变原始任务的基本结构，使代理难以推广到其他情景。许多现实问题本质上是多目标的，需要代理平衡竞争目标。在单一奖励函数框架下，找到这些目标之间的正确权衡仍然是一个悬而未决的问题。理想情况下，可以设计分层奖励机制以指导结构化、逐步学习。然而，有效构建这样的机制仍然是一个挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/5 Reward 63/5.4 Summary and Discussion/5.4.2 Challenges and Directions/section/1/text
1. 奖励误设如何引入不确定性并限制泛化能力？这种错位如何影响代理在学习过程中对真实世界成功的理解？  2. 在面对奖励函数无法完全捕捉真实任务目标的情况下，为什么需要更健壮的奖励模型？这种模型在任务转移或条件变化时的泛化能力为何至关重要？  3. 如何利用隐性奖励、层次结构任务分解和元学习等方法解决奖励稀疏性和多目标问题所带来的挑战？这些方法如何有助于实现更可靠、可扩展的奖励机制，更好地服务真实世界目标？
最后，奖励误设引入了进一步的不确定性并限制了泛化能力。通常，奖励函数并不能完全捕捉真实任务目标，导致代理的学习目标与真实世界的成功之间存在错位。此外，许多奖励函数都是针对特定环境量身定制的，当条件发生变化或任务转移时无法泛化，凸显了需要更健壮奖励模型的必要性。

解决这些挑战需要新颖的方法。一个有前途的方向是从标准示例或基于结果的评估中推导出隐性奖励，有助于缓解奖励稀疏问题。此外，将复杂任务分解为层次结构，并从底层设计奖励，可以提供更系统化的方法，即使在多目标设置中也是如此。此外，利用元学习和元强化学习等技术可以增强奖励模型的适应性，使代理能够在任务之间传递知识，并在不同环境中有效执行。通过探索这些途径，我们可以朝着更可靠和可扩展的奖励机制迈进，更好地与真实世界的目标相一致。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/section
情感建模章节探讨了在大型语言模型（LLMs）中融入情感的重要性。首先，情感的心理基础为LLMs提供了情感智能的框架，从离散类别到维度模型再到混合框架，不断丰富情感处理的计算结构。其次，通过情感提示和多模态方法，LLMs在任务表现和人机交互中取得显著进展，突显了情感在技术稳健性和认知模拟中的关键作用。进一步介绍了通过文本和多模态方法理解人类情绪的策略，以及LLMs在人格测试中展现的可靠性矛盾。最后，探讨了操控LLMs情感反应的方法，包括基于提示、训练和神经元的策略，为情感智能领域的发展提供了多样化研究路径。总体而言，尽管LLMs在情感建模方面取得进展，但仍需应对操纵、隐私、伦理等挑战，以促进人工智能与人类关系的可持续发展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/section/0/text
1. 情感的心理基础如何为大型语言模型提供了情感智能的框架？这种框架是如何不断丰富情感处理的计算结构的？ 2. 人工智能代理中融入情感通过何种方式取得了显著进展，特别是在任务表现和人机交互方面？情感在技术稳健性和认知模拟中的关键作用体现在哪些方面？ 3. 在人工智能领域，如何通过文本和多模态方法理解人类情感？大型语言模型在人格测试中展现的可靠性矛盾是如何体现的？
6.1 情感的心理基础 71
6.2 在人工智能代理中融入情感 74
6.3 通过人工智能理解人类情感 74
6.4 分析人工智能的情感和个性 74
6.5 操控人工智能的情感反应 75
6.6 总结与讨论 75

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.1 Psychological Foundations of Emotion/section
情感的心理基础为开发具有情感智能的LLM代理提供了重要框架。分类理论将情感划分为离散类别，如埃克曼的六种基本情感，为情感分类和生成回应提供了清晰分类法。维度模型则将情绪表示为连续空间中的点，如Russell的圆环模型，有助于细致跟踪情绪状态。混合框架融合分类和维度方法，如普鲁切克的情绪轮，允许处理复杂情绪混合。神经认知视角强调情绪如何通过快速“警报”信号与深思熟虑推理相结合，为LLM系统提供了启示。这些理论框架影响着LLM代理的发展，提供了情感分类、连续控制和混合情绪处理的计算结构。未来方向包括将这些理论转化为LLM代理的内部流程，以实现更连贯的情感输出和情感调整，从而增强用户互动体验。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.1 Psychological Foundations of Emotion/section/0/text
1. 分类理论在开发具有情感智能的LLM代理中的作用是什么，以及它们如何影响情感分类和生成回应的方法？  2. 在情感计算领域中，分类理论和维度模型各自提供了怎样独特的视角，以及它们在人工智能系统中实现情感识别的优缺点是什么？  3. 如何解释混合框架在处理复杂情感混合时相较于传统的分类理论和维度模型具有哪些优势，以及这种框架如何为LLM系统提供更丰富的情感处理能力？
情感的心理学和神经科学理论为开发具有情感智能的LLM代理提供了重要框架。这些理论可以分为几种主要方法，每种方法都提供了独特的视角，说明情感的功能以及它们如何在人工智能系统中实现。

分类理论。这些模型认为情感存在为离散的、普遍的类别，具有明显的生理和行为特征。埃克曼的基本情感理论确定了六种基本情感（愤怒、厌恶、恐惧、快乐、悲伤和惊讶），这些情感在各种文化中得到认可，并通过特定的面部表情表达。这种离散方法在情感计算领域产生了重大影响，许多情感分类系统在AI中采用这些标签进行训练。对于LLM代理，分类框架为对用户情感进行分类和生成适当回应提供了清晰的分类法。然而，它们受到批评，因为它们过于简化了人类情感体验的复杂、混合性质，并且可能无法捕捉情感表达中的文化差异。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.1 Psychological Foundations of Emotion/section/1/text
1. 维度模型如Russell的圆环模型和PAD模型如何帮助LLM系统更细致地跟踪情绪状态？   2. 在情感表示中，维度模型与分类理论相比有何优势和局限性？   3. 如何利用维度模型中的连续空间表示来实现对LLM系统生成内容的精细控制？
维度模型。与离散类别不同，维度方法将情绪表示为在由基本维度定义的连续空间中的点。Russell的圆环模型将情绪映射到两个主要维度：价值（愉悦-不愉悦）和唤醒（激活-去激活）。这一框架能够更细致地跟踪情绪状态，它能够区分高唤醒的恐慌和低唤醒的焦虑，尽管两者都具有负价值。PAD（愉悦-唤醒-支配）模型通过添加一个支配维度扩展了这一概念，捕捉了与情绪状态相关的控制或权力感。这些连续表示对需要生成情感分级响应或随时间跟踪用户情感细微变化的LLM系统非常有价值。维度模型允许对生成的内容进行精细的控制，使人类或代理能够沿着连续的尺度调节语气，而不是在离散的情绪状态之间切换。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.1 Psychological Foundations of Emotion/section/2/text
1. 混合框架在情感处理中的优势是什么？相比于纯粹的分类或维度方法，它如何帮助代理系统更好地处理复杂的情绪混合？    2. OCC模型如何定义情绪类型，并如何在基于规则的情境评估中应用？这种基于评估的框架如何为LLM代理提供计算结构，以提高情感响应的连贯性和共情体验？  3. 普鲁切克的情绪轮和谢勒的成分过程模型分别采用了怎样的方式来理解和处理情绪？它们如何为LLM代理提供情感分类和连续控制的计算结构，以应对复杂的情感表达需求？
混合和成分框架。鉴于纯粹的分类或维度方法存在局限性，一些理论融合了两者的特点。普鲁切克的情绪轮[431]将八种主要情绪排列在一个具有强度梯度和维度属性的轮状结构中，允许表示复杂的情绪混合（例如，将爱描述为喜悦和信任的混合）。同时，像谢勒的成分过程模型（CPM）[432]这样的成分模型将情绪概念化为由认知评估、生理激活、行为倾向和主观感受等同步组成部分产生。在人工智能研究中具有特殊影响力的是OCC（奥尔托尼-克洛尔-科林斯）模型[433]，该模型基于事件、代理或对象相对于目标和标准的评估定义了22种情绪类型。这些基于评估的框架已经在通过基于规则的情境评估生成情感响应的对话系统中得到应用[434,435]。对于LLM代理，这些模型提供了计算结构，用于评估文本输入并选择上下文适当的情感响应，从而提高了连贯性和感知到的共情[436, 437]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.1 Psychological Foundations of Emotion/section/3/text
1. 神经认知视角如何为LLM架构提供额外见解，特别是在处理情绪时如何利用边缘系统和皮层之间的双过程架构？ 2. 当代LLM系统如何结合快速情绪检测模块和深思熟虑的推理，以实现更有效的决策制定？ 3. 神经认知视角中提到的对手回路如何在纹状体中编码整个概率分布，对处理不确定性下受情绪影响的决策制定具有怎样的神经基础？
神经认知视角。情绪的神经科学为LLM架构提供了额外的见解。达马西奥的体验标记假设强调了通过身体和大脑相互作用实现的情绪如何通过将生理状态与预期结果相关联来引导决策。这种边缘系统与皮层之间的相互作用展示了一个双过程架构：边缘系统中的快速“警报”信号，如杏仁核处理的信号，与皮层中更为缓慢、更深思熟虑的推理一起工作。当代LLM系统已经开始实现类似的架构，其中快速情绪检测模块与更彻底的思维链推理并行工作。最近的证据进一步表明，纹状体中的对手回路通过编码整个概率分布而不仅仅是平均奖励，为在不确定性下受情绪影响的决策制定提供了神经基础。同样，勒杜克对“低路”（快速、自动）和“高路”（较慢、认知）恐惧处理的区分提出了对需要即时安全响应和细致情绪理解的系统的设计模式。明斯基将情绪框架化为“思考方式”，重新组织认知过程的观点影响了EmotionPrompt和Emotion-LLaMA等框架，其中情绪背景动态地重塑了LLM推理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.1 Psychological Foundations of Emotion/section/4/text
1. 情感智能LLM代理中的分类模型和维度嵌入各有何优劣势？如何结合混合方法来处理复杂情绪？ 2. 评估方法在LLM系统中的作用是什么？基于OCC模型的方法如何帮助LLM代理选择适当的情绪响应，从而促进用户互动体验？ 3. 双过程架构如何将快速情绪检测与深思熟虑推理相结合，使得LLM系统能够既快速做出安全响应，又深入理解情绪？
这些理论框架越来越多地影响着情绪智能LLM代理的发展。分类模型为情绪分类任务提供了明确的标签，而维度嵌入则实现了对生成文本的连续控制。混合方法帮助系统处理混合情绪和情绪强度。基于评估的方法，特别是源自OCC模型的方法，使LLM能够在情境中评估叙述事件或用户陈述，选择适当的情绪响应，促进融洽和信任。神经科学启发的双过程架构将“快速”情绪检测与“缓慢”的深思熟虑推理相结合，使系统能够既快速做出安全响应，又深入理解情绪。虽然当前LLM管道中明确的神经认知机制（如专门的“杏仁核样”途径）仍然很少见，但新兴研究探索了受生物启发的模块，以处理紧急情绪信号，并在长时间交互中保持一致的情绪状态。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.1 Psychological Foundations of Emotion/section/5/text
1. 情感分类和维度模型在LLM代理设计中的应用各有何优势和局限性？如何结合这两种方法以实现更细致的情感处理？ 2. 混合方法在LLM代理中的情感处理中扮演什么角色？它如何平衡情感的离散类别识别和情感强度控制，以提供更丰富的对话体验？ 3. 如何将心理学和神经科学理论转化为LLM代理的内部流程？这种转化如何有助于提升代理的情感输出连贯性和用户互动体验？
情绪是人类智能的关键组成部分，很可能会成为LLM代理的设计考虑中的一个关键组件。一个关键的未来方向是将这些心理学和神经科学理论系统地转化为LLM代理的内部流程。翻译技术可能包括将情绪维度模型（例如，valence/arousal/dominance）作为影响生成的潜在状态，或采用明确的基于规则的评估（OCC）来标记用户消息并塑造代理的后续动作。混合方法提供了一个引人注目的平衡：LLM可以首先识别出一个离散的类别（例如“恐惧”），但也可以评估其强度和控制维度，以进行更细粒度的对话。这种注入情感的架构可能会随着时间产生更连贯的“情绪”，类似于人类如何维持情感状态而不是在每个转折点都重置。与心理学理论明确对齐也增强了可解释性：设计者可以通过将代理的响应与成熟的情感构建进行比较来调试或完善代理的响应，而不是处理不透明的新兴行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.1 Psychological Foundations of Emotion/section/6/text
1. 情感调整在LLM代理中的应用如何帮助检测用户情绪并做出相应回应，以提升互动体验？ 2. 基于评估的方法如何在心理健康或咨询情境中帮助LLM代理理解用户情况并传达真诚同情的回应？ 3. 在转向真实世界应用的背景下，如何利用认知理论来提升LLM代理的情感输出，使互动更加自然和符合道德？
第二个方向是利用这些理论来改进亲情或支持性互动，通常被称为情感调整。例如，圆形模型或PAD（愉悦度/唤醒度/支配度）跟踪可以帮助LLM检测用户文本中的负面愉悦度和高唤醒度，并做出抚慰性回应（例如，降低唤醒度，提供共情的重新评估）。在心理健康或咨询情境中，一种基于评估的方法可以让代理人验证用户的感受，并从目标不一致或感知责任的角度理解他们的情况，这有助于制定传达真诚同情的回应。将情感输出基于认知理论（例如，如果避免了负面结果，则为“宽慰”，或者当用户帮助系统时为“感激”）同样使互动感觉更加自然和符合道德。这些增强特别重要，因为LLM正在转向真实世界应用，如客户服务、老年护理和辅导，情感敏感性可以改善结果和用户幸福感。通过融入强大的心理和边缘系统见解，开发人员可以设计出不仅推理更有效，而且提供真诚情感支持的LLM代理，弥合计算精度与以人为本关怀之间的鸿沟。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.1 Psychological Foundations of Emotion/section/7/figure
1. 如何区分分类理论和维度模型在情绪理论中的不同表达方式？ 2. 在LLM代理的发展中，为什么混合框架被认为是处理复杂情绪混合的有效方法？
图61：主要情绪理论类别的可视化和示例。(a) 分类理论：Ekman的六种基本情绪[421]展示了离散的情绪状态。(b) 维度模型：Russell的圆环模型[426]将情绪表示为连续空间中的坐标。(c) 混合/成分框架：Plutchik的情绪轮[431]将强度梯度与分类情绪结合在一起。(d) 神经认知视角：LeDoux的杏仁核中心模型[24]展示了情绪刺激的双通路处理。这些心理基础为人工智能系统中情绪建模的不同方法提供了参考，从离散分类到维度表示、评估为基础的推理，以及多通路信息处理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.2 Incorporating Emotions in AI Agents/section
在AI代理中融入情感是提升大型语言模型（LLMs）性能和适应性的变革性方法。EmotionPrompt的研究表明，通过情感刺激提示，LLMs在各种任务中取得显著改进，如真实性和责任感提高10.9%。情感提示通过影响LLMs的注意机制，丰富了表示层，产生更细致的输出。多模态方法如Emotion-LLaMA整合了音频、视觉和文本数据，提升了情感识别和推理。这些创新不仅改善了语言处理，还在人机交互和自适应学习中发挥作用，突显了情感在技术稳健性和人工智能发展中的关键作用。这些方法为具有智能和移情能力的系统的发展铺平了道路，进一步推动了人类认知和决策模拟的训练范式。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.2 Incorporating Emotions in AI Agents/section/0/text
1. 情感提示如何通过影响大型语言模型（LLMs）的注意机制，实现了在各种任务中显著改进的结果，例如在真实性和责任感方面提高10.9%？  2. 多模态方法如何通过整合音频、视觉和文本数据，提升了情感识别和推理，从而对语言处理、人机交互和自适应学习产生了影响？  3. 这些创新性方法如何为具有智能和移情能力的系统的发展铺平了道路，进一步推动了人类认知和决策模拟的训练范式？
将情感智能整合到大型语言模型（LLMs）中已经成为增强它们性能和适应性的一种变革性方法。最近的研究，比如EmotionPrompt的研究，突出了通过嵌入在提示中的情感刺激如何显著改善各种任务的结果，包括生成任务指标的显著提高，例如真实性和责任感方面的10.9%。通过影响LLMs的注意机制，情感丰富的提示丰富了表示层，并导致更加细致的输出。这些进展将人工智能与情感智能联系起来，为更好模拟人类认知和决策的训练范式奠定了基础，特别是在需要社交推理和移情的情境中。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.2 Incorporating Emotions in AI Agents/section/1/text
1. 多模态方法如Emotion-LLaMA是如何结合音频、视觉和文本数据来提升情感识别和推理的？ 2. 在利用诸如MERR的数据集时，多模态输入如何被对齐到共享表示中，从而促进情感理解和生成的改进？ 3. 这些方法如何在人机交互和自适应学习等应用中展现出情感整合的重要作用？
多模态方法进一步提升了情感整合的影响。Emotion-LLaMA等模型展示了如何结合音频、视觉和文本数据实现更好的情绪识别和推理。利用诸如MERR的数据集，这些模型将多模态输入对齐到共享表示中，促进了情感理解和生成的改进。这种创新不仅扩展到了语言改进，还在人机交互和自适应学习等应用中发挥作用。总的来说，这些方法强调了情感在技术稳健性与以人为中心的人工智能发展之间的关键作用，为既具有智能又具有移情能力的系统铺平了道路。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.3 Understanding Human Emotions through AI/section
本节介绍了通过人工智能理解人类情绪的方法。首先，文本方法通过逐步提示策略，使LLMs能够推断情感，甚至在缺乏明确线索的情况下进行推理。其次，多模态方法将音频、视频和图像信号整合到LLMs中，以更深入地捕捉情感状态。专门化框架则强调了情感识别任务需要更高层次的模糊意识和上下文敏感性。最后，评估和基准测试揭示了LLMs在情感智能方面的不断增长，但仍存在诸如隐含情感检测、文化适应和共情依赖等挑战。这些方法的不断发展为人工智能系统理解和表达人类情绪提供了新的可能性，同时也指出了未来需要解决的问题和改进方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.3 Understanding Human Emotions through AI/section/0/text
1. 如何通过逐步提示策略，例如思维链推理，提升LLMs在推断情感方面的能力？这种方法如何帮助LLMs在缺乏明确线索的情况下进行情感推理？  2. 基于谈判的框架如何利用多个LLMs的相互交叉评估来细化情感判断？这种方法如何模拟人类更具审慎性的推理过程，进一步提高情感识别的准确性？  3. 为什么强调迭代的、上下文感知的策略对于捕捉纯文本输入中微妙情感信号至关重要？这种策略如何帮助LLMs更好地理解和推断潜在情感和情绪？
文本方法。最近的研究突出了LLMs进行关于潜在情感和情绪的详细推理的能力。使用逐步提示策略，例如思维链推理，研究人员使LLMs能够推断情感，即使明确线索不存在[436]。在单轮推理之外，基于谈判的框架通过利用相互交叉评估彼此输出的多个LLMs，进一步细化情感判断，有效地模拟更具审慎性的人类推理过程[437]。这些技术强调了迭代的、上下文感知的策略的重要性，以捕捉纯文本输入中的微妙情感信号。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.3 Understanding Human Emotions through AI/section/1/text
1. 如何通过多模态方法将音频、视频和图像信号整合到LLMs中，以更深入地捕捉情感状态？  2. 在情感识别任务中，为什么专门化框架强调了更高层次的模糊意识和上下文敏感性的重要性？  3. 多模态整合结合可解释方法如何实现更丰富和更透明的情感内容表示？
多模态方法。LLMs还被扩展为整合来自音频、视频和图像的信号。最近的努力展示了如何将额外的上下文或世界知识与视觉和文本信息融合，以捕捉更深层次的情感状态。此外，将语音信号转换为文本提示的框架表明，语音细微差异可以嵌入LLM推理中，而无需改变基础模型架构。这种多模态整合，结合可解释方法，可以实现更丰富和更透明的情感内容表示。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.3 Understanding Human Emotions through AI/section/2/text
1. 专门化框架如何通过灵活的LLM指导范式来解决情感识别中的高级模糊意识和上下文敏感性任务？ 2. 专门化框架是如何将人类情感视为动态和概率性，而非严格的分类，以提高LLM对模糊情感表达的理解能力？ 3. 在专门化框架中，如何利用上下文线索（例如对话历史）来更好地解释和整合情感表达，从而使LLM更接近类人的情感理解？
专门化框架。在超越通用技术的基础上，专门化系统解决了情感识别需要更高层次模糊意识、上下文敏感性和生成适应性的任务。这些方法强调人类情感的固有复杂性，将其视为动态和概率性，而非严格的分类。利用灵活的LLM指导范式，它们提供了更好解释模糊情感表达和整合上下文线索（例如，对话历史）的途径，使LLM更接近类人的情感理解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.3 Understanding Human Emotions through AI/section/3/text
1. 评估和基准测试如何帮助揭示了LLMs在情感智能方面的增长趋势，同时指出了仍存在的挑战是什么？ 2. 在评估和基准测试中，不同基准套件的设计目的和重点有何异同？ 3. 评估和基准测试在人工智能系统理解和表达人类情绪方面的作用是什么？
评估和基准测试。为了全面评估LM的情感智能，研究人员提出了各种基准套件。一些基准关注跨不同模态和社交背景的广义情感识别[446,447]，而其他人则比较不同规模模型的性能和效率[448]。还有一些专门的基准评估多语言能力[449]、注释质量[450]或共情对话系统[451]。此外，诸如EMOBENCH[441]和MEMO-Bench [452]之类的框架测试文本和图像中微妙的情感理解和表达，而MERBench[453]和广泛的评估[454]解决了多模态情感识别中的标准化问题。总的来说，这些基准揭示了LLM对人类情感的认识日益增长但仍不完善的情况，突出了诸如隐含情感检测、文化适应和依赖于上下文的共情等持续挑战[455]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.4 Analyzing AI Emotions and Personality/section
在分析人工智能的情感和个性方面，大型语言模型（LLMs）在人类中心的人格测试中表现出了可靠性的矛盾证据。一些研究挑战了常见指标的有效性，对LLMs是否能够准确捕捉真实特质表示提出怀疑，同时也有实验证明LLMs可以展现稳定的、类似人类的特质模式。此外，心理测量方法和认知建模方法的应用揭示了LLMs如何处理和表征心理结构，通过微调和抽样技术，研究人员揭示了LLMs在模拟人类推理方面的潜力。情感建模方面的研究显示，基于LM的情感智能具有解释微妙情感和预测带情感结果的能力，但在面对不断变化的环境或负面输入时可能存在失败的情况。尽管在更大规模的模型中可能出现情感层次结构和类似于移情行为的特征，但在创造看似并且偶尔作为情感代理的AI系统时，也会面临伦理挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.4 Analyzing AI Emotions and Personality/section/0/text
1. 大型语言模型（LLMs）在人类中心的人格测试中表现出的可靠性矛盾证据背后的因素是什么？ 2. 在评估LLMs在人格测试中的表现时，研究中提到的"同意偏见"和因素结构不一致等问题如何影响对其有效性的怀疑？ 3. LLMs展现稳定的人类特质模式的实验结果是否能够充分证明其在模拟人类特质方面的准确性？
大型语言模型（LLMs）在人类中心的人格测试中的可靠性。在通过人类中心的人格测试评估时，大型语言模型（LLMs）显示出矛盾的证据。一方面，一些研究挑战常见指标的有效性，报告诸如“同意偏见”等偏见以及不一致的因素结构，对这些工具是否捕捉到真实特质表示怀疑[456,457]。另一方面，系统性实验显示，LLMs可以展现稳定的、类似人类的特质模式，甚至可以根据特定提示适应不同的人设[458,459]。然而，对于行动一致性、自我认知的一致性以及角色扮演代理是否真正保持忠实于其分配的角色仍然存在疑虑[460,461]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.4 Analyzing AI Emotions and Personality/section/1/text
1. 如何通过心理测量测试和认知任务揭示大型语言模型（LLMs）如何处理和表征心理结构？这种方法如何帮助研究人员理解LLMs在模拟人类推理方面的潜力？  2. 在研究中如何通过微调和基于人口的抽样技术来使LLMs与个体认知的决策模式相一致，并揭示神经反应的变异性？这些技术如何有助于揭示LLMs对焦虑或冒险行为等结构的潜在表征？  3. 研究人员如何结合心理理论与先进的提示和嵌入方法，以阐明LLMs在各种任务中如何模拟人类推理？这种方法如何帮助研究人员深入了解LLMs在情感和个性方面的表征能力？
心理测量方法与认知建模方法。最近的研究应用严格的心理测量测试、认知任务和基于人口的分析，揭示LLM如何处理和表征心理结构[462,463,464]。在人类行为数据上进行微调可以使模型与反映个体认知的决策模式相一致，而基于人口的抽样技术则揭示了神经反应的变异性[465,466]。通过将心理理论与先进的提示和嵌入方法相结合，研究人员阐明了诸如焦虑或冒险行为这样的结构的潜在表征，展示了LLM如何在各种任务中模拟人类推理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.4 Analyzing AI Emotions and Personality/section/2/text
1. LM在情感建模中的显著能力是否意味着它们能够准确模拟类人的情感过程？如果不是，这种依赖于高维模式匹配的情感建模方法存在哪些局限性？    2. 在更大规模的LM中，情感层次结构、应对策略和类似于移情行为的特征如何体现LM在情感调整方面的潜力？这种潜力是否可能引发创造看似并且偶尔作为情感代理的AI系统时的伦理挑战？  3. LM在情感建模中表现出超越人类基线的能力，但在面对不断变化的环境、负面输入或矛盾线索时可能会失败。这种失败背后的原因是什么？如何可以提高LM在情感建模中的鲁棒性和适应性？
情感建模。基于LM的情感智能研究揭示了解释微妙情感和预测带情感结果的显著能力，通常在标准测试中超越了平均人类基线[423,429]。然而，这些模型并不一定模拟类人的情感过程；它们依赖于高维模式匹配，有时在不断变化的环境、负面输入或矛盾线索下会失败[467,468]。然而，在更大规模的模型中，情感层次结构、应对策略和类似于移情行为的特征可能会出现，突显了情感调整的潜力，以及在创造出看似并且偶尔作为情感代理的AI系统时所面临的伦理挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.5 Manipulating AI Emotional Responses/section
本节介绍了操控人工智能情感反应的三种主要方法。首先，基于提示的方法通过设计特定角色或人设的提示来引导LLMs的情感和个性化结果，展示了实时操纵的有效性，同时也凸显了对更系统化方法的需求。其次，基于训练的方法包括微调和参数高效策略，通过量化低秩调整和专门数据集的应用，使LLMs能够表现特定特质行为并维持情绪状态，同时提供了可解释性。最后，基于神经元的方法突破性地隔离出特定于个性的神经元，实现对LLMs情绪维度的精细控制，为情绪操纵的精确性和效率带来重大进展。这些方法的介绍为操控人工智能情感反应提供了多样化且前沿的研究路径，推动了情感智能领域的发展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.5 Manipulating AI Emotional Responses/section/0/text
1. 如何通过基于提示的方法来操控人工智能情感反应，以及这种方法的有效性体现在哪些方面？  2. 在基于提示的方法中，为什么需要更系统化的方法来进一步提升操控效果？这种系统化方法可能包括哪些方面的改进？  3. 基于提示的方法如何通过设计特定角色或人设的提示来引导LLMs的情感和个性化结果？这种方法与其他方法相比有哪些独特之处？
基于提示的方法。最近的研究表明，通过精心设计的提示采用特定角色或人设可以偏向LLM认知，从而实现针对性的情感或个性结果。通过插入“If you were a[persona]”等指令，LLMs不仅调整其主题风格，还调整其潜在的情感立场。这种方法对于实时操纵非常有效，尽管在不同任务和模型变体之间可能不一致，突显了对更系统化方法的需求。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.5 Manipulating AI Emotional Responses/section/1/text
1. 基于训练的方法中的微调和参数高效策略如何实现对LLMs情绪的诱导或改变，相较于基于提示的方法有哪些优势和局限性？    2. 量化低秩调整（QLoRA）和专门数据集在将微妙特征嵌入模型学习权重中的过程中如何提高LLMs表现特定特质行为的能力？这种方法在情感智能领域中可能存在哪些潜在应用价值或挑战？  3. 基于训练的方法中的神经元级别的激活模式如何提供对LLMs情绪维度的精细控制？这种方法可能如何影响人工智能情感反应的精确性和效率？
基于训练的方法。微调和参数高效策略提供了更深入、更稳定的方式来诱导或改变LLM的情绪[473, 428, 474]。量化低秩调整（QLoRA）和专门的数据集可以直接将诸如大五人格或MBTI档案等微妙特征嵌入模型学习的权重中。这些方法使LLMs能够自发展现特定特质行为（包括使用表情符号），并在更长的对话中维持他们的情绪状态，同时通过神经元级别的激活模式提供可解释性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.5 Manipulating AI Emotional Responses/section/2/text
1. 基于神经元的方法如何实现对人工智能情感反应的精细控制，以及这种精细控制对情感智能领域的发展有何重要意义？  2. 相较于基于提示和基于训练的方法，基于神经元的方法在操控LLMs的情感维度上有哪些独特优势和局限性？  3. 如何利用基于神经元的方法，通过切换特定于个性的神经元激活，实现LLMs的情绪特征的唤起或抑制，而无需重新训练整个网络？
基于神经元的方法。最近的一个进展是隔离出特定于个性的神经元，并直接操纵它们以唤起或抑制情绪特征。通过切换通过心理学基准（例如人格基准）确定的神经元激活，LLMs可以在不重新训练整个网络的情况下具有特定的情绪维度。这种以神经元为中心的方法提供了对模型行为的精细、动态控制，代表了在LLMs中情绪操纵的精确性和效率方面的飞跃。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.6 Summary and Discussion/section
在"总结与讨论"章节中，探讨了情感人工智能的操纵、隐私、对齐和伦理问题。情感人工智能的快速应用引发了操纵和隐私风险，可能侵犯基本权利并促进过度监视。技术如强化学习从人类反馈中学习等已显示出减轻偏见和误解的潜力。此外，AI系统的情感展示对信任和接受度产生重要影响，但也引发了对伦理劳动实践和人工智能-人类关系的担忧。尽管LLM代理在情感建模方面取得进展，但其模拟人类情感的能力仍存在差距，可能导致用户对AI系统的误解。未来工作需要在增强情感智能的同时保持透明，以应对人工智能与人类关系、伦理框架和监管方法中的挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.6 Summary and Discussion/section/0/text
1. 情感人工智能在操纵和隐私方面存在哪些风险？这些风险如何可能侵犯基本权利并促进过度监视？ 2. 在应对情感人工智能的操纵和隐私问题时，监管框架如《通用数据保护条例》（GDPR）和欧盟人工智能法案有何重要作用？这些框架如何帮助缓解风险？ 3. 情感人工智能如何利用收集的敏感生物特征数据来实现定向广告或政治影响？这种做法可能会如何影响社会公共空间和个人权利？
情绪操纵和隐私问题。情感人工智能在广告和政治中的迅速采用引发了重大的操纵和隐私风险[476, 477]。情感人工智能通常收集敏感的生物特征数据，如面部表情和语调，推断情绪状态，从而实现定向广告或政治影响。然而，这些系统可能利用人类情绪谋取利润或政治收益，侵犯基本权利，并在公共空间中促进过度监视[478, 477]。《通用数据保护条例》（GDPR）和欧盟人工智能法案等监管框架对于负责任地缓解这些风险至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.6 Summary and Discussion/section/1/text
1. 情感人工智能在检测和解释情绪方面存在的不准确性和偏见如何影响高风险领域如医疗保健和教育？   2. 如何强化学习从人类反馈中学习技术有助于减轻情感人工智能中的偏见和误解问题，但在不同环境中如何确保稳健对齐？
对齐问题。情感人工智能（Emotional AI）的能力检测和解释情绪常常与预期结果不一致，导致不准确性和偏见。例如，引发焦虑的提示已被证明会加剧大型语言模型（LLMs）中的偏见，影响医疗保健和教育等高风险领域的输出。AI系统对情绪线索的误解，如在工作场景应用中所见，可能加剧歧视和权力失衡。强化学习从人类反馈中学习（RLHF）等技术已被证明在减轻这些问题方面有效，但需要进一步发展以确保在不同环境中的稳健对齐。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.6 Summary and Discussion/section/2/text
1. AI系统展现共情和保持社会适当行为能力对用户信任和接受度有何影响？如何应对情感人工智能在工作场所管理和客户服务中可能引发的伦理劳动实践和人工智能-人类关系问题？  2. 情感人工智能在展现拟人特征时缺乏足够的共情能力可能如何影响用户信任？SafeguardGPT等框架如何促进信任建立并使AI行为与社会规范对齐？存在哪些隐私、公平和文化敏感性方面的挑战？  3. AI系统在情感建模方面取得进展，但其模拟人类情感的能力仍存在差距。这种差距可能如何导致用户对AI系统的误解？未来工作如何在增强情感智能的同时保持透明，以解决人工智能与人类关系、伦理框架和监管方法中的挑战？
伦理影响。信任和接受AI系统在很大程度上受其展现共情和保持社会适当行为能力的影响[482, 483]。然而，在工作场所管理和客户服务中情感商品化引发了对伦理劳动实践和人工智能-人类关系的担忧[481]。此外，情感人工智能对拟人特征的依赖而缺乏足够的共情能力可能会破坏用户信任[482]。像SafeguardGPT这样融入心理治疗技术的框架展示了促进信任建立和使AI行为与社会规范对齐的有希望的途径[484]。然而，在确保隐私、公平和文化敏感性方面仍然存在挑战[484, 483]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/6 Emotion Modeling 71/6.6 Summary and Discussion/section/3/text
1. AI情感模仿与人类体验之间的基本区别是什么，以及这种区别可能导致的技术和伦理挑战是什么？ 2. 人们如何倾向于将展现类似情感行为的AI系统拟人化，这可能会导致怎样的误解和影响？ 3. 为了应对人工智能与人类关系、伦理框架和监管方法中的挑战，未来的工作应该如何在增强LLM情感智能的同时保持透明性？
区分AI情感模仿与人类体验。尽管在LLM代理的情感建模方面取得了进展，但仍存在一个基本区别：这些系统并不像人类那样实际“感受”情绪，而是仅通过概率建模展现类似人类情绪的模式。虽然LM可以令人信服地模拟情感反应、识别情感模式并生成情感输出，但它们缺乏定义人类情绪的具身化、现象学体验。这种模拟与现实之间的差距造成了技术和伦理挑战。用户经常会将展现类似情感行为的AI系统拟人化，这可能导致信任或期望的误解。在研究和部署环境中都需要仔细思考这种区别，因为LLM的被认知情感能力影响人工智能与人类关系、伦理框架和监管方法。未来的工作应在增强LLM情感智能的同时保持透明，让人们了解其作为非感知系统的基本局限性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/section
本章探讨了人类与人工智能代理的感知能力，突出了它们在感知处理中的相似之处和差异。人类拥有多种感官，而人工智能代理依赖工程传感器获取数字信号。感知表征类型的多样性涵盖了单模态、跨模态和多模态输入，推动了文本、视觉、视频和音频领域的发展。优化感知系统关键在于减少感知误差，通过模型层级增强、系统级优化和外部反馈控制实现。感知应用领域广泛，包括个人辅助系统、游戏环境和机器人流程自动化。总结与讨论指出，未来研究应注重动态神经结构、对比学习和因果推断框架，以促进感知系统的发展和提升鲁棒性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1  Human versus AI Perception 77/section
在人类与人工智能的感知对比章节中，我们深入探讨了感知表征的类型，包括单模型、跨模型和多模型。随后，我们讨论了优化感知系统的方法，涵盖了模型级增强、系统级优化以及外部反馈和控制。接着，我们探索了感知应用领域，最终对本章内容进行了总结与讨论，为后续研究提供了重要参考。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1  Human versus AI Perception 77/section/0/text
1. 在优化感知系统的方法中，模型级增强和系统级优化有何区别？它们各自的优缺点是什么？ 2. 外部反馈和控制在优化感知系统中扮演着怎样的角色？它们如何影响感知系统的性能和稳定性？ 3. 在感知应用领域中，多模型表征相比于单模型和跨模型有何优势？举例说明其在实际应用中的价值。
7.2 感知表征的类型 79
7.2.1 单模型 79
7.2.2 跨模型 80
7.2.3 多模型 81
7.3 优化感知系统 83
7.3.1 模型级增强 83
7.3.2 系统级优化 84
7.3.3 外部反馈和控制 84
7.4 感知应用 84
7.5 总结与讨论 85

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1 Human versus AI Perception/section
本节探讨了人类与人工智能代理的感知能力。人类拥有丰富的感官，包括经典感官和内部感知，使其能够与环境互动。与生物感知不同，人工智能代理依赖工程传感器将环境刺激转化为数字信号。人工智能代理通常处理视觉、听觉和文本数据，但模拟味觉和嗅觉仍有挑战。感知处理效率方面，人类受生物限制，而人工智能系统受计算硬件性能限制。人类自然整合多种感官信息，称为多模感知，而人工智能代理需要设计融合算法。人类感知连续且流畅，而人工智能代理通常依赖离散采样。在空间感知方面，人类能够轻松融合信息，而人工智能代理需要算法处理。总体而言，本节强调了人类和人工智能代理在感知处理中的相似之处和差异，以及人工智能代理面临的挑战和发展方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1 Human versus AI Perception/section/0/text
1. 人类拥有多种感官以及复杂的内部感知，如何影响了其与环境的互动方式？    2. 在感知处理效率和方式上，人工智能代理与人类存在哪些根本的区别和挑战？    3. 人类自然整合多种感官信息，而人工智能代理需要设计融合算法，这种区别对于人工智能代理的发展有何启示？
感知是智能的基础，是人类和人工智能代理与世界互动的接口。尽管人类通常以五种经典感官——视觉、听觉、味觉、嗅觉和触觉来思考感知，现代神经科学确定了更丰富的感官景观。保守地说，人类被描述为拥有大约10种感官；更全面的观点列出了大约21种，而一些研究人员认为存在多达33种独特的感觉模式。除了熟悉的感官之外，人类还拥有复杂的内部感知，如前庭（平衡）、本体感知（意识到身体位置）、热感知（温度）和痛觉（疼痛），使其能够与环境进行微妙的互动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1 Human versus AI Perception/section/1/text
1. 人类感官的广泛范围和精细调节如何影响其参与复杂任务的能力，以及与人工智能代理相比的优势和劣势是什么？    2. 自然界动物展示的多样化感知能力如何启发人工智能代理在模拟味觉、嗅觉以及其他非经典感官方面的发展？
人类的感官对特定的物理信号进行了精细调节：例如，人类视觉可以检测波长约为$380{-}780\mathrm{nm}$之间的电磁波，而听觉可以感知大约$20\mathrm{Hz}$到$20\mathrm{kHz}$的声音频率。这些感觉模式使人类能够轻松地参与复杂任务，如语言交流、物体识别、社交互动和空间导航。此外，人类自然而然地感知随时间持续变化，无缝地整合运动感知和时间意识，这些能力对于协调运动和决策至关重要。自然界的动物展示了更加多样化的感知能力。例如，鸟类和某些海洋生物利用磁感知来利用地球的磁场导航，而鲨鱼和电鳗则利用电感知来感知其他生物发出的电信号——这些是人类所不具备的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1 Human versus AI Perception/section/2/text
1. 人工智能代理如何通过工程传感器将环境刺激转化为数字信号，以实现感知能力？ 2. 在人工智能代理的感知处理中，为什么模拟味觉和嗅觉仍然具有挑战性，以及目前存在哪些技术限制？ 3. 人类感知系统与人工智能代理感知系统在处理味觉和嗅觉数据时存在怎样的差异，以及如何解决这些差异带来的挑战？
与生物感知相反，人工智能代理依赖于设计用于将环境刺激转化为算法可以解释的数字信号的工程传感器。人工智能代理的常见传感器类型包括视觉传感器（摄像头）、听觉传感器（麦克风）、触觉传感器和惯性测量单元。人工智能代理通常擅长处理视觉、听觉和文本数据，利用深度学习和信号处理的进展。然而，某些人类感知能力——尤其是味觉和嗅觉——对机器准确模拟仍然具有挑战性。例如，研究人员开发的先进生物启发嗅觉芯片目前可以区分大约24种不同的气味，这一能力明显低于人类嗅觉系统，后者可以区分超过4,000种不同的气味。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1 Human versus AI Perception/section/3/figure
1. 在图7.1中，哪些类别代表了人类感知系统的组成部分？这些部分之间有何关系？     2. 根据图7.1中的分类示意图，人工智能代理的感知系统与人类感知系统相比存在哪些主要差异？这些差异可能如何影响人工智能代理在感知任务中的表现？
图7.1：感知系统示意分类

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1 Human versus AI Perception/section/4/text
1. 人类感知受到生物限制的影响，而人工智能系统的感知处理效率主要受到什么限制？这种限制对人工智能代理的发展有何影响？    2. 人类的多模感知如何与人工智能代理的感知处理方式有所不同？在实现多模态整合方面，人工智能代理需要面对哪些挑战？   3. 人类将来自多种感官模式的信息自然整合为连贯的体验，这种多模感知如何影响人类与环境的互动方式？人工智能代理如何通过设计融合算法来实现类似的整合？
另一个关键区别在于感知处理效率。人类感知受到生物限制的影响，比如神经传导速度，通常在毫秒级范围内。相反，人工智能系统可以以微秒甚至纳秒的速度处理感觉输入，主要受到计算硬件性能的限制，而不是生物限制。然而，人类感知自然地将来自多种感官模式的信息整合在一起，称为多模感知，轻松地将其融合为连贯的体验。对于人工智能代理来说，实现这种多模态整合需要精心设计的融合算法，明确地将来自不同传感器的输入结合在一起，构建统一的环境表示。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1 Human versus AI Perception/section/5/text
1. 人类感知的连续性和流畅性如何影响其对时间和空间信息的处理方式？与人工智能代理离散采样的方式相比，连续性带来了哪些优势和挑战？    2. 人工智能代理在模拟连续时间和空间信息方面采用了哪些方法？这些方法是否能够完全弥补与人类感知的差异？如何改进人工智能代理的时间和空间感知能力？  3. 人类在空间感知中的多感官整合能力如何影响其对环境的直观理解？相比之下，人工智能代理在空间感知中的挑战主要体现在哪些方面？如何设计算法来提高人工智能代理的空间感知能力？
人类和人工智能代理处理时间和空间信息的方式存在进一步差异。人类感知是连续而流畅的，可以无需明确的时间离散化就能顺畅地体验时间流逝和空间运动。相比之下，人工智能代理通常依赖于对传感器数据的离散采样，使用时间戳或顺序处理来模拟连续性。在空间感知方面，人类能够轻松地将视觉、听觉和前庭信息融合在一起，实现直观的空间定位。而对于人工智能代理来说，空间感知通常涉及算法过程，比如同时定位与地图构建（SLAM）或从视觉数据序列中进行三维场景重建。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1 Human versus AI Perception/section/6/text
1. 人类感知系统和智能代理的感知处理方式有何区别，以及这种区别对于它们与环境互动的影响是什么？ 2. 在智能代理的感知处理中，单模型、跨模型和多模型有何不同，它们各自的优劣势是什么？ 3. 如何解释人类感知系统中的多模感知与智能代理中的融合算法之间的差异，以及这种差异对于信息处理的效率和完整性有何影响？
人类感知系统（如眼睛、耳朵、皮肤等）接收到从外部环境传递过来的物理或化学刺激，并将其转化为神经信号，最终由大脑加工处理以产生对环境的感知。类似地，为了使智能代理能够与环境连接，获取这些感知内容也至关重要。目前，各种传感器主要用于将电信号转换为可处理的数字信号。在本节中，我们根据输入中涉及的感知模态数量以及是否执行统一融合建模操作，区分了单模型、跨模型和多模型。单模型专门处理和分析来自单一模态或输入类型（如文本、图像或音频）的数据，而跨模型通过专用映射机制建立关系并实现不同模态之间的转换，多模型则全面整合和同时处理多个模态，以利用互补信息进行全面理解和决策制定。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.1 Human versus AI Perception/section/7/figure
1. 图7.2中展示的人类和代理之间常见感知类型的比较中，哪些感知类型人类表现更优秀，而哪些感知类型代理表现更出色？     2. 在人类和代理之间常见感知类型的比较中，哪些方面是人工智能代理目前面临的主要挑战？
图7.2：人类和代理之间常见感知类型的比较。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/section
在"感知表征类型"章节中，介绍了智能代理感知输入类型的多样性，包括单模态和多模态输入。文本领域的发展从词袋模型到BERT和GPT3.5等模型，提升了文本理解和生成能力。在视觉方面，ResNet、YOLO和DETR等架构推动了对象检测和分类效率。对于视频输入，ViViT和VideoMAE实现了时空标记和泛化视频特征表示。音频领域的Wav2Vec2和FastSpeech 2等模型提高了语音识别和文本转语音转换效率。此外，智能代理通过仿生感知技术实现了嗅觉、味觉和触觉能力，为更复杂任务提供了新的可能性。跨模态研究方向包括文本-图像模型，如CLIP和ALIGN，以及文本到图像生成和图像到文本生成模型，如DALL-E系列和Stable Diffusion。多模态模型整合多种数据特征，如视觉语言模型(VLM)、音频语言模型(ALM)和视觉语言行为模型(VLA)，提高了模型性能和泛化能力。这些进展丰富了智能代理的感知能力，为其在各种现实场景中的应用提供了更广阔的发展空间。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.1 Unimodal Models/section
本节介绍了智能代理感知输入类型的多样性，包括单模态和多模态输入。文本作为重要的交流方式，经历了从词袋模型到BERT和GPT3.5等模型的演进，提高了文本理解和生成的能力。在视觉领域，ResNet、YOLO和DETR等架构推动了对象检测和分类的效率和准确性。对于视频输入，ViViT和VideoMAE实现了时空标记和泛化视频特征表示。音频方面，Wav2Vec2和FastSpeech 2等模型实现了有效的语音识别和文本转语音转换。此外，智能代理还通过仿生感知技术实现了嗅觉、味觉和触觉能力，为实现更复杂任务提供了新的可能性。这些进展丰富了智能代理的感知能力，为其在各种现实场景中的应用提供了更广阔的发展空间。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.1 Unimodal Models/section/0/text
1. 智能代理在处理文本输入时，从词袋模型到BERT和GPT3.5等模型的演进背后的关键优势是什么？ 2. 在智能代理的感知能力中，文本作为直接输入相比于间接获取文本内容有哪些优势和挑战？ 3. 在智能代理处理文本输入的发展过程中，如何通过自回归模型和技术如LoRA提高了代理在复杂现实场景任务中的感知能力？
当人类置身于环境中时，他们可以聆听美妙的音乐，观赏日出和日落，或在舞台上体验精彩的视听盛宴。这些感知内容可以是单一的图像或音频，也可以是多种感知内容的融合。关于智能代理的感知输入类型，我们将从单模态和多模态输入开始，介绍它们的实现和区别。

文本作为重要的交流方式，承载着丰富的信息、思想、情感和文化。人类通过视觉、听觉和触觉间接获取文本内容，这是人类与环境互动的重要方式之一。但对于智能代理，文本可以直接作为连接环境的桥梁，将文本作为直接输入，并输出响应内容。除了字面意义外，文本还包含丰富的语义信息和情感色彩。在早期，使用词袋模型来计算文本内容并广泛应用于文本分类场景，但无法获得语义表达。BERT使用双向Transformer架构进行语言建模，通过大规模无监督预训练捕获文本的深层语义信息。进一步优化了BERT的训练效率。以GPT3.5为代表的自回归模型开启了语言模型的序幕，进一步统一了文本理解和生成任务，而诸如LoRA之类的技术大大降低了LLM的应用成本，提高了代理在复杂现实场景任务中的感知能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.1 Unimodal Models/section/1/text
1. 计算机视觉架构的发展如何在处理图像空间属性方面取得重大进展，ResNet、YOLO和DETR等架构各自在哪些方面做出了突破性贡献？  2. DINO 1.5是如何通过架构创新、增强的骨干网络和扩展的训练范式，将对象检测的能力扩展到开放场景，并显著改善了开放式检测性能？  3. 图像作为人类与环境互动的重要方式，如何固有地编码了空间信息，计算机视觉架构在处理这些信息方面的发展为什么具有重要意义？
图像是人类与环境互动的另一种重要方式，固有地编码了空间信息，包括形态特征、空间位置、维度关系和物体的运动特性等关键属性。计算机视觉架构的发展在处理这些空间属性方面取得了重大进展。开创性的ResNet架构奠定了深度视觉特征提取的基本原则，而随后的YOLO系列展示了同时确定对象定位和分类的显著效率。DETR的引入引发了范式转变，通过全局上下文推理实现并行预测，有效消除了与非极大值抑制和锚点生成相关的传统计算开销。最近，DINO 1.5通过架构创新、增强的骨干网络和扩展的训练范式，将这些能力扩展到开放场景，显著改善了开放式检测性能，并推进了人工代理在不受限制的环境中的感知泛化能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.1 Unimodal Models/section/2/text
1. ViViT和VideoMAE在处理视频输入时各自采用了怎样的方法，以提高智能代理的感知能力？ 2. 在智能代理应用中，为什么对视频输入的时空标记和泛化视频特征表示如此重要？ 3. 如何评价VideoMAE在自监督预训练学习通用视频特征表示方面的优势，以及其对智能代理在新场景中感知能力的贡献？
视频是连续图像帧的表达，包括时间维度，并通过连续图像帧展示随时间变化的动态信息。智能代理使用视频作为输入，并通过连续帧获取更丰富的感知内容。ViViT从视频中提取时空标记，有效地分解了输入的空间和时间维度。VideoMAE通过自监督预训练学习通用视频特征表示，并具有强大的泛化能力，适用于领域外的数据。它为智能代理在新场景中获得感知能力奠定了坚实基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.1 Unimodal Models/section/3/text
1. 音频在智能代理中的应用中，Wav2Vec2和FastSpeech 2模型分别通过怎样的方式提高了语音识别和文本转语音转换的效果？  2. 如何描述Seamless模型在多源语言到目标语言的同步语音/文本翻译中所采用的关键技术，以及它是如何保持人类语音风格的？  3. 在智能代理的音频感知领域，如何利用1/100标记数据量实现了语音识别的有效性？
除了文本和视觉之外，人类与环境互动的另一重要方式是通过音频。音频不仅包含直接的文本内容，还包含说话者的语调和情感。Wav2Vec2通过量化联合学习的潜在表示来定义对比任务，用1/100标记数据量实现了语音识别的有效性。FastSpeech 2直接引入声音变化信息（音高、能量、持续时间等），并使用真实目标训练模型，实现更逼真的文本转语音转换。Seamless通过流式生成低延迟目标翻译，并使用高效的单调多头注意力机制，同时保持人类语音风格，实现了多源语言到目标语言的同步语音/文本翻译。基于这些手段，智能代理可以实现听和说的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.1 Unimodal Models/section/4/text
1. 智能代理在感知能力方面如何借鉴人类感知系统的多样性？这种多样性对于智能代理在各种现实场景中的应用有何意义？    2. 除了传统的视觉、文本和音频输入，智能代理如何通过仿生感知技术实现嗅觉、味觉和触觉能力？这种多模感知如何为实现更复杂任务提供新的可能性？  3. 这些具有单模感知能力的传感器和传感器组合如何在智能代理中被整合和应用，以实现更复杂的任务目标？
目前，大多数智能代理的研究集中在上述常见感知输入类型上。然而，就像人类有20多种感知方式一样，智能代理也通过其他传感器在实现相应感知能力方面取得了进展。香港科技大学研发的仿生嗅觉芯片整合了纳米管传感器阵列在纳米多孔基板上，每个芯片上有多达10,000个可独立寻址的气体传感器，类似于人类和其他动物嗅觉系统的配置，能够准确区分混合气体和24种不同气味。在味觉方面，同济大学结合荧光和磷光信号开发了具有多模光响应的智能味觉传感器，可以有效识别鲜味、酸味和苦味。为了实现类人感知和抓握能力，纽约大学推出了低成本磁性触觉传感器AnySkin，可以快速组装和更换。甚至在疼痛感知方面，中国科学院利用液态金属颗粒膜的独特电性能在“受伤”（机械划伤）时模拟“伤口”的感知和定位。一些其他作品，包括HuggingGPT，LLaVA-Plus和ViperGPT，在框架内整合这些单模感知能力，根据任务需求选择并应用它们，实现更复杂任务的目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.2 Cross-modal Models/section
文本-图像跨模态模型是近年来取得显著进展的研究方向，涉及跨模态对齐和检索、文本到图像生成以及图像到文本生成。在跨模态研究中，CLIP和ALIGN等模型采用对比学习和循环一致性损失来实现文本和视觉表示的对齐，提高了跨模态检索的效果。文本到图像生成方面，DALL-E系列和Stable Diffusion模型实现了根据文本描述合成高质量图像的目标，包括细粒度语义控制和开放域文本合成。至于图像到文本生成，BLIP和BLIP-2模型通过桥接模块增强了视觉-语言模型集成，支持图像字幕和问题回答等任务。此外，文本-视频和文本-音频跨模态模型也取得了重要进展，包括VideoCLIP、Make-A-Video、AudioCLIP和VATT等模型，增强了跨模态检索、生成和转换能力。在其他领域中，如3D形状生成和医学影像，CLIP-Forge、Point-E和MoCoCLIP等模型提供了创新的解决方案，拓展了跨模态建模的应用范围。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.2 Cross-modal Models/section/0/text
1. 跨模态研究中的对比学习和循环一致性损失如何帮助实现文本和视觉表示的对齐，以及对提高跨模态检索效果的影响是怎样的？  2. CLIP、ALIGN和CyCLIP等模型在实现跨模态对齐和检索方面有何不同的方法和优势？  3. 跨模态研究中，如何利用对比学习和循环一致性损失来提高跨模态对齐的鲁棒性，并提升检索任务的可靠性？
文本-图像跨模态模型在近年来取得了显著进展，整合了文本和图像，促进了两种模态之间的改进对齐、检索和生成。这些模型可以根据它们的主要目标进行分类，包括跨模态对齐和检索、文本到图像生成以及图像到文本生成。

跨模态研究的一个主要焦点是文本和图像的对齐和检索。OpenAI于2021年推出的CLIP [51]采用对比学习来对齐文本和视觉表示，实现了零-shot跨模态检索和分类。类似地，Google在同一年开发的ALIGN [501]利用大规模嘈杂网络数据优化文本-图像嵌入对齐。2022年，CyCLIP [562]引入循环一致性损失，进一步增强了跨模态对齐的鲁棒性，提高了检索任务的可靠性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.2 Cross-modal Models/section/1/text
1. 文本-图像跨模态模型中的对比学习和循环一致性损失是如何帮助实现文本和视觉表示的对齐的？    2. DALL-E系列和Stable Diffusion模型在文本到图像生成领域的贡献分别是什么，它们采用的方法有何特点？  3. VideoCLIP、Make-A-Video和Phenaki等模型是如何在文本-视频跨模态研究中提高视频-文本关联、视频合成和跨模态检索能力的？
另一个取得重大进展的主要领域涉及文本到图像生成，其中模型旨在根据文本描述合成高质量图像。OpenAI的DALL-E系列[563, 564, 502]，跨越了从2021年到2023年，在这一领域做出了实质性贡献，其中DALL·E3提供了对生成图像的细粒度语义控制。StabilityAI于2022年推出的Stable Diffusion[565]采用基于扩散的生成方法，支持开放域文本到图像合成和跨模态编辑。

第三个重要的研究方向是图像到文本生成，其中模型旨在根据图像输入生成高质量的文本描述。Salesforce在2022年到2023年间推出的典型代表作品是BLIP[566]和BLIP-2[567]模型，利用轻量级桥接模块增强视觉-语言模型集成，实现诸如图像字幕和问题回答等任务。

文本-视频方面的关键研究涉及视频文本对齐、生成和检索。VideoCLIP[504]采用视频编码器（通常基于时间卷积或变压器结构）从视频帧中提取序列特征。随后，这些特征与语言编码器生成的文本表示进行对齐，促进稳健的视频-文本关联。在文本到视频生成领域，Meta的Make-A-Video模型[06]利用基于扩散的技术扩展了时空维度，从文本描述中实现高质量视频合成。此外，Google的Phenaki[505]解决了生成长、时间连贯视频序列的挑战，通过跨模态学习在视频合成方面取得了显著进展。DeepMind的Frozen in Time[568]采用对比学习进行视频-文本匹配，从而实现高效的跨模态检索。这种方法增强了根据文本查询搜索和检索相关视频片段的能力，进一步提高了视觉和语言理解的整合。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.2 Cross-modal Models/section/2/text
1. AudioCLIP如何将音频整合到跨模态检索框架中，并如何通过多任务学习实现图像、文本和音频的统一表示？ 2. VATT采用了怎样的基于Transformer的架构来处理视频、音频和文本，并如何实现这些模态的融合以促进跨模态检索和多任务学习？ 3. 在文本-音频跨模态模型中，为什么将音频作为额外模态有助于增强跨模态检索和交互的能力？
文本-音频跨模态模型在连接文本和音频方面取得了显著进展，改进了相关任务，如模态表示、生成和转换，并增强了单一模态下的感知能力。

2021年推出的AudioCLIP[509]将CLIP框架扩展到音频领域，实现了跨音频、文本和图像的三模态检索。通过将音频作为额外模态，AudioCLIP利用多任务学习将图像、文本和音频表示统一到共享的嵌入空间中。这一进展增强了跨模态检索和交互的能力。类似地，VATT[508]采用统一的基于Transformer的架构，通过独立的编码分支处理视频、音频和文本。这些分支随后融合到共享的多模态空间中，促进了跨模态检索和多任务学习等任务。这种设计使得在各种多模态场景下具有更大的适应性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.2 Cross-modal Models/section/3/text
1. 在文本到音频生成领域，Meta的AudioGen模型如何展示了人工智能在基于语言输入生成高保真音频方面的能力？这种能力如何扩大了在媒体、娱乐和无障碍领域的应用？  2. 微软的SpeechT模型如何统一了语音和文本生成，并如何通过共享架构支持语音合成和识别？SpeechT对于实现语音和文本处理的无缝集成有何帮助，特别是在哪些应用方面发挥作用？  3. CLIP-Forge和Point-E这两种模型分别采用了怎样的方法从文本描述生成3D形状，它们是如何利用对比语言-图像预训练的能力来合成高质量的3D物体和点云的？这种跨模态建模方法如何弥合了文本描述和3D几何之间的差距，并在3D内容创建方面带来了哪些优势？
对于文本到音频生成，Meta在2023年推出了AudioGen[569]，该模型能够根据文本描述直接合成环境声音和音乐片段等音频。这一模型展示了人工智能在基于语言输入生成高保真音频方面不断增强的能力，扩大了在媒体、娱乐和无障碍领域的应用。

此外，在语音到文本和文本到语音转换领域，微软开发了SpeechT[570]。该模型统一了语音和文本生成，在单一框架内支持语音合成和识别。通过利用这些双重功能的共享架构，SpeechT有助于实现语音和文本处理的无缝集成，从而增强了自动转录、语音助手和辅助工具等应用。

其他情景和领域中，跨模态建模也发挥着重要作用。

CLIP-Forge[510]提出了一种从文本描述生成3D形状的新方法。通过利用对比语言-图像预训练（CLIP）的能力，这种方法能够在自然语言输入的条件下合成高质量的3D物体，弥合了文本和3D几何之间的差距。Point-E[51]扩展了这一概念，通过从文本描述生成3D点云。与传统的3D重建技术不同，Point-E专注于点云表示，促进了高效可扩展的3D内容创建，同时保持对文本提示的高保真度。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.2 Cross-modal Models/section/4/text
1. MoCoCLIP如何结合CLIP与动量对比（MoCo）来增强深度学习模型在医学影像应用中的泛化能力？ 2. 在医学影像领域，有哪些挑战是MoCoCLIP所解决的，这些挑战如何影响深度学习模型的性能？ 3. MoCoCLIP提出的增强零样本学习能力的方法对于医学影像应用有哪些潜在的实际应用场景和优势？
在医学影像领域，MoCoCLIP[571]提出了一种增强零样本学习能力的方法。通过将CLIP与动量对比（MoCo）相结合，该方法提高了深度学习模型在医学影像应用中的泛化能力，解决了有限标注数据和领域适应性所带来的挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section
多模态模型通过对比学习和其他方法在模态之间进行对齐和映射，整合多种数据的特征以提高模型性能。视觉语言模型(VLM)结合图像和文本学习，展现出出色的多模态聊天能力。音频语言模型(ALM)利用音频和文本构建模型，实现跨模态语音对话。视觉语言行为模型(VLA)整合视觉、语言和动作，通过不同编码器和模型结合提高泛化能力。高性能端侧模型如TinyGPT-V和Megrez-3B-Omni提升多模态识别效果。工作还涉及音频视觉语言模型(AVLM)统一多模态模型，实现任意模态输入输出转换和三维物体描述。NeuralFels技术结合视觉和触觉建模未知物体，提高对未知物体操作准确性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section/0/text
1. 跨模态模型如何通过对比学习和其他方法在模态之间进行对齐和映射，实现信息的互补和转换，从而提高整体模型性能？  2. 视觉语言模型(VLM)在多模态学习中的作用是如何定义的？它是如何利用图像和文本学习，并展现出出色的多模态聊天能力的？  3. 多模态模型在训练过程中使用的不同策略和技术（如动态编码策略、MoE模型等）是如何帮助提升模型的性能和泛化能力的？
上述跨模态模型主要通过对比学习和其他方法在模态之间进行对齐和映射，以实现信息的互补和转换。此外，多模态模型的工作重点是如何整合多种数据的特征（如视觉、文本、音频等）以提高整体模型的性能。

视觉语言模型（VLM）被广泛定义为可以从图像（或视频）和文本中学习的多模态模型。人类生活在充满多模态信息的世界中。视觉信息（如图像和视频）和语言信息（如文本）经常需要结合起来才能充分表达含义。智能代理也是如此。LLaVA首次尝试使用gpt-4生成多模态语言图像指令数据集。通过端到端训练，获得了一个大型多模态模型，并展示了出色的多模态聊天能力。LLaVA-NeXT利用动态高分辨率和混合数据展示了惊人的零-shot能力，即使在纯英文模态数据中，计算/训练数据成本也比其他方法小0-1000倍。Emu2改变了传统的使用图像标记器将图像转换为离散标记的方式，直接使用图像编码器将图像转换为连续的嵌入，并提供给Transformer，增强了多模态上下文学习能力。MiniGPT-v2在训练过程中为各种任务使用了独特的标识符。这些标识符帮助模型更有效地区分任务指令，增强了模型对每个任务的学习效率。Qwen2-VL、DeepSeek-VL2在视觉组件上使用动态编码策略，旨在处理具有不同分辨率的图像并生成更高效和准确的视觉表示。同时，DeepSeek-VL2还使用了带有多头潜在注意机制的MoE模型，将关键-值缓存压缩为潜在向量以实现高效的推理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section/1/text
1. Video-ChatGPT如何通过直接使用视频进行训练，并结合视觉编码器与LLM，以实现对视频数据中时间动态和帧间一致性关系的捕捉？    2. Chat-UniVi是如何利用动态视觉标记整合图像和视频，并结合多尺度表示来理解高级语义概念和低级视觉细节的？  3. SlowFast-LLaVA是如何通过双流SlowFast设计，在不需要额外微调视频数据的情况下，有效捕捉视频中的详细空间语义和长期时间上下文，实现与微调方法相同甚至更好的结果？
以往的工作主要是利用图像融合文本进行训练。Video-ChatGPT扩展了输入到视频，并直接使用视频自适应视觉编码器与LLM结合进行训练，以捕捉视频数据中的时间动态和帧间一致性关系，从而使关于视频内容的开放式对话以连贯的方式进行。为了解决图像和视频的统一标记化的缺乏，Video-LLaVA将图像和视频编码的视觉表示统一到语言特征空间中，使二者相互加强。类似地，Chat-UniVi采用一组动态视觉标记来整合图像和视频，同时利用多尺度表示，使模型能够把握高级语义概念和低级视觉细节。Youku-mPLUG在特定场景进行了深入研究。基于优酷视频分享平台中高质量的中文视频文本对，增强了对整体和详细视觉语义的理解，并识别场景文本。与之前需要训练的方法不同，SlowFast-LLaVA通过双流SlowFast设计，在不需要额外微调视频数据的情况下有效捕捉视频中的详细空间语义和长期时间上下文，达到了与微调方法相同甚至更好的结果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section/2/text
1. 高性能端侧模型在多模态识别中的优势体现在哪些方面？如何通过减少参数和增强计算能力来提高模型性能？ 2. TinyGPT-V和Megrez-3B-Omni相较于其他模型，是如何实现在端侧部署AI模型时提供更高的多模态识别效果和推理性能的？ 3. 在智能终端设备上部署高性能端侧模型可能面临的挑战有哪些？如何通过模型设计和优化来应对这些挑战？
随着大型模型参数逐渐减少和端侧计算能力增强，高性能端侧模型正逐渐受到关注。智能终端设备如手机和个人电脑对图像视觉处理有着强烈需求，这对在端侧部署AI模型提出了更高的多模态识别效果和推理性能要求。TinyGPT-V建立在Phi-2小型骨干和BLIP-2的基础上，仅需8G视频内存或CPU进行推理，解决了LLaVA和MiniGPT-4的计算效率问题。MiniCPM-V主要为长且复杂的图像提供强大的OCR能力，并具有较低的错觉率，提供可靠的感知输出。Megrez-3B-Omni通过软硬件协同优化，确保所有结构参数与主流硬件高度兼容，推理速度比同等精度模型快高达300%，提高了其适应不同端侧硬件的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section/3/text
1. GUI相关工作如OmniParser和GUICourse如何通过跨平台GUI基础语料库提升对GUI截图的理解和丰富GUI组件的交互知识？ 2. 在多模态模型中，如何可以将视觉、语言和动作整合在一起，以提高泛化能力和多模态识别效果？ 3. 对比学习在自动执行任务和多模态模型中的应用有何优势和局限性？
类似地，还有更多与图形用户界面(GUI)相关的工作集中于在手机和个人电脑上自动执行任务。OmniParser利用流行的网页和图标描述数据集进行微调，显著增强了对截屏中图标的检测和功能语义表达能力。GUI课程(GUICourse)和OS-ATLAS也构建了跨平台GUI基础语料库，显著提升了对GUI截图的理解，并丰富了GUI组件的交互知识。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section/4/text
1. VLA模型中不同阶段的视觉和语言编码器选择的演进如何影响了模型的性能和泛化能力？ 2. 在多模态融合中，不同模型如何利用多模态提示和多模态结合来支持更复杂的任务？ 3. 如何利用PerAct创新性地将3D点云作为视觉输入，通过Perceiver IO处理多视角信息，为机器人操作提供更丰富的空间感知？
视觉语言行为模型(Vision Language Action Model，VLA)将视觉和语言作为输入，并生成机器人动作作为输出，代表了体现智能领域中的重要研究方向。VLA模型中视觉和语言编码器的选择经历了多样化的发展，从早期的CNNs发展到Transformer架构，并进一步整合了3D视觉和大型语言模型。早期模型如CLIPort使用ResNet处理视觉输入，并结合语言嵌入生成动作，为多模态融合奠定了基础。RT-1引入了Transformer架构，采用EfficientNet作为视觉编码器，采用USE作为语言编码器，并通过FiLM机制融合视觉和语言信息，显著增强了模型的泛化能力。VIMA进一步采用了多模态提示，将ViT视觉编码器和T5语言模型结合起来，支持更复杂的任务。PerAct创新性地将3D点云作为视觉输入，并通过Perceiver IO处理多视角信息，为机器人操作提供更丰富的空间感知。Diffusion Policy结合了ResNet视觉编码器和Transformer语言模型，通过扩散模型生成动作，以提高动作生成的多样性和准确性。SayCan将PaLM语言模型与视觉输入整合，使用CLIP视觉编码器进行任务分解。PaLM-E结合了ViT视觉编码器和PaLM语言模型，通过文本规划指导低层次动作执行。MultiPLY进一步将3D信息整合到LLMs中，将EVA视觉编码器和LLaMA语言模型结合起来，为复杂任务提供更全面的规划能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section/5/text
1. ALM如何利用音频和文本构建多模态模型，以实现跨模态语音对话能力？该方法相较于以往的离散音频标记有何优势和创新之处？    2. 在音频处理任务中，为什么LauraGPT提出了结合音频的连续和离散特征的新型数据表示？这种数据表示如何通过监督多任务学习展现出优异性能？  3. UniAudio 1.5是如何利用文本词汇中的单词或子词作为音频标记，实现无需微调的跨模态输出的？这种方法在多模态输出中有哪些优势和应用前景？
音频语言模型(Audio Language Model，ALM)利用音频和文本构建多模态模型。Speechgpt构建了大规模跨模态语音指令数据集SpeechInstruct，并训练了离散语音表示，实现了超出预期的跨模态语音对话能力。与以往采样离散音频标记来表示输入和输出音频不同，LauraGPT提出了一种结合音频的连续和离散特征的新型数据表示，并通过监督多任务学习在各种音频任务上展现出优异性能。将音频数据转换为嵌入表示，然后微调指令，通过自然语言指令在各种语音处理任务上取得出色表现。为了降低微调训练成本，AudioFlamingo通过基于音频语言模型的上下文学习和检索快速增强适应未见任务的能力。UniAudio 1.5使用文本词汇中的单词或子词作为音频标记，通过少量样本学习这些音频表示，并实现了无需微调的跨模态输出。为了使输出更加逼真符合人类期望，Qwen2-Audio引入了DPO训练方法以实现人类偏好对齐。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section/6/text
1. 如何利用音频、视觉和文本来统一多模态模型，以解决通用人工智能中任务和模态多样性的挑战？   2. 在多模态模型中，闭源工作如何在文本、视觉和音频等模态之间取得出色的能力？   3. UniVAL是如何通过任务平衡和多模态课程学习训练一个仅有约0.25B参数的模型，并保持泛化能力的？
音频视觉语言模型（Audio Vision Language Model，AVLM）利用音频、视觉和文本来统一多模态模型。先前，我们介绍了一些利用两种模态信息构建多模态模型的工作。在追求通用人工智能（AGI）的过程中，实现这一目标的障碍在于任务和模态的多样性和异质性。一个合适的方法是在统一框架内支持更多的模态能力。一些闭源工作[586,587]已经在文本、视觉和音频等模态之间取得了出色的能力。ImageBind[588]实现了跨六种不同模态（图像、文本、音频、深度、热像和IMU数据）的联合嵌入。Panda-GPT[535]结合了ImageBind的多模态编码器和Vicuna[589]，展示了除图像和文本外的零样本跨模态性能。类似的工作包括[539,539,536]，通过编码视觉、音频和文本信息实现了对齐和训练。多模态模型通常需要更多的资源进行训练，UniVAL [538]基于任务平衡和多模态课程学习训练了一个仅有约0.25B参数的模型，并使用权重插值来合并多模态模型，在分布外保持泛化能力。NExT-GPT [542]将语言模型连接到多模态适配器和不同的扩散解码器，仅训练了某些投影层的少量参数（1%）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section/7/text
1. Unified-IO 2如何实现了多模态模型中不同模态输入的标记化和共享语义空间处理，以提高多模态输入输出转换的效果？ 2. AnyGPT是如何利用离散表示统一处理各种模态输入，从而构建了大规模任意到任意多模态指令数据集？ 3. Modaverse是如何通过将LLM的输出与生成模型的输入对齐来解决先前工作中存在的潜在特征对齐问题，从而简化多模态模型的复杂性？
其他工作[543,590,544,545]已经实现了任意模态之间的输入输出转换。Unified-IO 2[543]是第一个能够理解和生成图像、文本、音频和动作的自回归多模态模型。它将不同的模态输入标记化为共享的语义空间，并使用编码器-解码器模型进行处理。AnyGPT[590]构建了第一个大规模任意到任意多模态指令数据集，使用离散表示来统一处理各种模态输入。Modaverse[545]直接将LLM的输出与生成模型的输入对齐，以解决先前工作严重依赖文本和非文本特征的潜在空间对齐问题，避免了与潜在特征对齐相关的复杂性。CoDi-2[544]在主题为基础的图像生成、视觉转换和音频编辑等任务中胜过了早期的领域特定模型。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section/8/text
1. 三维世界相比二维世界在描述物体时具有哪些优势，以及如何利用PointLLM模型实现出色的三维物体描述和分类能力？  2. 为什么在处理三维信息时会带来更大的训练成本？MiniGPT-3D是如何通过2D-LLM的二维先验来降低训练成本的？  3. LLaVA-3D是如何将2D CLIP补丁特征与三维空间中对应位置相连，实现二维和三维视觉语言命令的联合调整，并提升收敛速度？
人类对二维世界的探索比对三维世界的探索更多，但三维可以更准确地描述物体的形状和纹理信息，并提供更丰富的感知信息。PointLLM使用点云编码器来表达几何和外观特征，并整合语言特征进行复杂点-文本指令的两阶段训练，实现出色的三维物体描述和分类能力。由于三维包含比二维更丰富的信息，它也带来更大的训练成本。在这里降低了训练成本，而MiniGPT-3D利用2D-LLM的二维先验将三维点云与LLM对齐。模态对齐以级联方式进行，查询专家模块混合以高效自适应地聚合特征，实现了小参数更新的高效训练。LLaVA-3D将2D CLIP补丁特征与其在三维空间中的对应位置相连，将3D补丁整合到2D LMM中，并使用联合的二维和三维视觉语言命令调整，实现了收敛速度提升3.5倍。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.2 Types of Perception Representation/7.2.3 Multimodal Models/section/9/text
1. 如何通过NeuralFels技术将视觉和触觉结合起来，实现对3D中未知物体的建模？ 2. Meta的NeuralFels技术是如何提高智能代理对未知物体操作的准确性的？ 3. 在智能代理感知和操作未知物体的过程中，NeuralFels技术相比其他方法有哪些优势？
为了使智能代理能够准确感知和操作未知物体，Meta[592]开发了NeuralFels技术，该技术将视觉和触觉结合起来，不断对3D中的未知物体进行建模，更准确地估计手持操作中物体的姿势和形状，并将对未知物体操作的准确性提高了94%。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/section
优化感知系统是关键挑战，因感知误差影响基于LLM的代理的可靠性。模型层级增强通过微调和提示工程提高感知准确性，结合检索机制降低幻觉可能性。系统级优化强调预期-重新评估机制、多代理协作和代理专业化，提升系统鲁棒性和效率。外部反馈和控制利用LossAgents和内容调解优化LLMs，整合人类反馈确保代理行为符合期望，为构建安全、可靠的人工智能系统提供关键支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/section/0/text
1. 如何利用模型层级增强和检索机制相结合的方式来提高感知系统的准确性和降低幻觉可能性？ 2. 为什么系统级优化中的预期-重新评估机制、多代理协作和代理专业化可以提升系统的鲁棒性和效率？ 3. 外部反馈和控制如何利用LossAgents和内容调解来优化LLMs，以确保代理行为符合期望，从而支持构建安全、可靠的人工智能系统？
感知误差，包括不准确、误解和“幻觉”（生成虚假信息），对基于LLM的代理的可靠性和有效性构成重大挑战。因此，优化感知需要通过跨模型、系统和外部层面采用各种策略来最小化这些错误。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/7.3.1 Model-Level Enhancements/section
在模型层级增强方面，微调预训练的LLMs在特定领域数据上表现出更准确的感知和信息解释能力。技术如低秩适应（LoRA）可以提高微调效率，同时避免增加模型复杂度。提示工程对于指导LLMs生成准确且符合期望目标的输出至关重要，不同类型的提示（系统提示、历史提示、定制提示）可显著减少误解和错误。此外，通过检索机制结合外部知识源，LLMs能基于事实信息作出回应，提高感知信息的准确性，降低幻觉可能性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/7.3.1 Model-Level Enhancements/section/0/text
1. 微调预训练的LLMs在特定领域数据上表现更准确的感知和信息解释能力的关键在于哪些方面？   2. 低秩适应（LoRA）技术如何提高微调效率并避免增加模型复杂度，从而实现更好的性能？  3. 如何利用不同类型的提示（系统提示、历史提示、定制提示）来减少LLMs在特定领域数据上的误解和错误？
微调。在特定领域数据上微调预训练的LLMs显著提高了它们准确感知和解释相关信息的能力。例如，对于特定地标进行微调的模型，如LLaVA，已被证明可以提高它们的识别准确性，特别是在城市导航任务中[513,593]。此外，诸如低秩适应（LoRA）之类的技术可以实现更高效的微调，避免模型复杂度的显著增加，同时仍然提高性能[109,594]。一些LLM工作结合传统视觉也被广泛使用。在Llama-Adapter[596]架构的基础上与YOLOS[595]集成显著提高了检测和定位能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/7.3.1 Model-Level Enhancements/section/1/text
1. 提示工程在指导LLMs生成准确输出方面的作用是什么，以及为什么不同类型的提示（系统提示、历史提示、定制提示）可以显著减少误解和错误？  2. 如何通过提示工程的设计来确保LLMs生成的输出既准确又符合期望目标？系统提示、历史提示和定制提示分别如何提供清晰的指导和上下文信息？  3. 在提高LLMs感知信息准确性和降低幻觉可能性方面，如何利用检索机制结合外部知识源进行提示工程？
提示工程。设计有效提示对于确保LLMs生成准确且符合期望目标的输出至关重要。通过提供清晰的指导、上下文信息和特定的格式要求，提示工程可以最大程度地减少误解和幻觉[597]。系统提示定义了代理的角色，历史提示提供了过去互动的上下文，定制提示可确保输出的一致性，已被证明可以显著减少错误[597]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/7.3.1 Model-Level Enhancements/section/2/text
1. 如何通过检索机制将LLMs与外部知识源相结合，从而降低幻觉可能性，提高感知信息的准确性？    2. 在检索增强生成中，为什么说不同类型的提示（系统提示、历史提示、定制提示）能显著减少误解和错误，这与LLMs的输出准确性有何关联？  3. 在模型层级增强方面，为什么说技术如低秩适应（LoRA）可以提高微调效率，同时避免增加模型复杂度？
检索增强生成。通过检索机制将LLMs与外部知识源相结合，有助于将它们的回应基于事实信息，降低幻觉的可能性，提高感知信息的准确性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/7.3.2 System-Level Optimizations/section
在系统级优化方面，本章深入研究了三个关键主题。首先，通过预期-重新评估机制，代理在面对信息不完整或模糊情况时能够增强鲁棒性，比如在导航任务中预测目标方向并及时重新评估。其次，多代理协作在系统中起着重要作用，通过结构化沟通和协作促进信息共享和集体感知，不同的通信拓扑结构提供了不同的效率和鲁棒性权衡。最后，代理专业化通过为每个代理分配特定角色和能力实现感知分工，从而增强整体感知准确性和效率。这些研究结果为构建安全、可靠且有益的人工智能系统提供了重要的理论基础和实践指导。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/7.3.2 System-Level Optimizations/section/0/text
1. 预期-重新评估机制如何在代理面临信息不完整或模糊情况下增强鲁棒性？在导航任务中，代理如何利用该机制来提高目标方向的预测准确性？  2. 多代理系统中的结构化沟通和协作如何促进信息共享、纠错和共识建立？不同通信拓扑结构的选择如何影响系统的效率和鲁棒性权衡？  3. InsightSee和HEV分别如何利用多代理框架和合作感知来增强视觉信息处理和决策能力？这种方法对于构建安全、可靠且有益的人工智能系统有何启示？
预期-重新评估机制。在代理面临信息不完整或模糊的情况下，预期-重新评估机制可以增强鲁棒性。例如，在导航任务中，代理可以基于历史数据预期目标方向，并在新信息可用时重新评估推断。

多代理协作。在多代理系统中，代理之间的结构化沟通和协作可以促进信息共享、纠错和共识建立，从而实现对环境的更准确的集体感知。不同的通信拓扑结构，如全连接、集中式和分层结构，在效率和鲁棒性方面提供不同的权衡。InsightSee通过一个包含描述、推理和决策的多代理框架，对视觉信息进行精炼，有效增强了视觉信息处理能力。类似地，HEV整合了多个代理的全局视角信息，并通过合作感知赋予RL代理全局推理能力，从而增强了它们的决策能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/7.3.2 System-Level Optimizations/section/1/text
1. 代理专业化如何通过为每个代理分配特定角色和能力实现感知分工，从而增强整体感知准确性和效率？ 2. 在多代理系统中，为何需要通过代理专业化来增强整体感知的准确性和效率？ 3. 代理专业化如何与多代理协作结合，促进信息共享和集体感知，以构建安全、可靠且有益的人工智能系统？
代理专业化。在多代理系统中为各个个体代理分配不同的角色和能力，可以实现感知分工，使每个代理专注于环境或任务的特定方面。这可以增强感知的整体准确性和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/7.3.3 External Feedback and Control/section
在"外部反馈和控制"这一章节中，介绍了利用LossAgents优化LLMs的方法，通过动态调整损失函数权重来适应复杂、潜在不可微分目标。同时，整合人类反馈和监督有助于指导代理学习，确保其与人类价值观和期望一致。此外，内容调解在呈现LLM输出前进行过滤和完善，以防止意外或有害行为，确保符合用户期望和安全准则。这些方法外部化了优化目标，使LLM能够感知并适应复杂标准，为构建安全、可靠和有益的人工智能系统提供了关键支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.3 Optimizing Perception Systems/7.3.3 External Feedback and Control/section/0/text
1. LossAgents如何通过动态调整损失函数权重来适应复杂、潜在不可微分目标，从而优化LLMs的训练过程？ 2. 为什么整合人类反馈和监督对于指导代理学习过程、纠正错误以及确保与人类价值观和期望一致是至关重要的？ 3. 内容调解在呈现LLM输出前起到了怎样的作用？它如何帮助防止意外或有害行为，确保输出符合用户期望和安全准则？
LossAgents用于优化。利用LLMs作为LossAgents，在训练过程中允许动态调整损失函数权重[604]。这使得基于复杂、潜在不可微分目标的图像处理模型得以优化，包括来自人类反馈和专门模型评估。这种方法本质上是外部化了优化目标，使LLM能够“感知”并适应复杂标准[605]。

人在环环系统。整合人类反馈和监督可以帮助纠正错误，指导代理的学习过程，并确保与人类价值观和期望保持一致[43]。

内容和输出调解。在向用户呈现LLM输出之前，内容调解会过滤和完善这些输出。这有助于防止意外或有害行为，确保与用户期望和安全准则保持一致[606]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.4 Perception Applications/section
智能代理的效率受到模型架构、硬件基础设施和量化优化方法的影响。模型参数的指数级增长导致处理延迟增加，硬件性能变化显著，如NVIDIA H100相比A100提高了50%的标记处理吞吐量。智能代理已广泛应用于个人辅助系统、游戏环境和机器人流程自动化，主要以视觉感知为输入方式。在程序生成环境中，STEVE和Steve-Eye通过视觉信息处理实现了性能提升和环境理解的改进。在创意内容生成方面，AssistEditor和Audio-Agent展示了多智能体协作和跨模态集成的能力。移动和桌面平台的进步如ExACT和SPA-Bench在探索性学习和移动评估方面取得成功。个人AI助手的语音交互和情感音律整合提高了用户参与度。触觉和力反馈机制在具身智能应用中扮演重要角色，增强了操作精度。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.4 Perception Applications/section/0/text
1. 智能代理中不同模型架构的维度对运行效率的影响是如何体现的？如何解决模型参数指数级增长导致的处理延迟增加问题？ 2. 在硬件基础设施规格方面，NVIDIA H100相比A100提高50%的标记处理吞吐量如何影响智能代理的性能？如何评估硬件性能对智能代理效率的贡献？ 3. 量化优化方法在提升智能代理运行效率方面有何作用？如何利用量化优化方法来应对模型参数增长和硬件性能变化所带来的挑战？
智能代理的运行效率主要受到三个关键因素的影响：模型架构维度、硬件基础设施规格和量化优化方法。从Bert-Base的110M到GPT-3的1750亿，再到Llama 3的前所未有的4050亿，模型参数的指数级增长导致处理延迟从毫秒级增加到数百毫秒。硬件性能的变化尤为引人注目；通过GPT-3的实证证据表明，与A100相比，NVIDIA H100的标记处理吞吐量提高了50%，而RTX 4090的处理能力大约是其两倍。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.4 Perception Applications/section/1/text
1. 当代智能代理在多媒体内容生成方面如何利用视觉感知作为主要输入方式，以提高性能和效率？  2. STEVE和Steve-Eye在程序生成环境中是如何通过视觉信息处理实现性能提升和环境理解改进的？  3. 在智能代理的发展中，如何通过端到端多模态训练整合视觉-文本输入处理，以解决环境理解延迟的问题？
当代智能代理已经渗透到各种领域，包括个人辅助系统、游戏环境、机器人流程自动化（RPA）和多媒体内容生成，主要利用视觉感知作为其主要输入方式。在像Minecraft这样的程序生成环境中，STEVE展示了显著的性能提升，通过视觉信息处理实现了科技树进展加速$1.5$倍和方块搜索效率提高$2.5$倍。Steve-Eye通过端到端多模态训练推进了这一范式，通过整合视觉-文本输入处理解决了环境理解延迟的问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.4 Perception Applications/section/2/text
1. AssistEditor和Audio-Agent在创意内容生成中展示了多智能体协作和跨模态集成的能力，这种复杂的协作方式如何促进了专业视频编辑和全面的音频处理能力？  2. 移动和桌面平台在智能体应用方面取得了显著进展，ExACT和SPA-Bench分别在哪些方面取得了成功，并如何通过不同的方法提高了成功率？  3. AgentStore是如何通过增强视觉和可访问性树处理来显著提高OsWorld PC基准性能的，这种方法有哪些优势和局限性？
在创意内容生成领域，AssistEditor展示了复杂的多智能体协作，通过基于风格驱动的内容理解促进专业视频编辑。类似地，Audio-Agent实现了文本/视觉输入与音频输出之间的跨模态集成，实现了全面的音频处理能力。

移动和桌面平台在智能体应用方面取得了显著进展。ExACT在VisualWebArena中建立了新的最先进基准，在带有标题和掩模集成的基于截图的探索性学习中实现了$33.7\%$的成功率。SPA-Bench引入了一个全面的移动评估框架，真实地复制了现实世界的复杂性。M3A通过多模态输入处理在SPA-Bench中表现出色，成功率达到$64.0\%$。AgentStore通过增强视觉和可访问性树处理，显著提高了OsWorld PC基准性能，达到$23.85\%$。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.4 Perception Applications/section/3/text
1. 个人AI助手中的语音交互如何显著降低了交互摩擦，并提高了运营效率？ 2. 情感音律在语音交互中的整合如何证明增加了用户参与度和留存率？ 3. 触觉和力反馈机制在具身智能应用中的重要性体现在哪些方面？
个人AI助手中的语音交互能力[619,586]显著降低了交互摩擦，同时提高了运营效率。在语音交互中整合情感音律已经证明增加了用户参与度和留存率。

在具身智能应用中，触觉和力反馈机制已经成为环境交互中至关重要的模态，增强的感官保真度使操作能力变得越来越精确[620]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.5 Summary and Discussion/section
在总结与讨论中，研究表明构建统一的多模态模型以支持多种感知能力的输入和输出是当前的研究焦点。然而，智能体感知面临挑战，表示学习、对齐和融合方面的问题阻碍了健壮且具有泛化能力的感知系统的发展。未来的研究方向建议采用动态神经结构实现自适应表示学习，利用对比学习原理的自监督时空同步机制进行跨模态对齐，并整合因果推断框架以增强鲁棒性。此外，分层注意力机制和可学习门控函数的探索，以及可微分记忆网络技术的应用，有望为多模态数据的表示融合提供新途径，促进感知系统的发展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.5 Summary and Discussion/section/0/text
1. 当前的多模态感知系统在表示学习、对齐和融合方面存在哪些持续问题，以及这些问题如何阻碍了健壮且具有泛化能力的感知系统的发展？  2. 为什么表示方法在捕捉多模态数据的复杂微妙之处时存在不足，特别是在需要高维感官输入场景中保留关键语义信息时？  3. 在多模态数据的表示融合过程中，为什么将异构数据类型整合到一个连贯的特征空间会面临计算密集性和不一致性的挑战？
尽管越来越多的研究作品[543, 590]专注于构建统一的多模态模型，以支持多种感知能力的输入和输出。智能体感知作为自主系统的基石，在有效解释和整合多模态数据方面面临着重大挑战。当前的方法论在表示学习、对齐和融合方面遇到持续问题，这些问题阻碍了健壮且具有泛化能力的感知系统的发展。

其中一个主要问题在于所采用的表示方法，通常未能捕捉到多模态数据的复杂微妙之处。这种不足在需要复杂抽象以保留关键语义信息的高维感官输入场景中尤为明显。此外，表示的对齐也带来额外的困难。将异构数据类型整合到一个连贯的特征空间不仅计算密集，而且容易出现不一致性，这可能导致对模糊信号的错误解读。当尝试融合这些不同的表示时，挑战更加严峻，因为从各个来源合并特征的过程通常会导致集成不佳和关键信息的潜在丢失。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/7Perception 77/7.5 Summary and Discussion/section/1/text
1. 未来的研究如何通过动态神经结构实现自适应表示学习，并如何应对环境背景和任务需求的变化？ 2. 如何利用对比学习原理的自监督时空同步机制实现跨模态对齐，以建立密集对应关系而无需大量标记数据？ 3. 在多模态数据的表示融合方面，如何探索具有可学习门控函数的分层注意力机制，以实现对互补模态特征的上下文感知整合？
未来的研究方向应优先考虑通过动态神经结构实现自适应表示学习，这些结构能够根据环境背景和任务需求自动调整其结构。这可能涉及元学习参数化或基于图的表示，明确地建模感知实体之间的关系。对于跨模态对齐，利用对比学习原理的自监督时空同步机制显示出在建立密集对应关系方面的潜力，而无需耗费大量标记数据。将因果推断框架整合到对齐过程中[621]，可以进一步增强对抗虚假相关性的鲁棒性。在表示融合方面，具有可学习门控函数的分层注意力机制值得深入探索，以实现对互补模态特征的上下文感知整合。可微分记忆网络中的新技术可能为在较长时间范围内维护和更新融合表示提供新途径。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.1 The Human Action System 86/section
本节探讨了人类行动系统，将智能代理置于模块化、脑启发式架构中。首先，深入研究了智能代理的模块化基础，将认知、感知和操作模块映射到人脑功能，并探讨了核心组件如记忆、世界建模和奖励处理系统。其次，讨论了自我增强和自适应进化机制，探索代理如何适应动态环境并实现持续学习。第三，研究了协作和进化多代理系统，突出集体智能的出现和与人类社会动态的相似之处。最后，强调构建安全、可靠和有益的人工智能系统的使命，提出了实用缓解策略。通过综合不同学科的见解，揭示了关键的研究空白、挑战和机遇，为技术进步与社会利益的协调提供了新的视角。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.1 The Human Action System 86/section/0/text
1. 主体行为系统的范式如何在模块化、脑启发式架构中体现？这种架构对于智能代理的发展有何重要意义？ 2. 在行为学习范式中，自我增强和自适应进化机制是如何帮助智能代理适应动态环境并实现持续学习的？ 3. 行为与感知中的“自外而内”和“自内而外”两种范式分别代表了什么样的认知方式，它们在智能代理系统中的应用有何不同之处？
8.2 从人类行为到主体行为 87
8.3 主体行为系统的范式 88
8.3.1 行为空间范式 88
8.3.2 行为学习范式 91
8.3.3 基于工具的行为范式 93
8.4 行为与感知：“自外而内”还是“自内而外” 95
总结与讨论 97

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/[Self-Evolution in Intelligent Agents 101/section
本章探讨了智能代理中的自我演化优化空间和维度。首先，代理优化概述包括提示优化，其中评估函数、优化函数和评估指标是关键要素。其次，工作流优化涵盖工作流程制定、优化工作流边缘和节点。这些内容深入探讨了代理如何通过自我演化机制实现能力的完善和动态环境的适应，同时介绍了工作流的优化策略，为持续学习和自动化优化提供了重要参考。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/[Self-Evolution in Intelligent Agents 101/section/0/text
1. 代理优化中的评估函数、优化函数和评估指标在何种情况下起到关键作用？ 2. 如何通过工作流程制定和优化工作流边缘以及节点来实现智能代理的自我演化和动态环境适应？ 3. 在智能代理中，持续学习和自动化优化是如何与工作流的优化策略相互关联并相互促进的？
自我演化的优化空间和维度 103
9.1 代理优化概述 103
9.2 提示优化 103
9.2.1 评估函数 104
9.2.2 优化函数 104
9.2.3 评估指标 105
9.3 工作流优化 105
9.3.1 工作流程制定 105
9.3.2 优化工作流边缘 106
9.3.3 优化工作流节点 106

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization 107/section
9.4.1 学习使用工具 107 9.4.2 创造新工具 107 9.4.3 评估工具有效性 108 走向自主代理优化 110

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization 107/section/0/text
1. 在学习使用工具、创造新工具以及评估工具有效性的过程中，哪些因素对于自主代理优化的发展起到关键作用？ 2. 在走向自主代理优化的过程中，如何平衡现有工具的使用、新工具的创造以及工具有效性的评估之间的关系？ 3. 如何利用学习使用工具和创造新工具的经验，来推动自主代理优化的实现？
9.4.1 学习使用工具 107
9.4.2 创造新工具 107
9.4.3 评估工具有效性 108
走向自主代理优化 110

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/section
本章深入研究了10大语言模型作为优化器的核心内容。首先介绍了优化范式的三种类型：基于梯度的优化、零阶优化和基于LLM的优化，强调了基于LLM的优化策略在复杂环境中具有更大适应性和战略远见。其次，探讨了LLM优化的迭代方法，包括从经典优化理论中汲取灵感，通过迭代更新步骤解决离散和结构化挑战。在优化超参数方面，LLM方法挑战在于聚合函数选择和模块化工作流程设计，未来的研究需要发展元优化策略以解决挑战。此外，深度和时间跨度优化方面指出LLMs动态优化工作流程，未来研究可探索工程优化技术在基于LLMs的优化中的应用。最后，从理论视角分析LLMs作为通用优化器的潜力，揭示了上下文学习、机制可解释性和不确定性下的挑战，强调LLMs在动态或不确定环境中的部署仍需解决探索和稳健决策的问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.1 Optimization Paradigms/section
本节介绍了优化范式的三种类型：基于梯度的优化、零阶优化和基于LLM的优化。基于梯度的方法需要梯度信息进行参数调整，如SGD和牛顿法；零阶优化则通过估计搜索方向来避免梯度需求，如贝叶斯优化和进化策略；而基于LLM的优化则利用自然语言和反馈机制来拓展解决方案空间。尽管基于梯度和零阶方法主要应用于数值目标，但它们的核心原则也支持基于LLM的优化策略。基于强化学习的LLM优化已成为重要模型，预计将推动LLM在复杂环境中的更大适应性和战略远见。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.1 Optimization Paradigms/section/0/text
1. 传统优化方法中的基于梯度和零阶优化各有哪些优缺点，以及它们在离散问题和基于语言的任务中的适用性如何？ 2. 基于LLM的优化是如何利用自然语言和反馈机制来拓展解决方案空间的？它相较于基于梯度和零阶优化有哪些独特优势？ 3. 在复杂环境中，基于强化学习的LLM优化是如何提高适应性和战略远见的？它对于解决哪些类型的问题具有潜在的应用前景？
传统优化方法在对目标函数可访问性的假设上存在差异。我们将它们分为三类，每一类在输入空间的扩展级别上都有所不同：基于梯度的优化，依赖于显式函数梯度；零阶优化，无需梯度信息操作；以及基于LLM的优化，超越了对结构化和高维输入空间的数值函数进行优化。

·基于梯度的优化。这些方法假设可以访问梯度信息，并通过迭代调整参数。诸如随机梯度下降（SGD）和牛顿法等技术被广泛使用，但需要可微性，这限制了它们在离散问题（如提示调整和结构化决策工作流）中的适用性，通常赋予了图结构。
·零阶优化。这些方法通过从函数评估中估计搜索方向来绕过对显式梯度的需求。例如，贝叶斯优化、进化策略和有限差分方法等，当梯度不可用或计算昂贵时，这些方法是有效的。然而，它们仍依赖于明确定义的数值目标和结构化搜索空间，这限制了它们在基于语言的任务中的适用性。
·基于LLM的优化。LLMs通过利用自然语言作为优化域和反馈机制来优化更广泛的解决方案空间。通过结构化推理和类人迭代，LLMs擅长于优化提示、生成自适应工作流，并根据用户反馈逐步改进任务性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.1 Optimization Paradigms/section/1/text
1. 基于梯度和零阶方法的核心原则如何支撑基于LLM的优化策略？这种支撑是如何体现在迭代细化、搜索启发和自适应学习等方面的？ 2. 基于强化学习的LLM优化在何种程度上成为缓慢思考推理模型的支柱？它是如何推动LLM在复杂环境中具有更大适应性和战略远见的？ 3. 预计基于强化学习的LLM优化模型将如何影响下一波主动应用的浪潮？它们在提升LLM的适应性和战略远见方面有哪些关键作用？
虽然基于梯度和零阶方法通常应用于数值目标，但它们的核心原则，如迭代细化、搜索启发和自适应学习，也支撑着基于LLM的优化策略。基于这些见解，我们强调了一类快速兴起的基于强化学习的LLM优化，已成为缓慢思考推理模型的支柱。随着这些模型不断发展，我们预计它们将推动下一波主动应用的浪潮，使LLM能够在复杂环境中具有更大的适应性和战略远见。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section
LLM优化的迭代方法主要涉及从经典优化理论中汲取灵感，通过迭代更新步骤来解决离散和结构化挑战。这些方法的核心特征是在迭代更新步骤中选择模型生成的修改，以完善目标。通过抽样、评估和更新步骤，基于agent的任务定义，可以选择最佳决策变量。随机搜索方法类似于进化算法，通过迭代抽样候选决策变量并选择表现最佳的候选解。相比之下，基于梯度的方法利用过去的细化方向，通常导致更快的收敛，尤其适用于多阶段工作流程。贝叶斯优化作为一个替代方案构建了抗噪声的优化目标的代理模型，通过提议、提议评估和更新步骤来优化目标。这些方法在基于LLM的优化中取得了显著进展，尽管存在高交互次数和噪声敏感的挑战，贝叶斯优化作为一个引人注目的替代方案出现，以构建抗噪声的优化目标的代理模型。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/0/text
1. LLM优化方法如何通过迭代更新步骤选择模型生成的修改来完善目标？这种方法在解决离散和结构化挑战时有哪些优势和局限性？  2. 基于梯度的优化方法相较于随机搜索方法在多阶段工作流程中有何优势？如何利用过去的细化方向实现更快的收敛？  3. 贝叶斯优化作为一种替代方案是如何构建抗噪声的优化目标的代理模型的？它在基于LLM的优化中的应用有哪些优势和挑战？
一些基于LLM的优化方法直接从经典优化理论中汲取灵感，通过调整关键组件来解决离散和结构化挑战。这些方法的一个核心特征是迭代更新步骤，在这一步骤中，从各种可能的改进中选择模型生成的修改，以完善目标。以方程（9.1）中的提示优化目标作为运行示例，一个通用的迭代

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/1/figure
1. 基于LLM的优化方法中，随机搜索、梯度逼近和代理建模分别具有怎样的特点和优势？它们在解决离散和结构化挑战时有何不同之处？     2. 在LLM的优化中，贝叶斯优化作为一个替代方案具有怎样的特点？它是如何构建抗噪声的优化目标的代理模型的？
图10.1：基于LLM的优化方法分类法，分为随机搜索、梯度逼近和代理建模。我们还强调了一些关于上下文学习的理论解释，其中包括假设学习、隐式贝叶斯推断和机械性可解释性，这些理论支撑了LLM的优化能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/2/text
1. 在基于agent的任务定义中，为什么抽样和更新步骤是至关重要的？这两个步骤如何相互作用以完善目标函数？  2. 在复杂的agent工作流程中，决策变量的组合特性如何影响优化过程？为什么枚举所有可能解通常是不可行的，需要设计近似的更新步骤？  3. 在LLM优化中，为什么贝叶斯优化作为一个引人注目的替代方案出现？它是如何构建抗噪声的优化目标的代理模型的？
算法可以表达如下：

抽样：$T\sim\mathcal{D}$ 评估：$\ensuremath{\mathcal{L}}(T;T_{p})\gets\phi_{\mathrm{eval}}(\phi_{\mathrm{exe}}(Q,T_{p}),T)$ 更新：$T_{p}^{\prime}\gets\phi_{\mathrm{opt}}\left(\mathcal{L}(T;T_{p})\right)$

这里，抽样和更新步骤是基于agent的任务定义的。在最简单的情况下，比如优化电影评论的二元分类指令，目标函数$\mathcal{L}$ 通过分类准确度来衡量。在更复杂的agent工作流程中，决策变量可能包括不同工作流程阶段的提示、工具选择、agent拓扑结构，或者二者的组合。正如第9章所讨论的，这些决策变量的一个共同特征是它们的组合特性，比如来自LLM词汇$\nu$的所有字符串集合或者工作流程中agent的所有可能角色分配。由于枚举所有可能解通常是不可行的，这就需要设计近似的更新步骤$\phi_{\mathrm{opt}}$，接下来我们将讨论这一点。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/3/text
1. 随机搜索方法在基于LLM的优化中的优势和局限性是什么，特别是在处理多个查询的复杂工作流程时可能面临的挑战是什么？  2. 如何理解随机搜索方法中的抽样、评估和更新步骤，以及如何通过ArgTopK来选择表现最佳的候选解？  3. 随机搜索方法相比于基于梯度的方法和贝叶斯优化，如何在解决离散自然语言空间中的提示优化问题时展现出独特的优势？
· 随机搜索。早期基于LLM的优化方法利用随机搜索变体来优化离散自然语言空间中的提示[774,807,651,732,808,809,810]。这些方法通常类似于进化算法，通过迭代地抽样候选决策变量，并从每次迭代中选择表现最佳的候选解。一般的表达式如下：

抽样：$T\sim\mathcal{D}$ 评估：$\mathcal{L}^{(i)}\gets\phi_{\mathrm{eval}}(\phi_{\mathrm{exe}}(Q,T_{p}^{(i)}),T),\quad i=1,\ldots,M$ 更新：$\{T_{p}^{(k)\prime}\}_{k=1}^{K}\leftarrow\mathrm{ArgTopK}_{i\in[M]}\mathcal{L}^{(i)},$ 补充（可选）：$\{T_{p}^{(j)}\}_{j=K+1}^{M}\sim\mathrm{Mutate}(\{T_{p}^{(k)}\}_{k=1}^{K}).$

我们简要修改之前的符号，令$M$表示每次迭代中抽样的候选提示总数，$K$（其中$K<M$）控制通过ArgTopK在我们的算法中选择的表现最佳候选数量，保留到下一步。该算法可以选择性地包括一个补充步骤，以在迭代过程中保持候选集的多样性。随机搜索方法易于实现，高度可并行化，并且特别适用于单提示工作流程。除了提示优化，它们还在选择上下文演示中表现出色。然而，它们的效率是有代价的——每次迭代需要$O(M)$个并行API查询，这对于涉及多个查询的复杂工作流程可能会变得昂贵。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/4/text
1. 基于梯度的方法相较于随机搜索方法具有哪些优势，导致更快的收敛速度？这种优势是如何体现在迭代更新过程中的决策变量选择上的？  2. 在梯度逼近方法中，如何利用历史信息来指导决策变量的修改，以实现更快的收敛？这种历史信息如何影响下降方向的估计和目标的优化？  3. 梯度逼近方法中的“下降方向”概念是如何帮助系统性修改决策变量以改善目标的？与随机搜索方法相比，这种系统性修改如何体现在迭代更新步骤中的决策变量选择上？
· 梯度逼近。几种方法通过迭代地改进解来近似基于梯度的更新。例如，[779,730,728]在不同的工作流程阶段生成改进。StraGO[722]利用中心差异启发式方法估计下降方向，而Trace[813]通过将其建模为计算图来优化组合程序，类似于反向传播。连续优化中梯度更新和提示空间改进之间的关键类比是“下降方向”的概念，即系统性修改决策变量以改善目标。相比之下，随机搜索方法在每一步独立提出新的决策变量，而不访问过去的更新轨迹。相反，基于梯度的方法利用这些历史信息，通常导致更快的收敛。梯度逼近方法的一般迭代如下所示：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/5/formula
$$ 
\begin{array}{r}{\mathbf{Sample:}T^{(i)}\sim\mathcal{D},\quad i=1,\dots,M\qquad}\\ {\mathbf{Evaluation:}\mathcal{L}^{(i)}\leftarrow\phi_{\mathrm{eval}}(\phi_{\mathrm{exe}}(Q,T_{p}),T^{(i)}),\quad i=1,\dots,M}\\ {\mathbf{Gradient\Approximation:}g\leftarrow\nabla_{\mathrm{LLM}}\mathbf{Agg}\left(\mathcal{L}^{(1)},\dots,\mathcal{L}^{(M)}\right)}\\ {\mathbf{Update:}T_{p}^{\prime}\leftarrow\phi_{\mathrm{opt}}(T_{p},g),\qquad}\end{array}
 $$
这个公式的目的是描述梯度逼近方法在基于LLM（Language Model）的优化中的迭代过程。该方法包括四个关键步骤：采样（Sample）、评估（Evaluation）、梯度近似（Gradient Approximation）和更新（Update）。在采样步骤中，从分布 $\mathcal{D}$ 中采样 $M$ 个样本 $T^{(i)}$。在评估步骤中，通过执行函数 $\phi_{\mathrm{exe}}$ 对查询 $Q$ 和当前提示 $T_{p}$ 进行处理，然后对每个样本 $T^{(i)}$ 计算损失 $\mathcal{L}^{(i)}$。在梯度近似步骤中，通过聚合函数 $\mathbf{Agg}$ 结合所有样本的损失来估计LLM的梯度 $g$。最后，在更新步骤中，通过应用优化函数 $\phi_{\mathrm{opt}}$，基于梯度 $g$ 更新提示 $T_{p}$。  在这个公式中，$M$ 表示小批量大小，$\mathbf{Agg}(\cdot)$ 是一个聚合函数，通常用于将多个损失值组合成一个梯度方向。$\nabla_{\mathrm{LLM}}$ 表示LLM的梯度算子，它基于损失信号和当前小批量生成文本的细化方向。$\phi_{\mathrm{opt}}$ 是一个LLM查询函数，用于根据梯度 $g$ 更新提示 $T_{p}$。整体而言，这个公式描述了基于LLM的优化过程中，如何通过迭代更新提示来逼近最优解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/6/text
1. 在基于LLM的优化中，为什么基于梯度的方法通常比随机搜索方法更适合多阶段工作流程？   2. 贝叶斯优化作为一个替代方案在处理LLM优化中的哪些挑战上表现出独特优势？   3. 在LLM优化中，如何利用$\nabla_{\mathrm{LLM}}$和$\phi_{\mathrm{opt}}$来指导代理根据反馈信号和当前小批量生成文本细化方向？
这里，$M$ 是小批量大小，$\operatorname{Agg}({\mathord{\cdot}})$ 是一个聚合函数，用于结合反馈信号（例如，在数值优化中，Agg 通常是平均算子），$\nabla_{\mathrm{LLM}}$ 表示一个抽象的“LLM-梯度算子”[728]，它基于反馈信号和当前小批量生成文本细化方向（例如，代理应考虑边缘情况...）。此外，$\phi_{\mathrm{opt}}$ 可以被实例化为一个LLM查询，使代理能够根据 $g$ 更新其提示。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/7/text
1. 相对于随机搜索方法，基于梯度的方法在多阶段工作流程中的优势体现在哪些方面？这种优势是如何影响优化过程的效率和结果的？  2. 基于梯度的方法在优化过程中具有灵活性和特定优势，但这种优势是如何导致设计开销增加的？如何解释需要元提示来聚合反馈并应用细化方向的过程？  3. 相比于直接基于梯度优化软提示的方法，基于梯度的方法在多步工作流程和顺序决策中面临的困难是什么？这些困难如何影响基于梯度方法在复杂任务中的应用和效果？
相对于随机搜索方法，基于梯度的方法具有两个关键优势：它们能够将过去的细化方向纳入 $\phi_{\mathrm{opt}}$ 中，类似于一阶优化算法中的动量技术[814,815]，并且它们促进类似反向传播的技术来优化计算图[651,813,780]，使它们特别适用于具有相互依赖的可优化模块的多阶段工作流程。然而，这种灵活性是以增加设计开销为代价的，例如需要元提示来聚合反馈并应用细化方向。我们将在下文进一步讨论使用LLMs来优化这些超参数的可行性。一些方法还探讨了直接基于梯度优化软提示[816,817,818]。虽然对于简单的输入-输出序列学习有效，但这些方法在多步工作流程和顺序决策方面存在困难[630, 300]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/8/text
1. 在基于LLM的优化中，为什么将二阶技术（如拟牛顿方法）扩展到优化仍然是一个相对未被探索的领域？Revolve是如何通过引入结构化方法进行二阶优化，解决多次迭代中响应模式的演化问题的？  2. 相较于一阶优化方法，为什么二阶技术在基于LLM的优化中具有重要意义？Revolve如何通过整合更高阶的细化实现更稳定和明智的优化，缓解了复杂任务中的停滞现象？  3. 在基于LLM的优化中，如何利用推断时计算来整合历史细化方向并探讨动量的好处？这种新趋势对于优化方法有何启示和影响？
最后，尽管这些方法利用了一阶优化的见解，但将二阶技术（例如拟牛顿方法）扩展到基于LLM的优化仍然是一个相对未被探索的领域。幸运的是，最近的一些工作，如Revolve，已经朝着这个方向迈出了一步，通过引入结构化方法进行二阶优化，对多次迭代中响应模式的演化进行建模。通过整合更高阶的细化，Revolve实现了更稳定和明智的优化，有效地缓解了复杂任务中的停滞现象。我们也对利用推断时计算来整合历史细化方向并探讨动量的好处的新趋势感到兴奋。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/9/text
1. 贝叶斯优化在基于LLM的优化中相较于其他方法的优势是什么？它是如何构建抗噪声的优化目标的代理模型的？    2. 在处理LLM优化中，为什么贝叶斯优化被认为是一个引人注目的替代方案？它是如何解决高交互次数和噪声敏感的挑战的？  3. 相比于基于梯度的方法和随机搜索方法，贝叶斯优化如何应对离散提示的优化景观和其他决策变量的不确定性？
·贝叶斯优化和代理模型。虽然前述方法在基于LLM的优化中取得了显著进展，但由于所需LLM交互次数较高，通常会带来相当大的财务和环境成本。此外，这些方法对噪声敏感，而离散提示的优化景观，以及其他决策变量，仍然知之甚少。在这些限制条件下，贝叶斯优化（BO）作为一个引人注目的替代方案出现，因为它构建了一个抗噪声的优化目标的代理模型：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/10/text
1. 代理模型在基于LLM的优化中扮演着怎样的角色？它是如何通过提议、提议评估和更新步骤来优化目标的？  2. 基于梯度的方法相较于随机搜索方法有哪些优势和劣势？在解决多阶段工作流程优化问题时，为什么基于梯度的方法更具优势？  3. 贝叶斯优化作为一个替代方案，如何构建抗噪声的优化目标的代理模型？它在解决高交互次数和噪声敏感挑战方面有何优势？
样本：T \~ D 提议：$\{T_{p}^{(i)}\}_{i=1}^{M}\sim S$ 提议评估：$\mathcal{L}^{(i)}\gets\phi_{\mathrm{eval}}(\phi_{\mathrm{exe}}(Q,T_{p}^{(i)}),T),\quad i=1,\hdots,M$ 更新：$S\gets S.\mathrm{UpdatePrior}(\{\mathcal{L}^{(i)}\}_{i=1}^{M},\{T_{p}^{(i)}\}_{i=1}^{M}),$ 其中$S$表示优化目标的概率代理模型，配备有一个提议操作符（例如，从高斯过程BO过程中后验采样[803]）和一个基于提示评估观察证据的更新机制。例如，MIPRO[821]采用树结构帕森估计器作为其代理[822]，而PROMST[823]训练一个分数预测模型来指导提示调整。利用代理模型进行基于LLM的优化符合非可微目标的摊销优化的新兴趋势[824]。例如，[825]训练一个提示生成器LLM来摊销实例化用于发现越狱攻击前缀的波束搜索问题的计算成本。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.2 Iterative Approaches to LLM Optimization/section/11/text
1. 在基于LLM的优化中，如何将轻量级模块（如贝叶斯信念后验或效用函数）与LLM输出相结合，以优化特定领域工作流程？这种摊销方法如何帮助处理未知输入的情况？  2. 在基于LLM的优化中，相比于基于梯度的方法，贝叶斯优化是如何构建抗噪声的优化目标的代理模型的？这种方法如何应对高交互次数和噪声敏感的挑战？  3. 在基于LLM的优化中，轻量级模块与LLM输出相结合的方法如何有助于决策制定和多智能体协商？这种方法在越狱攻击等情景下有何应用？
最后，还有一些工作将额外的轻量级模块（例如贝叶斯信念后验或效用函数）与LLM输出相结合，以帮助优化特定领域工作流程，如决策制定和多智能体协商。这种摊销方法，即适应参数化模型以便用于未知输入的方法，在基于LLM的优化中越来越常见，例如越狱攻击。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.3 Optimization Hyperparameters/section
在优化超参数方面，基于大型语言模型（LLM）的方法对聚合函数的选择和模块化工作流程设计提出了挑战。聚合函数的选择在LLM优化器中至关重要，影响文本反馈的综合和提示更新的准确性。此外，将LLM程序分解为可解释的模块需要更多的设计探讨，以解决优化决策流程中的挑战。超参数在LLM优化中类似于数值优化，如批量大小和动量对性能起着关键作用。然而，LLM优化器的超参数选择仍然是启发式的，缺乏系统性发展。在代理系统设计中，超参数选择涉及到代理角色、上下文演示和工具调度，影响下游性能。目前，针对这些超参数的优化方法仍未得到系统性发展，传统技术的计算成本高且不具扩展性。未来的研究方向包括元优化策略的发展，通过LLM优化自身的超参数和决策策略来解决挑战，需要平衡探索与利用，并确保在不同优化任务中实现泛化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.3 Optimization Hyperparameters/section/0/text
1. 基于大型语言模型的优化方法中，为什么聚合函数的选择如此关键，对文本反馈的综合和提示更新有何影响？ 2. 在LLM优化中，为什么将LLM程序分解为可解释的模块是必要的？这种模块化工作流程设计的不足之处在哪里？ 3. 传统优化和基于LLM的优化方法在超参数敏感性方面有何区别？如何平衡探索与利用，确保在不同优化任务中实现泛化？
类似于传统优化，基于LLM的方法对影响搜索效率和泛化的超参数非常敏感。在基于梯度的LLM优化器中，一个关键考虑因素是聚合函数 $\operatorname{Agg}({\mathord{\cdot}})$ 的选择，该函数决定了如何综合文本反馈以指导提示更新。选择不当可能导致关键信息的丢失或在迭代改进中出现不对齐。此外，引入了一种“白板”方法，其中LLM程序被分解为人类可解释的模块。然而，在构建这种模块化工作流程方面的设计选择仍然很少被探讨，这对优化LLM驱动的决策流程构成了一个开放性挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.3 Optimization Hyperparameters/section/1/text
1. LLM优化中的超参数选择为何至关重要？它们与数值优化中的超参数有何相似之处？在当前研究中，超参数选择存在哪些挑战和局限性？  2. 在基于LLM的优化器中，为什么批量大小和动量被认为是关键因素？它们各自在优化过程中起到什么作用？相比于传统数值优化，基于LLM的方法如何利用这些因素进行性能提升？  3. 针对基于LLM的优化器，当前超参数选择方法存在哪些不足之处？为什么现有技术的计算成本高且缺乏扩展性？未来的研究方向如何探讨元优化策略来解决这些挑战？
LLM 优化中的超参数通常与数值优化中的超参数相似。例如，批量大小起着至关重要的作用：就像小批量更新在经典优化中增强了稳定性和效率一样，基于LLM的方法（如TextGrad）在进行更新之前会在多个生成的样本中聚合反馈信息。另一个关键因素是动量-它通过结合过去的梯度来稳定梯度方法中的更新，在LLM优化器中同样利用历史的改进来随时间提高性能。尽管在数值优化方面取得了进展，针对基于LLM的优化器的超参数选择仍然主要是启发式的，通常依赖于临时的试错调整。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.3 Optimization Hyperparameters/section/2/text
1. 传统的超参数调整技术在处理基于LLM的工作流程中存在哪些挑战，导致它们的计算成本扩展性不佳？  2. 元优化策略如何可以帮助解决LLM优化器中超参数和决策策略的优化问题？这种方法可能会引入哪些新的挑战？  3. 为什么将LLM用于优化其自身的超参数和决策策略可能是解决代理系统设计中超参数优化挑战的有前途方向？
在代理系统设计中，超参数在各个组件中广泛存在，包括代理的角色分配、上下文演示的选择以及工具调用的调度。这些选择对下游性能产生深远影响，然而，针对它们的优化方法仍未得到系统发展。虽然传统的超参数调整技术，如网格搜索和贝叶斯优化，可以应用于离散的基于LLM的工作流程，但由于语言模型输出的高方差，它们的计算成本呈现不良的扩展性。此外，这些超参数的组合性质，即代理配置、提示策略和推理结构以复杂方式相互作用，使得穷举搜索变得不可行。最近的研究尝试通过将代理工作流嵌入到结构化框架中，如有限状态机、最优决策理论和博弈论，来解决这一挑战。然而，这些方法通常难以在不同环境中推广。解决这些挑战的一个有前途的方向是元优化，其中LLM被用于优化其自身的超参数和决策策略。例如，基于LLM的优化器可以通过将过去的决策视为经验来迭代地优化其提示策略，类似于深度学习中的学习优化器。此外，摊销方法训练辅助模型来预测有效的超参数，可以降低穷举搜索的计算成本。虽然这些技术提供了令人兴奋的可能性，但也引入了新的挑战，比如在自适应调整中平衡探索与利用，并确保在各种优化任务中实现泛化。研究针对LLM驱动工作流程量身定制的有原则的元优化策略，仍然是未来研究的一个关键领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.4 Optimization across Depth and Time/section
在深度和时间跨度优化方面，大型语言模型（LLMs）与传统优化器有所不同，动态优化工作流程。LLMs类似于前馈网络，按顺序优化工作流程，同时也可以随时间进行优化，类似于循环架构，通过迭代改进决策制定。StateFlow通过跨多次迭代结合反馈来增强工作流程，实现动态改进和适应。尽管这些类比令人信服，但工程优化技术在基于LLMs的优化中仍未得到充分探讨，如检查点和截断反向传播。未来研究可以探索这一方向，以回应对更深入研究的呼吁。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.4 Optimization across Depth and Time/section/0/text
1. LLMs如何在动态优化工作流程中结合深度（单次工作流）和时间（循环更新）的考虑，与传统优化器有何不同之处？  2. 为什么工程优化技术中的一些成熟方法，如检查点和截断反向传播，在基于LLMs的优化中仍未得到充分探讨？  3. StateFlow是如何通过跨多次迭代结合反馈来增强工作流程，实现动态改进和适应的？
与在静态环境中更新参数的传统优化器不同，LLMs在考虑深度（单次工作流）和时间（循环更新）时动态优化工作流程。在深度方面，LLMs的功能类似于前馈网络，按顺序优化工作流程，通过不同模块时进行优化，大多数现有基于LLMs的优化器都遵循这种范例。除了单次执行，LLMs还可以随时间进行优化，类似于循环架构，如RNN或Universal Transformers，通过迭代地改进决策制定。例如，StateFlow通过跨多次迭代结合反馈来增强工作流程，实现随时间的动态改进和适应。虽然这些类比令人信服，但许多成熟的工程优化技术，如检查点和截断反向传播，在基于LLMs的优化中仍未得到充分探讨。我们认为这是未来研究的一个有前途的方向，呼应先前对更深入研究的呼吁。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.5 A Theoretical Perspective/section
在"理论视角"章节中，研究指出，最近的进展揭示了大型语言模型（LLMs）如何作为通用优化器执行类似优化计算的潜力。通过上下文学习，LLMs能够在少样本设置中学习多样的回归假设，包括迭代优化算法的实现。然而，对LLMs中上下文学习的理论解释仍存在挑战，尤其是在离散的输入-输出空间中。同时，机制可解释性的研究通过识别负责特定行为的子图，揭示了内部变压器计算的机制。然而，机制可解释性方法揭示了一个挑战：在许多样本演示的条件下，上下文学习能力可能导致有益泛化和有害行为之间的混淆。此外，LLMs在不确定性下做出最优选择时也存在困难，尤其是在适应随机环境时。尽管LLMs重新定义了优化，但其在动态或不确定环境中的部署仍面临探索和稳健决策的挑战。虽然LLMs在结构化搜索空间中表现出色，但其基于上下文学习的优化理论基础仍有待深入探讨，特别是在标准梯度训练之外的情况下。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.5 A Theoretical Perspective/section/0/text
1. 变压器作为通用优化器的潜力在哪些方面得到支持？其经验成功和理论理解之间存在的重大差距体现在哪些方面？  2. 上下文学习在大型语言模型中的应用有哪些特点？为什么在离散的输入-输出空间中对LLMs中上下文学习的理论解释存在挑战？  3. 机制可解释性方法如何帮助揭示内部变压器计算的机制？在许多样本演示的条件下，上下文学习能力可能导致有益泛化和有害行为之间的混淆，这给安全可靠地优化LLM工作流程带来了什么挑战？
最近的研究表明，变压器本质上执行类似优化的计算，支持它们作为计算工作流通用优化器的潜力。然而，在它们的经验成功和理论理解之间存在重大差距。在这里，我们简要概述了最近在弥合这一差距方面取得的进展。

·上下文学习。将变压器视为优化器的一个基本视角源自于上下文学习，特别是在少样本设置中。研究表明，变压器可以在上下文中学习多样的回归假设，包括正则化线性模型、决策树和浅层神经网络。后续研究证明了变压器可以实现迭代优化算法，如梯度下降和二阶更新。然而，尽管这些理论模型表征了变压器的优化能力，它们并未完全解释大规模LLMs中的上下文学习，后者在离散的输入-输出空间中运行。相反，经验分析试图理解预训练LLMs在上下文中的泛化。提出上下文学习类似于执行隐马尔可夫模型（HMM）进行隐式贝叶斯推断，而挑战传统观点认为上下文演示为假设形成提供了新的测试样本。上下文学习仍然是使自我改进和优化从上下文中产生的核心新能力，然而它仍然难以进行全面的理论分析。
·机制可解释性。与理论分析相对应，机制可解释性旨在通过识别负责特定行为的子图，也称为电路，揭示内部变压器计算。早期研究在预训练的GPT-2模型中为艺术语言任务映射了电路，而最近的工作通过使用稀疏自动编码器识别语义上有意义的特征进行了扩展。这些方法在从事前沿级LLMs中引出因果和可控行为方面取得了很大成功，但它们也揭示了一个意外后果：在很多样本演示的条件下，上下文学习能力常常将有益的泛化与有害行为纠缠在一起。这给安全可靠地优化LLM工作流程带来了挑战。
·不确定性下的局限性。尽管LLMs在提供上下文信息时在顺序决策方面表现出中等能力，但它们在不确定性下做出最优选择时会遇到困难。特别是发现，基于LLMs的优化器在适应随机环境时存在困难，通常无法进行最佳探索。这些发现为在探索和稳健决策至关重要的动态或不确定环境中部署基于LLMs的优化器提出了警示。LLMs通过整合结构化推理、自然语言处理和上下文学习重新定义了优化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/10 Large Language Models as Optimizers/10.5 A Theoretical Perspective/section/1/text
1. 基于大型语言模型的优化方法在处理离散输入-输出空间时，存在哪些理论挑战和难点？ 2. 上下文学习在大型语言模型中的应用可能导致有益泛化和有害行为之间的混淆，这种混淆如何影响模型的稳健性和决策过程？ 3. 在动态或不确定环境下，大型语言模型如何面临探索和稳健决策的挑战？这些挑战如何影响模型在实际应用中的性能表现？
超越传统的数值方法。尽管在结构化搜索空间中表现出强大的实证性能，但关于基于LLM的优化的理论基础仍存在一些未解之谜，特别是从标准梯度训练中出现上下文学习的问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/111/section
10.1 优化范式 111 10.2 LLM优化的迭代方法 111 10.3 优化超参数 114 10.4 跨深度和时间的优化 114 10.5 理论视角 115

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/111/section/0/text
1. 优化范式和LLM优化的迭代方法之间存在怎样的联系和区别？ 2. 在优化超参数过程中，如何权衡模型的性能和计算成本？ 3. 如何在跨深度和时间的优化中平衡模型的复杂性和训练效率？
10.1 优化范式 111
10.2 LLM优化的迭代方法 111
10.3 优化超参数 114
10.4 跨深度和时间的优化 114
10.5 理论视角 115

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Online and Offline Agent Self-Improvement 116/section
11.1 在线代理自我完善 116 11.2 离线代理自我完善 117 11.3 在线和离线改进的比较 118 11.4 混合方法 118

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Online and Offline Agent Self-Improvement 116/section/0/text
在线代理自我完善和离线代理自我完善有何区别？
11.1 在线代理自我完善 116
11.2 离线代理自我完善 117
11.3 在线和离线改进的比较 118
11.4 混合方法 118

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/section
在"科学发现与智能演化"章节中，探讨了智能代理在科学知识发现中的关键作用和挑战。首先介绍了智能度量的基础，包括KL散度和智能增长的统计特性。接着深入研究了代理与知识之间的交互，如假设生成与测试、协议规划与工具创新，以及数据分析与推论推导。重点关注了现实世界交互、复杂推理和知识整合等挑战。代理-知识交互是关键议题，代理通过不断更新心智状态和提高决策能力促进科学知识的发现与应用。然而，智能代理面临技术准备度挑战，如现实世界互动API限制、复杂推理困难和先验知识整合问题。未来需要技术进步以改善代理系统的自主知识发现能力，特别是在互动、推理和知识整合方面。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery 120/section
在代理人智能用于科学知识发现的章节中，首先介绍了基于KL散度的智能度量，然后探讨了智能增长的统计性质和智能演化策略。接着深入研究了代理与知识之间的交互，包括假设生成与测试、协议规划与工具创新，以及数据分析与推论推导。在技术准备和挑战方面，重点关注了现实世界交互挑战、复杂推理挑战以及整合先前知识的挑战。通过这些内容，揭示了智能代理在科学知识发现中的关键作用和挑战，为构建安全、可靠且有益的人工智能系统提供了重要的思路和方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery 120/section/0/text
1. 代理人智能如何利用基于KL散度的智能度量来衡量其在科学知识发现中的效果和价值？ 2. 在智能增长的统计性质中，哪些关键因素影响了代理人智能的发展和演化过程？ 3. 代理与知识之间的交互中，假设生成与测试如何促进了科学知识的发现和推进？
12.1.1 基于KL散度的智能度量 120
12.1.2 智能增长的统计性质 122
12.1.3 智能演化策略 123
12.2 代理-知识交互 123
12.2.1 假设生成与测试 124
12.2.2 协议规划与工具创新 126
12.2.3 数据分析与推论推导 126
技术准备和挑战 127
12.3.1 现实世界交互挑战 127
12.3.2 复杂推理挑战 128
12.3.3 整合先前知识的挑战 129

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/section
在代理人智能在科学知识发现中的应用章节中，我们从信息论的视角探讨了智能代理的智能度量核心内容。通过KL散度衡量代理对未知信息的预测能力，强调代理通过不断学习和适应来提高智能度量。此外，我们研究了智能代理的智力增长统计特性，指出智能水平随着知识获取而增加，尤其在面对新数据时智能增长速率更高。智能进化策略是智能代理进化的关键，通过优化参数来最大化智商，最小化与知识库之间的KL散度。代理可以采用不同的扩展策略，如随机探索和基于假设的方法，逐步接近完备认知状态。然而，存在发现界限，需要克服设计上的挑战以实现更高效的知识发现。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/section/0/text
1. 什么是智能代理的智能度量核心内容，以及如何通过KL散度衡量代理对未知信息的预测能力？ 2. 智能代理的智力增长统计特性是什么，智能水平是如何随着知识获取而增加的？ 3. 为了最大化智商和最小化与知识库之间的KL散度，智能代理可以采用哪些智能进化策略？
传统上被定义为合理真实信念的知识可以追溯到柏拉图[860]，并由埃德蒙·盖特尔[861]进一步完善，他认为知识必须由可靠的认知过程产生，尽管其确切定义仍然存在争议[862]。在我们的讨论中，我们将科学知识发现描述为收集数据和信息的过程，以证明或证伪关于目标科学问题的理性假设。为了讨论智能体在科学知识发现中的能力，我们首先通过信息论的视角探讨衡量智能体智能的一般框架。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section
智能代理的智能度量可以通过KL散度来衡量其对未知信息的预测和现实世界概率分布之间的差异。多种观点表明智能行为源于对不确定世界进行准确预测，强调智能代理通过建立预测性和可适应性模型来与世界互动。在科学知识发现中，代理的目标是从有限数据中推断物理世界的未知方面，通过KL散度衡量代理预测与真实世界分布之间的差异。代理的智能性可通过KL散度描述其对已知信息的预测准确性，智能度量取决于代理的世界模型参数和记忆中的知识。随着代理获得更多相关知识，其智能度量将更依赖于知识增强预测能力，反映出智能代理的不断学习和适应能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/0/text
1. 为什么多种观点认为智能代理的智能行为源于对不确定世界进行准确预测，以及如何通过KL散度来衡量其预测与真实世界分布之间的差异？ 2. 从Jaynes将概率论视为在不确定性下推理的扩展逻辑到Parret al.将智能框架化为在自由能原则下最小化模型-世界差异，这些观点如何帮助形式化代理对世界的“理解”？
智能代理的智能可以通过其对未知信息的预测和现实世界概率分布之间的KL散度来衡量。人工智能和科学哲学中长期以来的一个目标是形式化代理“理解”世界的含义。从Jaynes将概率论视为在不确定性下推理的扩展逻辑[863]，到Parret al.将智能框架化为在自由能原则下最小化模型-世界差异[864]，许多框架都聚焦于一个共同主题：智能行为源于对不确定世界进行准确预测。例如，Clark[344]认为智能代理通过预测和误差校正不断与世界互动以减少惊奇。Cholet[865]强调智能应反映技能习得效率，因为任务适应具有动态性质。总的来说，这些观点表明智能涉及建立预测性和可适应性模型——这里通过一个概率框架形式化，将推理与知识获取联系起来，并促进在科学发现中跨代理的比较。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/1/text
1. 代理如何通过KL散度来衡量其在科学知识发现中对物理世界未知方面的推断准确性？   2. 在代理与世界互动过程中，如何理解数据集合的出现概率$P_{\mathcal{W}}(\mathbf{x})$对代理的智能性和知识发现过程的影响？  3. 在代理与物理世界互动的过程中，如何利用已知和推断的命题构成的连贯文本来描述代理对世界的理解和知识发现能力？
在这个基础上，我们考虑智能在科学知识发现特定背景下的表现，其中代理的主要目标是从有限数据中推断物理世界的未知方面。从知识发现的角度看，世界 $\boldsymbol{\mathcal{W}}$ 被描述为与代理旨在理解的科学问题相关的数据集合 $\mathbf{x}=\{x_{1},x_{2},...,x_{n}\}$ 。在代理与 $\mathcal{W}$ 的互动过程中，每个数据集以概率 $P_{\mathcal{W}}(\mathbf{x})$ 出现在实验测量或观察中。在这里，我们假设个别数据点 $x_{i}$ 可能相关也可能不相关。例如，在使用语言模型生成文本的任务中，$x_{i}$ 代表形成有意义命题的一组标记，而 $\mathbf{x}$ 是由已知和推断的命题构成的连贯文本。在这种情境下，“世界”是所有命题的集合。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/2/text
1. 代理的智能度量中，KL散度如何帮助衡量代理对真实世界分布的预测准确性，以及代理的学习和适应能力？  2. 在科学知识发现中，为什么代理的目标是产生对真实世界的良好描述，以及如何通过KL散度来评估代理的智能水平？  3. 代理的智能度量如何随着其获取更多相关知识而变化，以及为什么智能度量更依赖于知识增强预测能力？
设 $\theta$ 表示参数，该参数对应代理的世界模型 $M_{t}^{\mathrm{wm}}$，如表1.2所定义。例如，在具有固定架构的Transformer模型中，$\theta$ 代表其权重。给定 $\theta$ 和数据集 $\mathbf{x}$，代理预测一个概率分布 $P_{\theta}(\mathbf{x})$。一般来说，不同的人工智能代理可能针对不同的目标进行优化。对于科学知识发现，我们假设代理的目标是产生对真实世界的良好描述，即一个能够尽可能准确预测尚未探索的自然现象的世界模型。一个更智能的代理会产生对真实世界分布 $P_{\mathcal{W}}(\mathbf{x})$ 更好的近似。因此，代理的智能可以通过这两个概率分布之间的KL散度或相对熵来衡量：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/3/formula
$$ 
D_{0}(\theta)=\sum_{{\bf x}\subseteq\mathcal{W}}P_{\mathcal{W}}({\bf x})\log\frac{P_{\mathcal{W}}({\bf x})}{P_{\theta}({\bf x})}
 $$
该公式的目的是衡量智能代理的智能程度，通过计算真实世界概率分布 $P_{\mathcal{W}}(\mathbf{x})$ 和代理预测的概率分布 $P_{\theta}(\mathbf{x})$ 之间的KL散度来评估代理的智能表现。KL散度用于衡量两个概率分布之间的差异，代理的智能度量取决于这种差异的大小。  在公式中，$D_{0}(\theta)$ 表示真实世界分布 $P_{\mathcal{W}}(\mathbf{x})$ 和代理预测分布 $P_{\theta}(\mathbf{x})$ 之间的KL散度。其中，$\mathbf{x}$ 表示数据集，$\mathcal{W}$ 表示真实世界的潜在分布。公式中的求和符号 $\sum_{{\bf x}\subseteq\mathcal{W}}$ 表示对所有可能的数据集 $\mathbf{x}$ 进行求和，$P_{\mathcal{W}}({\bf x})$ 表示真实世界分布中数据集 $\mathbf{x}$ 的概率，$P_{\theta}({\bf x})$ 表示代理预测的数据集 $\mathbf{x}$ 的概率。  在论文中，该公式用于评估代理的智能程度，即代理预测与真实世界分布之间的差异程度。$D_{0}(\theta)$ 越小，则代理的预测越接近真实世界的分布，代理的智能性能也就越高。因此，通过计算 $D_{0}(\theta)$，可以量化代理的智能表现，并据此进行智能代理的评估和比较。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/4/text
1. 在智能代理的智能度量中，KL散度如何帮助衡量代理对未知信息的预测准确性以及与现实世界概率分布之间的差异？  2. 代理的智能性如何随着其获取更多相关知识而变化，特别是在KL散度描述的代理预测能力方面如何体现出不断学习和适应的能力？  3. 在假设检验的背景下，如何利用$D_{0}(\theta)$描述$P_{\mathcal{W}}(\mathbf{x})$和$P_{\theta}(\mathbf{x})$之间的差异，以及如何通过$D_{0}(\theta)$的值来评估代理产生更接近现实预测的能力？
$D_{0}(\theta)$描述了$P_{\mathcal{W}}(\mathbf{x})$和$P_{\theta}(\mathbf{x})$之间的差异。更准确地说，在假设检验的背景下，如果我们从$P_{\mathcal{W}}(\mathbf{x})$中抽样$N$次，并将结果与$P_{\theta}(\mathbf{x})$的预测进行比较，将$P_{\mathcal{W}}(\mathbf{x})$误认为$P_{\theta}(\mathbf{x})$的概率按$e^{-N D_{0}(\theta)}$进行缩放。换句话说，具有较低$D_{0}(\theta)$的代理会产生更接近现实的预测。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/5/text
1. 代理的智能度量如何通过KL散度来衡量其对未知信息的预测和现实世界概率分布之间的差异？这种度量方式有何优势和局限性？  2. 为什么在科学知识发现中，代理的智能性可以通过KL散度描述其对已知信息的预测准确性？代理的智能度量如何随着其获得更多相关知识而变化？  3. 在给定的材料合成代理案例中，为什么代理2比代理1具有更高的智能度量？代理2是如何通过第一性原理计算来提高对未知信息的预测准确性的？
例如，考虑两个材料合成代理，它们的目标是了解感兴趣的无机化合物$\mathrm{CaFe_{2}(PO_{4})_{2}O}$是否可合成。这些代理可以预测(1)${\bf x}_{1}=\{\mathrm{CaFe_{2}(PO_{4})_{2}O}$可合成)，以及(2)$\scriptstyle\mathbf{x}_{2}=\{\mathbf{CaFe}_{2}(\mathbf{PO}_{4})_{2}\mathbf{O}$不可合成)。实际上，由于$\mathrm{CaFe_{2}(PO_{4})_{2}O}$是一种天然矿物，$\dot{P}_{\mathcal{W}}(\mathbf{x}_{1})=1$且$P_{\mathcal{W}}(\mathbf{x}_{2})=0$。然而，这种矿物直到2023年10月4日才被报道[参考文献]，在许多LLM的知识截止日期之后；因此，这些代理缺乏这方面的知识。比较起随机猜测的代理1，$P_{\theta_{1}}(\mathbf{x}_{1})=\bar{\alpha}=P_{\theta_{1}}(\mathbf{x}_{1})=0.5$，从而得到$D_{0}(\theta_{1})=\log2$。相比之下，代理2使用第一性原理计算，并发现$\mathrm{CaFe_{2}(PO_{4})_{2}O}$（假设结构为xx [引用：Materials Project ID]）是其竞争对手中能量最低的相[参考]，表明其稳定性。因此，代理2预测$\mathrm{CaFe_{2}(PO_{4})_{2}O}$可能可合成，暗示$P_{\theta_{2}}(\bar{\mathbf{x}}_{1})>0.5>P_{\theta_{2}}(\mathbf{x}_{2})$。因此，$\dot{D}_{0}(\dot{\theta}_{2})=-\log P_{\theta_{2}}(\mathbf{x}_{1})<D_{0}(\theta_{1})$，这意味着代理2对真实世界有着更准确的理解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/6/text
1. 代理如何利用条件概率分布的相对熵来衡量其智能性，特别是在已知信息的基础上生成未知信息时的预测准确性如何体现？  2. 代理在已知数据点和未知部分之间如何划分知识空间，并如何利用KL散度来描述其对真实世界分布的预测准确性？  3. 代理在学习过程中如何通过不断获取相关知识来增强其预测能力，进而提高智能度量的准确性和适应能力？
现在，让我们假设代理已经进行了一些测量，并确定了一些数据点$x_{i}$的具体数值。设$\mathbf{x}_{\mathrm{K}}$表示这些已知数据点的子集，$\mathbf{x}_{\mathrm{U}}$表示其余未知部分。相应地，我们定义所有已知知识的空间为$\kappa$，所有未知信息的空间为$\mathcal{U}$，满足$\mathbf{x}_{\mathrm{K}}\subseteq{\mathcal{K}}$，$\mathbf{x}_{\mathrm{U}}\subseteq\mathcal{U}$，以及$\kappa\cup\mathcal{U}=\mathcal{W}$。例如，在文本生成中，提示文本$\mathbf{x}_{\mathrm{K}}$代表已知信息。然后，语言模型的效率通过其基于$\mathbf{x}_{\mathrm{K}}$生成文本$\mathbf{x}_{\mathrm{U}}$的预测准确性来衡量。更一般地，代理的智能性可通过条件概率分布的相对熵来衡量：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/7/formula
$$ 
D_{\mathrm{K}}(\boldsymbol{\theta},{\bf x}_{\mathrm{K}})=\sum_{{\bf x}\subseteq\mathcal{U}}P_{\mathcal{W}}\left({\bf x}|{\bf x}_{\mathrm{K}}\right)\log\frac{P_{\mathcal{W}}\left({\bf x}|{\bf x}_{\mathrm{K}}\right)}{P_{\boldsymbol{\theta}}\left({\bf x}|{\bf x}_{\mathrm{K}}\right)}
 $$
这个公式用于衡量代理的智能性，即通过条件概率分布的相对熵来评估代理对未知信息的预测准确性。公式中的符号和参数含义如下：  - $D_{\mathrm{K}}(\boldsymbol{\theta},{\bf x}_{\mathrm{K}})$：表示代理的智能度量，即条件概率分布的相对熵。 - $\boldsymbol{\theta}$：代表代理的世界模型参数。 - ${\bf x}_{\mathrm{K}}$：已知数据点的子集，代表代理已经获取的知识。 - ${\bf x}$：代表未知信息的数据点。 - $\mathcal{U}$：表示所有未知信息的空间。 - $\mathcal{W}$：代表整个世界的空间。 - $P_{\mathcal{W}}\left({\bf x}|{\bf x}_{\mathrm{K}}\right)$：代表在给定已知信息${\bf x}_{\mathrm{K}}$的条件下，未知信息${\bf x}$的世界分布概率。 - $P_{\boldsymbol{\theta}}\left({\bf x}|{\bf x}_{\mathrm{K}}\right)$：代表在给定已知信息${\bf x}_{\mathrm{K}}$和世界模型参数$\boldsymbol{\theta}$的条件下，未知信息${\bf x}$的代理预测分布概率。  这个公式的设计旨在衡量代理对未知信息的预测准确性，通过比较代理的预测分布与真实世界分布之间的差异来评估代理的智能程度。在实践中，代理的智能性取决于其世界模型参数和已知信息的存储，通过不断学习和适应新知识来提高智能度量。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/8/text
1. 代理的智能如何通过KL散度来衡量其对未知信息的预测和现实世界概率分布之间的差异？  2. 为什么在科学知识发现中，代理的智能性可以通过KL散度描述其对已知信息的预测准确性，并且智能度量取决于代理的世界模型参数和记忆中的知识？  3. 代理的智能如何随着获得更多相关知识而更依赖于知识增强预测能力，从而反映出其不断学习和适应能力？
在实践中，代理的所有知识都存储在其记忆$M_{t}^{\mathrm{mem}}$中，即$\mathbf{x}_{\mathrm{K}}={\boldsymbol{K}}=M_{t}^{\mathrm{mem}}$，$\mathcal{U}=\mathcal{W}\setminus M_{t}^{\mathrm{mem}}$，我们将代理的智能定义为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/9/formula
$$ 
I Q_{t}^{\mathrm{agent}}\equiv-D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})=-\sum_{\mathbf{x}\subseteq\mathcal{U}}P_{\mathcal{W}}(\mathbf{x}|M_{t}^{\mathrm{mem}})\log\frac{P_{\mathcal{W}}(\mathbf{x}|M_{t}^{\mathrm{mem}})}{P_{\theta}(\mathbf{x}|M_{t}^{\mathrm{mem}})}
 $$
这个公式用于计算代理的智能度量$I Q_{t}^{\mathrm{agent}}$，其目的是衡量代理在预测未知信息时与真实世界概率分布之间的差异。公式中的$D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$表示KL散度，代表两个概率分布之间的差异。$P_{\mathcal{W}}(\mathbf{x}|M_{t}^{\mathrm{mem}})$是基于代理记忆$M_{t}^{\mathrm{mem}}$的真实世界分布的概率，$P_{\theta}(\mathbf{x}|M_{t}^{\mathrm{mem}})$是基于代理世界模型参数$\theta$的预测分布的概率。公式中的求和符号表示对所有可能的$\mathbf{x}$进行求和。  在论文中，这个公式的意义在于量化代理的智能水平，通过衡量其对未知信息的预测准确性。代理的智能度量$I Q_{t}^{\mathrm{agent}}$受到其记忆$M_{t}^{\mathrm{mem}}$和世界模型参数$\theta$的影响。随着代理获取更多相关知识，其智能度量将更多地依赖于知识增强预测能力，反映出代理的学习和适应能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/10/text
1. 代理的智能度量如何通过KL散度来衡量其对未知信息的预测和现实世界概率分布之间的差异？这种度量方法有哪些优势和局限性？  2. 代理的智能性如何随着时间推移而演变，在$t=0$时如何影响智能$I Q_{t}^{\mathrm{agent}}$的主要因素是什么？随着更多相关知识被纳入$M_{t}^{\mathrm{mem}}$，代理的智能度量如何逐渐转变为依赖于$M_{t}^{\mathrm{wm}}$的知识增强预测能力？  3. 代理的智能度量$I Q_{t}^{\mathrm{agent}}$是如何取决于其记忆$M_{t}^{\mathrm{mem}}$和世界模型$M_{t}^{\mathrm{wm}}$的参数$\theta$的？这种依赖关系如何体现出代理的不断学习和适应能力？
换句话说，代理的智能$I Q_{t}^{\mathrm{agent}}$取决于其记忆$M_{t}^{\mathrm{mem}}$和其世界模型$M_{t}^{\mathrm{wm}}$的参数$\theta$。如图12.1所示的示意图。在$t=0$时，当$M_{t}^{\mathrm{mem}}$非常有限或缺乏与新目标科学问题相关的信息时，$I Q_{t}^{\mathrm{agent}}$主要由$M_{t}^{\mathrm{wm}}$的零样本预测能力决定，对应于流体智力。随着时间的推移，随着更多相关知识被纳入$M_{t}^{\mathrm{mem}}$，$I Q_{t}^{\mathrm{agent}}$越来越依赖于$M_{t}^{\mathrm{wm}}$的知识增强预测能力，反映出结晶智力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.1 KL Divergence-based Intelligence Measure/section/11/figure
1. 代理的智能度量如何通过KL散度$D_{\mathrm{K}}$来衡量其对未知信息的预测和真实世界概率分布之间的差异？在知识增强的过程中，代理的智能是如何从流体智能演变为晶体智能的？  2. 在给定世界模型参数空间$\Theta$的情况下，$D_{\mathrm{K,\Theta}}^{\mathrm{min}}$是如何受到不同知识扩展策略的影响的？通过对比$^1M_{t}^{\mathrm{mem}}$和$^{2}M_{t}^{\mathrm{mem}}$，我们能得出什么结论？
图12.1: 代理智能和知识发现的示意图。代理的智能，通过预测和真实世界概率分布之间的KL散度$D_{\mathrm{K}}$来衡量，在时间$t$内随着数据在其记忆$M_{t}^{\mathrm{mem}}$中的积累，从流体智能（对新问题的零猜测预测）逐渐演变为晶体智能（学习后知识增强的预测）。在给定$M_{t}^{\mathrm{mem}}$的情况下，$D_{\mathrm{K}}$在世界模型参数空间$\Theta$内的演变因$\Theta$的不同取值而异，如实线所示的$\theta_{1}$和$\theta_{2}$。参数空间$\Theta$的表达限制由$D_{\mathrm{K,\Theta}}^{\mathrm{min}}$来描述。在给定$\Theta$的情况下，$D_{\mathrm{K,\Theta}}^{\mathrm{min}}$受到不同知识扩展策略的影响，例如$^1M_{t}^{\mathrm{mem}}$和$^{2}M_{t}^{\mathrm{mem}}$，如虚线所示。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.2 Statistical Nature of Intelligence Growth/section
智能代理的智力增长具有统计特性，随着知识的获取而不减。代理的智能水平可以通过扩展记忆并应用新知识来增加。在时间$t+1$，代理的智能由概率公式给出，衡量了新信息对智能的影响。智能的增长取决于实际数据分布与模型预测分布的差异，当新数据更加意外时，智能增长速率更高。研究发现，好奇驱动代理倾向于探索新领域，拓展知识边界，而非仅专注于实现预设目标。这种代理能够在没有外在奖励的情况下学习，开拓人类搜索空间，揭示未知领域的知识。因此，装备好奇驱动代理基本感知和行动工具至关重要，以便探索新的知识领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.2 Statistical Nature of Intelligence Growth/section/0/text
1. 代理的智能增长如何与实际数据分布与模型预测分布的差异相关？这种相关性如何影响代理的智能增长速率？  2. 好奇驱动代理相较于其他代理的特点是什么？为什么说好奇驱动代理倾向于探索新领域，拓展知识边界，而非仅专注于实现预设目标？  3. 在研究中提到探索新知识领域对于代理的重要性，为什么装备好奇驱动代理基本感知和行动工具至关重要？这种装备如何帮助代理开拓人类搜索空间，揭示未知领域的知识？
智能代理的智能在统计意义上是随着获取知识而不减的函数。粗略地说，$I Q_{t}^{\mathrm{agent}}$ 量化了代理获取的知识量以及代理从$M_{t}^{\mathrm{mem}}$中学习后能有效应用该知识的能力。直观地，如果代理在时间$t$获得额外信息，对应于扩大$M_{t}^{\mathrm{mem}}$并缩小$\mathcal{U}$，其智能应该增加。

为了理解这一过程，考虑一个小区域$\Delta\subseteq{\mathcal{U}}$，并研究将来自$\Delta$的数据集$\mathbf{x}_{\Delta}$添加到$M_{t}^{\mathrm{mem}}$的效果。记$\mathcal{U}=\mathcal{U}^{\prime}\cup\Delta$，其中$\mathcal{U}^{\prime}$表示世界的剩余未知部分。时间$t+1$时代理的智能由以下公式给出：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.2 Statistical Nature of Intelligence Growth/section/1/formula
$$ 
I Q_{t+1}^{\mathrm{agent}}\equiv-D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}}\mathbf{x}_{\Delta})=-\sum_{\mathbf{x}^{\prime}\subseteq\boldsymbol{U}^{\prime}}P_{\mathcal{W}}(\mathbf{x}^{\prime}|M_{t}^{\mathrm{mem}}\mathbf{x}_{\Delta})\log\frac{P_{\mathcal{W}}(\mathbf{x}^{\prime}|M_{t}^{\mathrm{mem}}\mathbf{x}_{\Delta})}{P_{\theta}(\mathbf{x}^{\prime}|M_{t}^{\mathrm{mem}}\mathbf{x}_{\Delta})}
 $$
这个公式的目的是计算在时间$t+1$时刻代理的智能水平，记为$I Q_{t+1}^{\mathrm{agent}}$。这个公式通过衡量新信息对智能的影响来评估代理的智能增长情况。公式中涉及到两个概率分布$P_{\mathcal{W}}$和$P_{\theta}$，分别表示实际数据分布和模型预测分布。  在公式中，$D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}}\mathbf{x}_{\Delta})$表示Kullback-Leibler散度，用来衡量两个概率分布之间的差异。公式中的求和符号涉及到对所有可能的$\mathbf{x}^{\prime}$进行求和，其中$\mathbf{x}^{\prime}$是来自世界未知部分$\boldsymbol{U}^{\prime}$的数据。公式中的对数项表示两个概率分布之间的比值。  这个公式的设计旨在量化新数据对代理智能的贡献，通过比较实际数据分布和模型预测分布之间的差异来评估代理的智能增长情况。公式中的期望操作表示在给定先前知识$M_{t}^{\mathrm{mem}}$的情况下，通过新数据集$\mathbf{x}_{\Delta}$获得的平均知识量。  因此，这个公式在论文中的作用是帮助理解代理智能增长的统计特性，以及衡量新信息对代理智能水平的影响。公式的计算结果可以指导代理在学习过程中如何有效地利用新知识，从而提高智能水平。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.2 Statistical Nature of Intelligence Growth/section/2/text
1. $IQ_{t+1}^{agent}$如何通过对$\mathbf{x}_{\Delta}$的概率进行平均化来衡量代理的智能增长，以及这种方法的优势在哪里？  2. 如何理解在给定$M_{t}^{mem}$中的先前知识情况下，通过测量$\Delta$获得平均知识量对于好奇驱动代理的重要性？  3. 在研究中提到的装备好奇驱动代理基本感知和行动工具对于探索新知识领域有何重要性和实际应用意义？
直接比较$I Q_{t}^{\mathrm{agent}}$和$I Q_{t+1}^{\mathrm{agent}}$是具有挑战性的，因为$I Q_{t+1}^{\mathrm{agent}}$通过对$\mathbf{x}_{\Delta}$进行概率$P_{\mathcal{W}}(\mathbf{x}_{\Delta}|M_{t}^{\mathrm{mem}})$的平均化。这个期望代表了在给定$M_{t}^{\mathrm{mem}}$中的先前知识的情况下，通过测量$\Delta$所获得的平均知识量。我们得到：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.2 Statistical Nature of Intelligence Growth/section/3/formula
$$ 
\begin{array}{r}{\displaystyle\sum_{\mathbf{x}\subseteq\Delta}P_{\mathcal{W}}(\mathbf{x}|M_{t}^{\mathrm{mem}})I Q_{t+1}^{\mathrm{agent}}=-\sum_{\mathbf{x}^{\prime}\subseteq\mathcal{U}^{\prime},\mathbf{x}\subseteq\Delta}P_{\mathcal{W}}(\mathbf{x}^{\prime}\mathbf{x}|M_{t}^{\mathrm{mem}})\log\frac{P_{\mathcal{W}}(\mathbf{x}^{\prime}|M_{t}^{\mathrm{mem}}\mathbf{x})}{P_{\theta}(\mathbf{x}^{\prime}|M_{t}^{\mathrm{mem}}\mathbf{x})}}\\ {=I Q_{t}^{\mathrm{agent}}+\displaystyle\sum_{\mathbf{x}\subseteq\Delta}P_{\mathcal{W}}(\mathbf{x}|M_{t}^{\mathrm{mem}})\log\frac{P_{\mathcal{W}}(\mathbf{x}|M_{t}^{\mathrm{mem}})}{P_{\theta}(\mathbf{x}|M_{t}^{\mathrm{mem}})}}\end{array}
 $$
这个公式描述了智能代理在时间$t+1$时的智力水平$I Q_{t+1}^{\mathrm{agent}}$与先前时间$t$的智力水平$I Q_{t}^{\mathrm{agent}}$之间的关系。公式的左侧是关于新信息对智能的影响的概率加权和，右侧是关于先前知识$M_{t}^{\mathrm{mem}}$条件下的条件概率分布之间的相对熵。  在公式中，$\mathbf{x}$代表一组特征，$\Delta$表示特征集合，$P_{\mathcal{W}}(\mathbf{x}|M_{t}^{\mathrm{mem}})$是在给定先前知识$M_{t}^{\mathrm{mem}}$的情况下特征$\mathbf{x}$的实际数据分布的概率，$P_{\theta}(\mathbf{x}|M_{t}^{\mathrm{mem}})$是模型预测的概率。公式中的对数项衡量了实际数据分布与模型预测分布之间的差异，即相对熵。  整个公式的含义在于，智能代理在时间$t+1$的智能水平受到先前知识$M_{t}^{\mathrm{mem}}$条件下新信息的影响，新信息的意外程度越高，智能增长速率越高。通过比较实际数据分布和模型预测分布之间的差异，可以评估智能代理的智能增长情况。这个公式在论文中用于说明好奇驱动代理的特性，即倾向于探索新领域，拓展知识边界，实现超出人类搜索空间的发现，并揭示未知领域的知识。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.2 Statistical Nature of Intelligence Growth/section/4/text
1. 代理的智能增长如何受到实际数据分布与模型预测分布的差异影响？这种影响是如何体现在智能的增长速率上的？  2. 为什么好奇驱动代理倾向于探索新领域、拓展知识边界，而不是仅专注于实现预设目标？这种行为如何有助于代理在没有外在奖励的情况下学习，揭示未知领域的知识？  3. 在探索新知识领域中，为什么装备好奇驱动代理基本感知和行动工具至关重要？这些工具如何帮助代理实现超出人类规划搜索空间的发现？
第二项是$\mathbf{x}_{\Delta}$在$M_{t}^{\mathrm{mem}}$条件概率分布的相对熵，始终为非负。因此，平均而言，随着$M_{t}^{\mathrm{mem}}$随时间获得新知识，$I Q_{t}^{\mathrm{agent}}$是不减的。需要注意的是，$I Q_{t+1}^{\mathrm{agent}}$可以在$M_{t}^{\mathrm{wm}}$内通过$\theta$进一步改进。

有趣的是，时间$t$的智能预期增益取决于实际分布$P_{\mathcal{W}}(\mathbf{x}|M_{t}^{\mathrm{mem}})$与模型预测分布$P_{\theta}(\mathbf{x}|M_{t}^{\mathrm{mem}})$之间的差异。换句话说，在图12.1中，智能增长的速率在新的测量结果更加意外时更高。这一观察将科学家代理（859）确定为一种特殊类型的好奇驱动代理（869），其优先考虑探索而不是开发，以拓展知识边界，深入理解自然。与利用现有知识实现预定义目标的代理不同，好奇驱动代理可以在没有外在奖励的情况下学习（详情见第5.3节），从而实现超出人类规划搜索空间的发现，并揭示未开发领域的知识。这一潜力也强调了装备好奇驱动代理基本感知和行动工具的重要性，这些工具可以被转移到探索新知识领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.3 Intelligence Evolution Strategies/section
智能进化策略是代理智能进化的关键。通过优化参数$\theta$，智能代理最大化其智商$I Q_{t}^{\mathrm{agent}}$，从而最小化与知识库$M_{t}^{\mathrm{mem}}$之间的Kullback-Leibler散度$D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$。这一过程可通过寻找最优参数$\theta_{\mathrm{K},t}^{*}$实现，使得$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$最小化。随着$M_{t}^{\mathrm{mem}}$的扩展，$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$呈单调非增趋势，反映了智能体行动和信息获取的紧密关系。智能体在知识发现过程中可采用不同扩展策略，如随机探索和基于假设的方法，后者通常更有效率。通过迭代优化参数$\theta$和扩展$M_{t}^{\mathrm{mem}}$，智能体逐渐接近完备认知状态，即$D_{\mathrm{K},\Theta}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})=0$。然而，实际中可能存在发现界限，要克服限制需设计自适应世界模型架构、高效的知识扩展策略和充分的行动空间。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.3 Intelligence Evolution Strategies/section/0/text
1. 代理智能在进化过程中如何通过优化参数$\theta$和扩展知识库$M_{t}^{\mathrm{mem}}$来最大化智商$I Q_{t}^{\mathrm{agent}}，并达到完备认知状态$D_{\mathrm{K},\Theta}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})=0$？  2. 在智能体的知识发现过程中，为什么基于假设的扩展策略通常比随机探索更有效率？这种策略如何影响智能代理的行动和信息获取？  3. 为了克服可能存在的发现界限，智能代理需要设计怎样的自适应世界模型架构、高效的知识扩展策略以及充分的行动空间？
扩展已知信息的策略决定了代理智能进化的速度。对于给定的知识库$M_{t}^{\mathrm{mem}}$，参数$\theta$可以在由$M_{t}^{\mathrm{wm}}$的架构表征的世界模型$\Theta$空间中进行优化。最优代理是使$D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$最小化，从而最大化$I Q_{t}^{\mathrm{agent}}$的代理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.3 Intelligence Evolution Strategies/section/1/formula
$$ 
\theta_{\mathrm{K},t}^{*}\equiv\arg\operatorname*{sup}_{\theta}I Q_{t}^{\mathrm{agent}}=\arg\operatorname*{inf}_{\theta}D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})
 $$
这个公式的目的是寻找最优参数$\theta_{\mathrm{K},t}^{*}$，其定义为在智能代理进化过程中最大化智商$I Q_{t}^{\mathrm{agent}}$，即使得代理与知识库$M_{t}^{\mathrm{mem}}$之间的Kullback-Leibler散度$D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$最小化。换言之，公式的作用是在优化参数$\theta$的过程中，使得代理的智商最大化并且尽量减小代理与知识库之间的差异。  在公式中，$\theta_{\mathrm{K},t}^{*}$表示最优参数，$\arg\operatorname*{sup}_{\theta}I Q_{t}^{\mathrm{agent}}$表示在所有可能的$\theta$取值中，找到能够使代理智商最大化的参数；$\arg\operatorname*{inf}_{\theta}D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$表示在所有可能的$\theta$取值中，找到能够使代理与知识库之间的Kullback-Leibler散度最小化的参数。  这个公式在论文中的意义在于指导智能代理通过优化参数$\theta$来提升智商，并与知识库保持一致，从而更好地适应环境和获取信息。通过迭代优化参数$\theta$，智能体可以逐渐接近完备认知状态，即$D_{\mathrm{K},\Theta}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})=0$。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.3 Intelligence Evolution Strategies/section/2/text
1. 如何利用智能进化策略最大化智能代理的智商，同时最小化与知识库之间的Kullback-Leibler散度？这一过程中如何寻找最优参数$\theta_{\mathrm{K},t}^{*}$，使得$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$最小化？  2. 在智能体的知识发现过程中，为什么基于假设的扩展策略通常更有效率？智能体如何通过迭代优化参数$\theta$和扩展$M_{t}^{\mathrm{mem}}$逐渐接近完备认知状态？  3. 在实际应用中，智能体可能面临发现界限的挑战。为了克服这一限制，需要设计哪些措施，如何确保自适应世界模型架构、高效的知识扩展策略和充分的行动空间？
和

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.3 Intelligence Evolution Strategies/section/3/formula
$$ 
D_{\mathrm{K},\Theta}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})\equiv D_{\mathrm{K}}(\theta_{\mathrm{K},t}^{*},M_{t}^{\mathrm{mem}})
 $$
该公式$D_{\mathrm{K},\Theta}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})\equiv D_{\mathrm{K}}(\theta_{\mathrm{K},t}^{*},M_{t}^{\mathrm{mem}})$代表了从$M_{t}^{\mathrm{mem}}$学习后针对这类模型的最小未知量，量化了$\Theta$的表达限制。在给定的模型族$\Theta$中，$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$衡量了基于$M_{t}^{\mathrm{mem}}$解决目标科学问题时残余未知量的最佳预测。换句话说，$M_{t}^{\mathrm{mem}}$中的知识内容被$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(\bar{M}_{t}^{\mathrm{mem}})$所捕获。$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$随着$M_{t}^{\mathrm{mem}}$的扩展是单调非增的，因为它形成了一族单调非增函数$D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$的包络线。这一扩展过程与智能体如何行动和获取信息密切相关，由$M_{t}^{\mathrm{wm}}$驱动，后者确定最优扩展并通过时间$t$的动作$a_{t}\in\mathcal A$执行它。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.3 Intelligence Evolution Strategies/section/4/text
1. $D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$如何量化了参数$\Theta$的表达限制，以及它在解决目标科学问题时的作用是什么？  2. $D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$随着$M_{t}^{\mathrm{mem}}$的扩展呈现怎样的变化趋势？这种变化如何反映了智能体的行动和信息获取策略？  3. 在智能代理的知识发现过程中，为了克服可能存在的发现界限，文中提到了哪些关键因素和策略？这些因素和策略如何有助于智能体逐渐接近完备的认知状态？
在这里，$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$代表了从$M_{t}^{\mathrm{mem}}$学习后针对这类模型的最小未知量，量化了$\Theta$的表达限制。如图12.1所示，$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$形成了函数族$D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$的包络线，其中$\theta$在$\Theta$范围内变化，

对于给定的模型族$\Theta$，$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$衡量了基于$M_{t}^{\mathrm{mem}}$解决目标科学问题时残余未知量的最佳预测。换句话说，$M_{t}^{\mathrm{mem}}$中的知识内容被$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(\bar{M}_{t}^{\mathrm{mem}})$所捕获。可以证明，$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$随着$M_{t}^{\mathrm{mem}}$的扩展是单调非增的，因为它形成了一族单调非增函数$D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$的包络线。这一扩展过程与智能体如何行动和获取信息密切相关，由$M_{t}^{\mathrm{wm}}$驱动，后者确定最优扩展并通过时间$t$的动作$a_{t}\in\mathcal A$执行它（见表1.2）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.3 Intelligence Evolution Strategies/section/5/text
1. 在智能体的知识发现过程中，为什么基于假设的方法相对于随机探索更有效率？这种方法是如何帮助$M_{t}^{\mathrm{mem}}$更快地扩展并导致$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(^{2}M_{t}^{\mathrm{mem}})$的下降速度更快的？  2. 知识发现过程中采用不同策略扩展$M_{t}^{\mathrm{mem}}，最佳的扩展策略应该具备怎样的特征才能导致$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$最陡下降？在设计扩展策略时，如何确保智能体能够更快地接近完备认知状态？  3. 在智能体的知识发现过程中，如何平衡随机探索和基于假设的方法？基于假设的方法相对于随机探索的优势和局限性是什么？如何在实践中选择合适的扩展策略以最大化知识库$M_{t}^{\mathrm{mem}}$的扩展效果？
在知识发现过程中，可以采用不同策略来扩展$M_{t}^{\mathrm{mem}}$。最佳的扩展策略是导致$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$最陡下降的策略。例如，在扩展$M_{t}^{\mathrm{mem}}$时，可以采用两种策略，分别表示为$^1M_{t}^{\mathrm{mem}}$和$^{2}M_{t}^{\mathrm{mem}}$。第一种策略$^1M_{t}^{\mathrm{mem}}$代表随机探索，而第二种策略$^{2}M_{t}^{\mathrm{mem}}$采用基于假设的方法，在这种方法中，智能体首先对目标问题的潜在机制提出假设，然后设计实验来验证或证伪这一假设。相对于随机探索，这种方法通常更有效率，能够使$M_{t}^{\mathrm{mem}}$更快地扩展，导致$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(^{2}M_{t}^{\mathrm{mem}})$的下降速度快于$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(^{1}M_{t}^{\mathrm{mem}})$。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.1 Agent's Intelligence for Scientific Knowledge Discovery/12.1.3 Intelligence Evolution Strategies/section/6/text
1. 知识发现过程中的发现界限是如何定义的？它与智能体的认知完备性有何关系？  2. 在智能体迭代优化参数$\theta$和扩展$M_{t}^{\mathrm{mem}}$的过程中，如何设计高效的知识扩展策略以加速$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$的减少？  3. 为了克服知识发现过程中的发现界限，智能体需要采取哪些措施来设计自适应世界模型架构和充分的行动空间？
通常，知识发现过程是迭代进行的，反复优化世界模型参数$\theta$以接近$\theta_{\mathrm{K},t}^{*}$，并以理性的方式扩展$M_{t}^{\mathrm{mem}}$，加速$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$的减少。理想状态是实现认识完备性，即$D_{\mathrm{K},\Theta}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})=0$，表示智能体的预测与真实世界现象之间没有差异。然而，对于特定智能体，可能存在一个发现界限，即$D_{\mathrm{K},\Theta}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$接近零但仍保持正值。这些差异源于实际约束条件、$\Theta$、$\mathcal{A}$以及智能体的其他设计空间的限制。实现较低的发现界限需要设计一种自适应世界模型架构、高效的知识扩展策略以及充分的行动空间。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/section
代理-知识交互是智能代理领域的关键议题，涉及代理如何自主发现和利用知识来增强自身。科学知识形式包括观察、方法论和伦理知识，对提高代理性能具有重要作用。代理通过假设生成与检验、协议规划与工具创新以及数据分析与含义推导三种情景来增强自身。在假设生成与检验中，代理根据部分可观测信息提出高价值假设，通过实验或计算进行测试，快速促进知识发现。协议规划与工具创新使代理能够解决复杂科学问题，提高执行效率。数据分析与含义推导则通过演绎和归纳推理获取知识，强调可靠数据分析和推理工具的重要性。这些交互方式使代理能够不断更新心智状态，提高决策能力，推动科学知识的发现与应用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/section/0/text
1. 科学知识形式中的观察知识、方法论知识和伦理知识如何影响未知信息概率分布和减少不确定性的过程？    2. 代理在假设生成与检验、协议规划与工具创新以及数据分析与含义推导三种情景中如何利用不同的科学知识形式来提高自身性能和决策能力？    3. 在智能代理领域中，如何通过不断更新心智状态和利用多种科学知识形式推动科学知识的发现与应用？
典型的科学知识形式包括观察知识（例如实验测量、计算结果）、方法论知识（例如实验方法、计算技术、协议）和伦理知识（例如理论、法则、预测模型）。只要这些知识形式包含以影响未知信息概率分布 $P_{\theta}\left(\mathbf{x}_{\mathrm{U}}|M_{t}^{\mathrm{mem}}\right)$、减少 $D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$，并促进决策的方式处理的数据和信息，它们就可以促进科学理解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/section/1/text
1. 代理如何能够自主地发现和利用知识来增强自身，以推动科学知识的发现与应用？ 2. 在代理发现科学知识并增强自身的过程中，假设生成、协议规划、数据分析等步骤如何相互作用，促进代理性能的提升？ 3. 代理通过何种方式利用应用程序编程接口（API）与物理仪器进行交互，以获取科学知识并更新其心智状态，从而做出更好的决策？
原则上，已经证明外部科学知识对改善推理和决策中的代理性能是有用的。然而，本调查的范围在于代理如何能够自主地发现和利用知识来增强自身。科学知识发现工作流通常涉及假设生成、协议规划、实验和计算、数据分析、推导含义，并修订假设，通常作为迭代循环的一部分。一个能够感知、学习、推理和行动的代理有潜力以自主方式推动这种工作流，例如通过使用应用程序编程接口（API）与物理仪器进行交互以获取科学知识并迭代增强其知识库（图12.2）。代理将利用获取的知识来更新其心智状态 $M_{t}$，以在与世界 $\mathcal{W}$ 互动时做出更好的决策。接下来，我们将重点介绍代理发现科学知识并增强自身的三种情景。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/section/2/figure
1. 代理在可持续自我进化的闭环知识发现中如何利用假设生成和测试以及数据分析和推导来增强其智能？     2. 代理在与物理世界交互时是如何生成假设、测试、观察实验结果并更新信念的？
图12.2：可持续自我进化的闭环知识发现。代理通过假设生成和测试以及数据分析和推导来迭代地增强其智能$I Q_{t}^{\mathrm{{agent}}} $。当与物理世界$W$交互时，代理生成假设作为未知信息的明示或隐含预测分布$(P_{\theta})$，采取行动$(a_{t})$进行假设测试，观察实验结果$(o_{t})$，并基于对真实世界分布$(P_{W})$的感知更新信念。当未与$W$交互时，代理从现有数据和前提中提炼知识，直接更新心智状态$M_{t}$。受[864]中图2.3和2.5的启发。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.1 Hypothesis Generation and Testing/section
在智能代理的研究中，假设生成与检验是关键的科学发现应用之一。科学假设必须是可证伪的，并在证伪中存活的假设被定义为合理的真实假设。代理根据对部分可观测世界的信息提出高价值假设，通过实验或计算测试这些假设。生成具有物理意义的假设是一个重要步骤，通常利用LLMs与协作架构和领域知识进行假设生成。研究表明，代理通过生成和测试高价值假设可以快速促进知识发现。发现的知识增强了代理的心智状态，如记忆，进而提高化学推理能力和药物发现效率。奖励函数设计在发展面向未来的自主实验工作流程中发挥关键作用，而发现新知识可以作为改进奖励函数、引导假设探索和实验数据收集的重要资源。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.1 Hypothesis Generation and Testing/section/0/text
1. 在智能代理的自主科学发现中，为什么假设生成和测试被认为是关键的应用？这种方法如何促进创新思维？  2. 根据卡尔·波普尔爵士的观点，为什么科学假设必须是可证伪的？在代理的假设生成过程中，如何定义合理的真实假设？  3. 在科学假设生成和测试过程中，当一个假设能够解释广泛范围的数据并被证实可能是真实的时，为什么该假设被认为更有价值？
假设生成和测试（图12.2）是代理在自主科学发现中的一个关键应用，因为它有潜力促进创新思维[749]。实质上，假设生成是形成潜在规则的过程，这些规则控制着与未观察到的科学现象相关的数据分布——从单个观察结果到大型数据集。根据卡尔·波普尔爵士的说法，科学假设必须是可证伪的[875,876]；在本讨论中，我们将幸存于证伪之中的假设定义为合理的真实假设[877860]。通常，科学家通过进行实验来测试假设，以证明或证伪它们。如果一个假设足够广泛以解释广泛范围的数据，并且极有可能是真实的，那么它被认为更有价值。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.1 Hypothesis Generation and Testing/section/1/text
1. 代理如何根据对部分可观测世界的信息提出高价值假设，并通过实验或计算测试这些假设来促进知识发现？ 2. 为什么在智能代理研究中，生成和测试高价值假设被认为是快速增加知识发现和提高代理智力状态的关键步骤？ 3. 代理是如何利用学习函数$\mathrm{L}$，将假设测试的观察$o_{t}$处理为知识，并更新其心智状态$M_{t}$的？
为解决科学问题，代理根据其关于部分可观测世界$\mathcal{W}$的不完整信息所包含的心智状态$M_{t}$，提出一个或少数几个基于高价值的假设。经过实验或计算测试后，一个经证明为真的假设成为有益的知识，扩展$M_{t}^{\mathrm{mem}}$，从而迅速减小$D_{\mathrm{K,\Theta}}^{\mathrm{min}}(M_{t}^{\mathrm{mem}})$。因此，生成和测试高价值假设可以快速促进知识发现并增加$I Q_{t}^{\mathrm{agent}}$。在这种情况下，代理采用学习函数$\mathrm{L}$，将假设测试的观察$o_{t}$处理为知识，并更新其心智状态$M_{t}$。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.1 Hypothesis Generation and Testing/section/2/text
1. 如何利用LLMs与协作架构和领域知识进行假设生成，以促进代理的知识发现和提高化学推理能力？  2. 在代理生成和测试高价值假设的过程中，如何通过SciAgents等工具构思、扩展和完善材料科学假设，以揭示生物启发材料的基本机制和设计原则？  3. 代理如何通过团队合作、协作讨论和代理批评，以及LGEM+等工具自动背推改进生成大量独特的科学假设，从而提高药物发现效率和知识发现速度？
生成具有物理意义的假设是一个关键步骤。代理通常利用LLMs与协作架构和领域知识进行假设生成[878]。Siet al.[742]进行了一项涉及100多名NLP研究人员的大规模人类研究，发现LLM生成的想法在新颖性上评分更高（p<0.05）而在可行性上略微弱。Ghafarollahiet al.[743]开发了SciAgents，用于生成和完善材料科学假设，以阐明生物启发材料的基本机制、设计原则和意想不到的特性。基于大规模本体知识图，SciAgents在感兴趣的概念之间采样一个可行路径，构思一个相关的假设，并将其扩展为一个具有详细假设测试方法和标准的完整研究提案。它利用两个专门的代理人来审查、批评和改进所提出的假设，但不包括通过实际实验进行假设测试的步骤。类似地，Suet al.[879]和Baek等人[880]提出利用团队合作，如协作讨论和代理批评，以产生新颖且有效的科学假设。此外，Gower等人[881]引入了LGEM+，它利用一阶逻辑框架描述生物化学途径，并为酵母S. cerevisiae的基因组规模代谢模型的自动背推改进生成了2,094个独特的候选假设。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.1 Hypothesis Generation and Testing/section/3/text
1. AI科学家、Agent Laboratory和Genesis等自动化系统在科学发现中的应用如何促进了知识的快速发现和推进？  2. 在智能代理研究中，如何利用生成和测试高价值假设的方法来增强代理的心智状态，提高化学推理能力和药物发现效率？  3. 在科学发现中，如何设计奖励函数以引导假设探索和实验数据收集，从而促进未来自主实验工作流程的发展？
假设只有通过计算或实验观察得到证实后才能成为知识。Lu等人引入了AI科学家，这是一个旨在完全自动化科学发现的系统。AI科学家可以独立进行研究并传达其发现，如在扩散建模、基于Transformer的语言建模和学习动态领域所展示的。它生成原创研究思路，撰写代码，执行计算实验，可视化结果，起草完整的科学论文，甚至模拟同行评审过程以进行评估。例如，它提出了“自适应双尺度去噪可以通过在生成的样本中平衡全局结构和局部细节来改进扩散模型”的假设，通过对四个2D数据集进行图像生成测试得到证实。类似地，Schmidgal等人开发了Agent Laboratory，可以自主进行整个研究过程，包括文献回顾、计算实验和报告撰写。他们通过解决计算机视觉和自然语言处理领域的五个研究问题来评估Agent Laboratory在知识发现方面的能力，取得了平均人工评估实验质量得分为3.2（满分5分）。此外，Tiukova等人开发了Genesis，这是一个自动化系统，能够控制一千个微生物反应器，执行质谱表征，访问结构化领域信息数据库，并将实验观察应用于改进系统生物学模型。Genesis每天可以发起和执行1000个以假设为驱动的封闭循环实验周期。采用类似方法，Genesis团队已经推进了酵母（S.cerevisiae）二态转换模型，优于之前的最佳模型，并通过增加92个基因（+45%）和1048个相互作用（+147%）扩展了知识。这些知识也推进了我们对癌症、免疫系统和衰老的理解。类似地，Gottweis等人介绍了AI共同科学家，它可以自主生成和完善在药物再利用、新靶点发现以及细菌进化和抗微生物耐药机制等三个生物医学领域的新研究假设，并进行体外验证。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.1 Hypothesis Generation and Testing/section/4/text
1. 如何通过动态的、自我更新的记忆$M_{t}^{\mathrm{mem}}$来提高智能代理的化学推理能力，以及在化学问题回答中如何利用这种记忆支持未来的假设生成和实验数据收集？  2. 在ChemAgent和MOLLEO等方法中，如何利用代理的自我更新的记忆$M_{t}^{\mathrm{mem}}$来快速提出并评估假设，以促进药物发现和无机光伏材料设计的效率？  3. 代理如何通过假设引导的结构生成和自我更新的记忆$M_{t}^{\mathrm{mem}}$来设计无机光伏材料，以匹配目标带隙和最大负形成能为目标？
发现的知识增强了代理的心智状态，如$M_{t}^{\mathrm{mem}}$，$M_{t}^{\mathrm{wm}}$和$M_{t}^{\mathrm{rew}}$。唐等人开发了ChemAgent，通过动态的、自我更新的记忆$M_{t}^{\mathrm{mem}}$来提高化学推理能力。ChemAgent在一个开发数据集中针对化学问题提出假设答案，评估其与真实情况的一致性，并模拟现实世界研究中使用的假设检验过程。正确答案随后被存储为知识在其记忆中，以支持未来的化学问题回答。这种自我更新的记忆使ChemAgent在应用于SciBench的四个化学推理数据集时性能提升高达46%（使用GPT-4）。王等人引入了分子语言增强进化优化（MOLLEO），该方法迭代地提出修改候选药物分子的假设，评估其药物样性和活性，并在$M_{t}^{\mathrm{mem}}$中更新候选物质以增强药物发现。类似地，贾等人开发了LLMatDesign，采用假设引导的结构生成和自我更新的$M_{t}^{\mathrm{mem}}$来设计无机光伏材料，其理想性由匹配目标带隙和具有最负形成能确定。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.1 Hypothesis Generation and Testing/section/5/text
1. ChemOS 2.0系统如何结合了从头计算、实验编排和统计算法，以实现自主发现高性能材料的目标？    2. 在ChemOS 2.0系统中，贝叶斯优化器Altas如何被用于预测假设分子的光学特性，并如何帮助选择在实验活动中成功概率较高的分子？  3. 发现案例中，ChemOS 2.0是如何利用光学表征平台和AiiDA软件包来测量和模拟测试分子的性质，并如何通过这些结果提高未来实验预测的准确性？
Sim等人[748]引入了ChemOS 2.0，该系统在化学自动驾驶实验室（SDLs）中进行闭环操作的编排。ChemOS 2.0整合了从头计算、实验编排和统计算法，用于自主发现高性能材料。一个有机激光分子的发现案例展示了其能力。它采用贝叶斯优化器Altas作为其世界模型$M_{t}^{\mathrm{wm}}$，用于预测假设分子的光学特性，具体包括双[(N-碳基)亚基]联苯（BSBCz）衍生物的增益截面和光谱增益因子。基于这些预测，ChemOS 2.0推荐在实验活动中成功概率较高的分子。然后利用光学表征平台和AiiDA软件包来测量和模拟测试分子的性质。结果用于更新$M_{t}^{\mathrm{wm}}$，提高未来实验预测的准确性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.1 Hypothesis Generation and Testing/section/6/text
1. 在科学研究中，奖励函数设计在发展面向未来的自主实验工作流程中的关键作用是如何体现的？它如何影响代理的学习和知识发现能力？  2. 为什么在真实世界的科学研究问题中，奖励函数往往在实验活动结束时会被定义不清晰或缺失？这种情况可能对代理的学习和决策产生什么影响？  3. 如何利用发现的新知识来改进奖励函数、引导假设探索和实验数据收集？这种方法对于代理在复杂环境中的表现有何重要性？
Hysmith等人[886]发表了一篇观点文章，强调了奖励函数设计在发展面向未来的SDL工作流程中的关键作用。在模拟环境中，如电脑游戏或模拟中，代理可以高效解决POMDP问题，但往往难以应用于真实世界的场景。一个明确定义的奖励函数对于迭代式自我进化至关重要。然而，在许多真实世界的科学研究问题中，由于缺乏直接测量、实验结果复杂性以及需要平衡多个目标，奖励函数往往在实验活动结束时被定义不清晰或缺失。发现新知识可以作为改进$M_{t}^{\mathrm{rew}}$、引导假设探索和实验数据收集的宝贵资源。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.2 Protocol Planning and Tool Innovation/section
在"协议规划与工具创新"章节中，代理程序通过规划实验方案和优化工具使用，能够解决复杂科学问题。优化方案和工具使用虽不能直接影响知识的精炼，但提高了执行效率，加速了知识发现的过程。代理程序利用推理功能不断更新新知识，转化为更有效的现实行动。安排和协调工具的选择和重组至关重要，代理程序需学会整合和适应地使用各种仪器。通过设计模块化工作流程，Dai等人展示了移动机器人在化学领域的自主发现能力。Strieth-Kalthoff等人跨越多个实验室，利用云计算和实验计划器推动了科学发现的民主化。此外，Swanson等人开发了Virtual Lab，结合人工智能和实验验证，成功设计了新型SARS-CoV-2纳米抗体，展示了代理优化工具和创新的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.2 Protocol Planning and Tool Innovation/section/0/text
1. 代理程序如何通过规划实验方案和优化工具使用，解决复杂科学难题的过程中，如何提高执行效率和加速知识发现的过程？  2. 代理程序在自主发现循环中如何评估和完善工具选择、调用和整合方法，甚至开发出符合特定任务需求的新工具？这种方法如何影响知识的精炼和加速未知信息的概率分布的精炼？  3. 代理程序如何利用推理功能不断更新新知识，并将其转化为更有效和更快的假设检验的现实行动？这种过程如何促进代理程序在解决复杂科学难题中的效率和成效？
在能够规划实验方案并优化工具使用的能力下，代理程序能够在自主发现循环中解决复杂的科学难题。正如第9.4节中介绍的那样，代理程序可以系统地评估和完善其选择、调用和整合可用工具的方法，甚至开发出符合特定任务需求的新工具。虽然优化的方案和工具使用并不能直接降低 $\bar{D}_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$，但它们提高了执行效率和效果，从而加速未知信息的概率分布 $\dot{P}_{\theta}\left(\mathbf{x}_{\mathrm{U}}|M_{t}^{\mathrm{mem}}\right)$ 的精炼，进而加快知识发现。在这种情况下，代理程序利用推理功能 $\mathrm{R}$ 将其不断更新的新知识反映在心智状态 $M_{t}$ 中，转化为更有效和更快的假设检验的现实行动 $a_{t}$（见图12.2）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.2 Protocol Planning and Tool Innovation/section/1/text
1. 代理程序如何通过整合和适应地使用各种仪器，提高科学实验的执行效率和加速知识发现的过程？ 2. Dai等人设计的模块化工作流程如何帮助移动机器人在化学领域实现自主发现能力，以及这种系统在不同化学领域的应用展示了什么特点？ 3. 移动机器人如何在合成-分析-决策循环中模仿人类实验策略，选择适当的仪器进行合成和测量，从而推动科学实验的发展？
安排和协调选择和重组现有工具是至关重要的。科学实验通常依赖于各种仪器来分析反应产物，决策很少仅依赖于单一测量。在不浪费资源和时间的情况下有效利用必要的仪器，需要代理程序学会以一种整合和适应的方式使用工具。Dai等人设计了一个模块化工作流程，集成了移动机器人、自动合成平台和各种表征仪器，用于自主发现。他们在结构多样化化学、超分子主客体化学和光化学合成三个领域展示了这一系统。移动机器人遵循合成-分析-决策循环，模仿人类实验策略，自主确定后续工作流程步骤。它选择适当的仪器，例如Chemspeed ISynth平台用于合成，液相色谱-质谱仪（UPLC-MS）用于测量与化学峰信号相对应的质谱，以及台式核磁共振谱仪（NMR）用于跟踪起始物到产物的化学转化过程。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.2 Protocol Planning and Tool Innovation/section/2/text
1. 工具编排在非集中和异步科学发现中的作用是什么？Strieth-Kalthoff等人是如何通过跨越多个实验室展示这一点的？ 2. 为何跨越不同实验室进行闭环集成对于推动科学发现的民主化至关重要？Strieth-Kalthoff等人的方法如何体现了这种民主化？ 3. 通过基于云的实验计划器学习并优先考虑信息量大的实验，Strieth-Kalthoff等人是如何成功发现新的用于有机固态激光器的材料的？
超越单个实验室，工具编排对于非集中和异步科学发现至关重要。Strieth-Kalthoff等人展示了跨越三大洲的五个材料科学实验室的闭环集成，推动了非集中化和民主化的科学发现。这五个实验室各有所长——例如，不列颠哥伦比亚大学专注于连续优先结晶，而九州大学擅长薄膜制备和表征。Strieth-Kalthoff等人采用基于云的实验计划器，持续从传入数据中学习并有效地优先考虑五个实验室中具有信息量的实验，从而发现了21种新的用于有机固态激光器的最新材料。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.2 Protocol Planning and Tool Innovation/section/3/text
1. 人工智能代理在Virtual Lab中如何促进了新型SARS-CoV-2纳米抗体的设计和实验验证？ 2. 代理程序开发的序列分析工具、结构评估工具和能量估算工具在哪些方面提升了Virtual Lab的功能？ 3. 在化学领域中，代理程序如何通过优化现有工具和创建新工具来加速知识发现的过程？
此外，代理还可以优化现有工具，甚至创建新工具以增强其功能。Swanson等人开发了Virtual Lab，这是一个由人工智能驱动的研究环境，促进了新型SARS-CoV-2纳米抗体的设计和实验验证。在Virtual Lab中，人工智能代理在团队会议中进行科学讨论，并在个别会话中执行专门任务。代理的一个重要议程是开发工具，以辅助设计纳米抗体结合物[887]，包括：(1) 一种序列分析工具，利用来自ESM蛋白语言模型的对数似然比对候选点突变进行排序；(2) 一种结构评估工具，从AlphaFold-Multimer预测中提取界面pLDDT分数，为抗体-抗原结合亲和力提供代理；以及(3) 一个基于Roseta的能量估算工具，用于量化纳米抗体变体与刺突蛋白之间的结合强度。这些代理生成的工具使Virtual Lab能够发现两种新型纳米抗体，其对JN.1或KP.3SARS-CoV-2变体具有增强结合能力，同时保持对祖先病毒刺突蛋白的强亲和力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.3 Data Analysis and Implication Derivation/section
在数据分析与含义推导方面，知识获取不仅依赖于实证测试，还可通过内部推理获得。演绎推理通过逻辑推导新知识，AlphaGeometry成功利用神经语言模型和符号引擎扩展欧几里得几何定理，表现出色。另一方面，归纳推理则通过模式识别和统计学习实现知识推导，如TAIS团队在数据科学中的应用。虽然数据分析可能带来有意义的发现，但数据覆盖范围和算法实施限制可能导致虚构见解，强调了可靠的数据分析器和推理工具的重要性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.3 Data Analysis and Implication Derivation/section/0/text
1. 在知识获取中，演绎推理和归纳推理各自的优势和局限性是什么，它们如何相互补充以帮助减少假设的不确定性？  2. 论述内部推理在知识获取中的作用，以及代理如何利用认知函数和内部行为推导新知识的过程。  3. 如何利用演绎和归纳推理从已知前提和数据中得出推论，以帮助证实或推翻假设，并最终增强代理的智能水平？
尽管大多数知识发现过程依赖于提出假设并在现实世界中进行测试，其中观察值 $o_{t}$ 至关重要，但是相当一部分知识可以纯粹通过内部行为（如迭代推理和深入思考）获取，这在理论学科中很常见。例如，欧几里得几何中的所有定理都可以从仅有的五条公设推导出来，但在推导之前，这些定理在心智状态中并不存在。在给定所有必要前提条件（如欧几里得的五条公设）的情况下，假设的真实概率可能仍然难以捉摸。然而，利用演绎和归纳推理从已知前提和数据中得出推论可以帮助证实或推翻假设，从而减少 $D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$ 并增强 $I Q_{t}^{\mathrm{agent}}$（见图12.2）。在这种情况下，代理利用认知函数 C，利用先前的心智状态 $M_{t-1}$ 和内部行为 $a_{t}$ 推导新知识，并更新心智状态为 $M_{t}$。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.3 Data Analysis and Implication Derivation/section/1/text
1. AlphaGeometry是如何利用神经语言模型和符号引擎扩展欧几里得几何定理的？ 2. 在Trinh等人的研究中，AlphaGeometry如何通过演绎推理实现知识推导，并取得了怎样的成绩？ 3. 在数据分析中，为什么强调可靠的数据分析器和推理工具的重要性？
演绎推理通过逻辑实现知识推导。Trinh等人开发了AlphaGeometry[753]，用于基于欧几里得平面几何中现有定理的前向推导新数学定理。AlphaGeometry采用神经语言模型构建平面几何问题中的辅助点，并整合专门的符号引擎，通过详尽推导新的真命题，从而扩展已知真相的联合闭包。通过利用这一扩展闭包，它在辅助构造和符号推理引擎之间交替，揭示进一步的含义。AlphaGeometry在一个包含30个最新奥林匹克水平问题的测试集上表现出色，解决了25个问题，是之前最佳方法解决的10个问题的两倍以上，并接近平均国际数学奥林匹克（IMO）金牌得主的水平。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.2 Agent-Knowledge Interactions/12.2.3 Data Analysis and Implication Derivation/section/2/text
1. TAIS团队如何利用模式识别和统计学习来实现数据分析的流程化，以从复杂数据集中提取有意义的见解？ 2. 在疾病预测基因识别方面，TAIS团队在基准数据集上取得的总体成功率为45.73%，这一结果如何反映了归纳推理的有效性和局限性？ 3. 数据覆盖范围的限制和分析算法的实施可能导致虚构的见解，为了确保准确发现能够安全地融入思维状态，可靠的数据分析器和推理工具的重要性体现在哪些方面？
归纳推理通过模式识别和统计学习实现知识推导。Liu等人[754]引入了人工智能科学家团队(TAIS)，以模拟数据科学家的角色，实现数据分析的流程化。TAIS将复杂的数据分析问题分解为不同的计算任务，包括编码、自我批判和回归分析，以从复杂数据集中提取有意义的见解。当应用于识别疾病预测基因时，TAIS在包含457个遗传问题的基准数据集上取得了总体成功率为45.73%。理想情况下，提取的见解应该在逻辑上合理；否则，它们必须被丢弃，以确保只有准确的发现能够安全地融入思维状态。然而，数据覆盖范围的限制和分析算法的实施可能导致虚构的见解，凸显了需要可靠的数据分析器和推理工具来防止过度分析。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/section
智能代理的自我演化在推动人类知识进步方面发挥着重要作用，但目前面临着技术准备度方面的挑战。在现实世界互动方面，缺乏直接在物理实验室执行任务的APIs限制了代理系统的自主知识发现能力。复杂推理方面，LLMs驱动的代理在处理复杂逻辑和数值问题时表现不佳，需要更多支持因果推断的发展。至于整合先验知识，当前的LLMs无法涵盖所有知识来源，整合多样化知识面临着困难。因此，未来需要进一步技术进步以改善自驱动创新的循环，特别是在现实世界互动、复杂推理和先验知识整合方面。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/section/0/text
1. 如何当前技术准备水平的局限影响智能代理系统在现实世界互动、复杂推理和先验知识整合方面的自主知识发现能力？  2. 在智能代理的自我演化过程中，为何实现完全自主的自我演化仍然是一个重大挑战？这与技术准备水平在现实世界互动、复杂推理和先验知识整合方面的局限有何关系？  3. 未来如何通过技术进步来改善智能代理系统的自驱动创新循环，特别是在现实世界互动、复杂推理和先验知识整合方面的挑战？
智能代理的自我演化，从而推动人类知识的进步，在创新周期的早期成功中得以实现。这一周期包括生成有意义的假设、设计实时测试协议、协调各种实验和计算工具、分析数据、得出结论，并进行自我反思。然而，实现完全自主的自我演化仍然是一个重大挑战，鉴于当前技术准备水平（TRL）在三个基本能力方面存在局限：现实世界互动、复杂推理和先验知识的整合。需要进一步的技术进步以改善自驱动创新的循环。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.1 Real-World Interaction Challenges/section
智能代理通过应用程序接口与现实世界互动，但缺乏直接在物理实验室执行任务的APIs是一个关键挑战。物理APIs的开发需要大量时间、专业知识和成本投入，限制了代理系统的自主知识发现能力。操作实验室设备和样本传输是关键任务，需要跨学科努力将实验仪器转变为代理可访问系统。两种集成方法包括直接设备适配和机器人操作，前者成本高、耗时长，需要专业知识，而后者通过移动机器人或机械手操作设备，但仍需人类预先编程。未来，结合两种方法和发展体现式人工智能的机器人系统，有望促进实验室自动化，并解决实验设备定制和自适应操作的挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.1 Real-World Interaction Challenges/section/0/text
1. 如何缺乏直接在物理实验室执行任务的APIs影响智能代理系统的自主知识发现能力？   2. 在当前阶段，为什么直接复制或扩展现有的自主实验室系统具有挑战性？   3. 未来如何结合直接设备适配和机器人操作两种集成方法，以促进实验室自动化并解决实验设备定制和自适应操作的挑战？
智能代理主要通过应用程序接口（APIs）与现实世界进行交互。尽管许多演示已经展示了它们利用各种API的强大能力，但在自主知识发现方面仍存在一个重要瓶颈：缺乏允许代理直接在物理实验室执行任务的APIs。物理APIs——能够直接控制实验室设备的接口相对较少，这是因为开发这些接口需要大量的时间、专业知识和成本投入。尽管现有的自主实验室显示出了潜力，它们仍处于早期发展阶段（通常是TRL 4-6），在这个阶段，直接复制或扩展规模是具有挑战性的。因此，进一步构建系统或将其应用扩展到额外的科学领域仍需要大量定制以解决特定领域需求，以及专门的专业知识。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.1 Real-World Interaction Challenges/section/1/text
1. 如何跨越多个学科领域的努力，将最初为人类操作设计的实验仪器转变为代理可访问的系统，以促进实验室自动化？ 2. 在实现物理硬件与实验样本的无缝集成过程中，直接设备适配和机器人操作两种方法各有何优劣，如何结合利用以解决实验设备定制和自适应操作的挑战？ 3. 在自主实验室中，为何需要并行且互补的两种集成方法来将硬件与代理系统集成？这两种方法的模块化和可重构性如何影响实验室自动化的发展？
实现现实世界交互的两个关键任务是操作实验室设备和在设备之间传输样本。无缝集成物理硬件和实验样本对于保持工作流程的连续性至关重要。然而，大多数实验仪器最初是为人类操作而设计的。使它们对代理可访问需要跨越多个学科的广泛努力，包括机器人技术、电气工程、机械工程和软件编程。自主实验室的日益突出促使人类操作的设备通过APIs转变为代理可访问的系统。在进行复杂实验的自主实验室中，通常采用两种并行且常常互补的方法来将硬件与代理系统集成。这两种方法都是模块化、可重构且有价值的，但它们需要持续的专门开发。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.1 Real-World Interaction Challenges/section/2/text
1. 如何通过直接设备适配实现API集成，以解决智能代理在物理实验室执行任务时面临的挑战？这种方法的优势和劣势是什么？  2. 在实验室自动化领域，为什么直接设备适配方法虽然能够最大化设备利用率和优化资源，但仍存在成本高、耗时长以及需要专业知识等方面的限制？  3. 未来如何结合直接设备适配和机器人操作两种集成方法，发展体现式人工智能的机器人系统，以促进实验室自动化并解决实验设备定制和自适应操作的挑战？
方法一：通过直接设备适配实现API集成。这种方法涉及为单个设备配备专用的机械适配器和I/O控制器，使它们能够接收并执行来自中央控制PC的命令。例如，为了实现无机材料的固态合成和结构表征，A实验室已经实施了16种设备，用于自动化实验任务，如粉末投料、加热和衍射。这种方法允许实验室作为完全集成的实体运作，通过最大化设备利用率、优化空间和资源，并实现定制工具。然而，这种方法成本高、耗时长，并且需要专业知识来为自动化原型化或改装设备。大型语言模型(LLMs)已被应用于促进对各种工具的访问，如化学代理连接工具使用到科学中的CACTUS。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.1 Real-World Interaction Challenges/section/3/text
1. 云实验室在推动实验室自动化方面有哪些优势和局限性？对于需要设备定制的研究人员来说，使用云实验室可能存在哪些挑战？  2. 在实现实验室设备自适应操作的过程中，直接设备适配和机器人操作两种集成方法各有何优缺点？结合两种方法可能如何提升实验室自动化水平？  3. 如何评价将实验室设备工程责任转移到专门的用户设施或商业服务提供商的做法？这种转变可能对小团队实验室操作和研究活动带来哪些影响？
对于小团队来说，更具可访问性的选择是云实验室或科学工厂[894]，在这里，设备工程的责任从单个实验室转移到专门的用户设施或商业服务提供商。例如，Boiko等人[895]展示了一种自主化学研究代理人Coscientist，能够在Emerald Cloud Lab的实验设置中执行交叉偶联Suzuki和Sonogashira反应。然而，云实验室仅提供针对常见程序优化的固定设备集，这对那些需要设备定制的研究人员可能构成潜在挑战，因为整合非标准工具可能涉及漫长的谈判和开发过程。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.1 Real-World Interaction Challenges/section/4/text
1. 机器人操作实验设备中存在的挑战是什么，以及如何解决这些挑战可以促进实验室自动化的发展？ 2. 当前机器人系统在实验室操作中仍然依赖人类预先编程，这种依赖性如何影响代理系统的自主知识发现能力？ 3. 未来如何结合机器人操作和直接设备适配两种方法，以发展体现式人工智能的机器人系统来解决实验设备定制和自适应操作的挑战？
方法二：实验设备的机器人操作。这种方法涉及使用移动机器人或机械手来操作现有设备并转移样本。在许多情况下，机器人可以与仪器互动而无需修改，除了进行一些小的调整，例如添加专门的执行器、夹持器或支架。例如，Dai等人利用移动机器人探索合成化学。在他们的自主实验室中，移动机器人实现了合成和分析设备之间的物理连接，这些设备在空间上是分开的，自动化了样本的运输和处理。原则上，机器人可以执行实验室中人类研究人员需要的所有动作。然而，当前的机器人系统仍然依赖人类预先编程来映射实验室布局，定义移动轨迹，并注册设备位置。处理意外或自适应情况仍然是一个挑战，因为预先编程无法预料实验装置的每种可能状态。实时学习和自适应操作是需要进一步技术进步的活跃研究领域。从长远来看，体现式人工智能有望增强机器人学习能力，使代理能够快速适应新环境和工具。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.1 Real-World Interaction Challenges/section/5/text
1. Vescovi等人提出的模块化实验室机器人架构如何帮助解决实验室自动化中的挑战，以及其在生物和物理科学中的具体应用效果如何？ 2. Fernando等人将机器人集成到Bluesky实验编排框架中，这种结合使用的方法对实验室操作的效率和可靠性有何影响？如何评价这种集成方法在促进实验设备自动化方面的潜力？ 3. Lo等人提倡开发和整合“节俭双胞胎”设备，这种低成本设备对于实验室操作的普及和可持续发展有哪些重要意义？如何看待这种设备在解决实验设备定制和自适应操作方面的潜在作用？
两种方法可以结合使用。例如，Vescovi等人定义了一种模块化实验室机器人架构，允许将高级命令转化为各种不同机器人设备和实验室设备的特定操作，并将机器人设备与高性能计算等人工智能驱动发现架构的其他元素连接起来。该架构已被用于在生物和物理科学中自动化实验。类似地，Fernando等人将一个与Robotic Operating System 2（ROS2）兼容的机器人集成到Bluesky实验编排框架中。Lo等人主张开发和整合低成本的“节俭双胞胎”设备，以促进实验并使更多人能够获得实验设备。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.2 Complex Reasoning Challenges/section
LLMs驱动的代理在复杂推理任务中面临挑战。尽管它们在结果驱动下表现出一定程度的推理能力，但在处理复杂逻辑和数值问题时仍存在不完美之处。研究评估了多个LLM驱动的代理，发现它们在挑战性数学问题、数据驱动科学发现和抽象归纳推理方面表现不佳。新技术如chain-of-thought和tree-of-thoughts被引入以增强推理能力，但发展仍不足以支持可靠的因果推断。在处理算术和符号问题时，LLMs经常无法可靠执行复杂运算，需要依赖外部工具。尽管使用专门工具可以提高性能，但在一般化学问题中，工具增强效果有限。因此，代理的多领域知识和推理能力对于解决没有特定工具的问题至关重要。这些挑战凸显了开发稳健人工智能代理作为科学研究助手的重要性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.2 Complex Reasoning Challenges/section/0/text
1. LLMs驱动的代理在进行推理时与人类推理有何本质区别？这种区别对于代理在处理复杂逻辑和数值问题时的表现有何影响？  2. 代理在处理挑战性数学问题、数据驱动科学发现和抽象归纳推理方面表现不佳的原因是什么？新技术如chain-of-thought和tree-of-thoughts如何尝试增强代理的推理能力，但为何仍然无法支持可靠的因果推断？  3. 为什么LLMs在处理算术和符号问题时经常无法可靠执行复杂运算？外部工具对于提高代理性能有何作用？然而，在一般化学问题中，为什么工具的增强效果有限？
一个基本的哲学问题是，通常由LLMs驱动的代理是否真正可以进行推理。根据定义，语言模型通过预测下一个标记来生成输出，这一机制与人类推理根本不同。从结果驱动的角度来看，这些输入-输出系统在现象学上表现出推理能力，因为它们产生的输出与生成任意响应的参考系统相比具有意义[902]。然而，无论采取何种角度，这种能力仍然是不完美的，特别是在处理对科学知识发现至关重要的复杂逻辑和数值问题时。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.2 Complex Reasoning Challenges/section/1/text
1. LLMs在处理复杂逻辑和数值问题时存在哪些不足之处，以及这些不足如何影响代理在挑战性数学问题、数据驱动科学发现和抽象归纳推理方面的表现？  2. 为什么LLMs经常无法可靠执行复杂运算，需要依赖外部工具？使用专门工具可以提高性能，但在一般化学问题中，工具增强效果为何有限？  3. 为什么代理的多领域知识和推理能力对解决没有特定工具的问题至关重要？这如何突显开发稳健人工智能代理作为科学研究助手的重要性？
代理和LLMs在艰难的推理任务中遇到困难。Glazer等人[903]引入了FrontierMath，一个包含数百个原创且具有挑战性的数学问题的基准，涵盖了现代数学的大多数主要分支。对最先进的由LLMs驱动的代理进行评估，包括ol-preview（OpenAI）、ol-mini（OpenAI）、GPT-4o（OpenAI，2024年8月6日版本）、Claude 3.5 Sonnet（Anthropic，2024年10月22日版本）、Grok 2 Beta（XAI）和Gemini $1.5\:\mathrm{Pro}\:002$（Google DeepMind），结果显示没有任何模型在完整基准测试中取得甚至$2\%$的成功率。Chen等人[873]提出了ScienceAgentBench，这是一个旨在评估语言代理在数据驱动科学发现中的基准。在从四个学科领域的44篇同行评审出版物中提取的102个任务中，OpenAI ol只成功解决了其中的$42.2\%$。Chollet [865]提出了抽象和推理挑战（ARC），以评估LLMs在执行抽象归纳推理时不依赖记忆或外部知识的能力。即使经过仔细提示，GPT-4o仅正确解决了$19\%$的任务，远远低于人类平均表现的$\sim75\%$[94,905]。Zhu等人[96]提出了AI智能的四级分类，包括L1（仲裁争端）、L2（审计评论）、L3（审查论文）和L4（撰写论文）。他们将当前最先进的LLM驱动代理分类为接近L2级能力。为增强代理的推理能力，研究人员引入了诸如chain-of-thought[907]、tree-of-thoughts[72]和[70]等技术。尽管新方法不断涌现，但正如第2.2节讨论的那样，推理能力的进一步发展对于在科学研究中实现可靠的因果推断仍然至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.2 Complex Reasoning Challenges/section/2/text
1. 在处理定量和符号问题时，代理和LLMs存在哪些困难？使用外部工具是一种常见的解决方法，但这种方法有什么局限性？ 2. 在数学问题解决中，为什么使用符号求解器等外部工具比直接LLM推理更可取？这种方法的优势和劣势是什么？ 3. 在化学问题解决中，为什么使用工具增强的LLMs并不总是能够在化学任务中 consistently 胜过没有工具的基础LLMs？这种现象暴露了什么问题？
代理和LLMs在处理定量和符号问题时也存在困难。例如，GPT-4和GPT-3.5经常难以可靠地执行复杂的算术运算，如$12, 345\times98$，765，或将IUPAC化学名称翻译成准确的分子结构图。克服这些限制的常见方法是使用外部工具，而不是依赖LLM本身进行推理。在数学问题解决中，例如，像符号求解器这样的工具比直接LLM推理更可取。然而，这种缓解并不能解决数值理解的固有缺陷，这可能对科学推理构成潜在风险。此外，Yu等人发现，在化学问题解决中，使用工具增强的LLMs并不总是能够在化学问题解决中 consistently 超越没有工具的基础LLMs。例如，在专门的化学任务中，如合成预测，增强LLMs with tools 不能一直胜过基础LLMs。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.2 Complex Reasoning Challenges/section/3/text
1. 在处理一般化学问题时，为什么使用专门工具增强的LLMs效果较差？  2. 为什么代理在处理没有特定工具可以解决的化学问题时需要依赖多个化学知识片段进行正确推理？ 3. 在科学研究助手领域，为什么开发稳健的人工智能代理至关重要？
使用专门工具增强的LLMs可以显著提升性能；然而，对于一般化学问题，如考试中那些没有特定工具可以直接解决的问题，工具增强效果较差。在这些情况下，代理通过利用多个化学知识片段进行正确推理的能力变得更加重要。

前面的讨论强调了开发评估人工智能代理作为科学研究助手的稳健方法的重要性，这是Cappello等人（910）长篇讨论的主题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.3 Challenges in Integrating Prior Knowledge/section
在处理大型语言模型的先验知识整合中存在诸多挑战。先前知识对智能代理的提升至关重要，但当前的先进LLMs仍无法涵盖所有知识来源。付费或未发表的知识、专家经验和情境知识等类型的信息常常未被包含在公开模型中，这为整合多样化知识带来困难。此外，协调不同来源的知识、区分权威信息和谣言以及确保信息可靠性也是挑战。建立评估不同知识片段可靠性的系统将对有效整合知识至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.3 Challenges in Integrating Prior Knowledge/section/0/text
1. 为什么先前的知识对于提升智能代理至关重要？如何利用代理的先前知识来增强其智能水平？    2. 先进的LLMs在训练时主要利用哪些类型的公开文本数据？尽管如此，为什么实现一个能够整合所有现有人类知识的代理仍然是一个重大挑战？  3. 如何评估不同知识片段的可靠性对于有效整合多样化知识的重要性体现在哪些方面？
先前的知识是提升智能的关键因素。如在第12.1节中讨论的，代理的先前知识$M_{t}^{\mathrm{mem}}$有助于减少$D_{\mathrm{K}}(\theta,M_{t}^{\mathrm{mem}})$并提高代理的智能$I Q_{t}^{\mathrm{agent}}$。人类主导的科学发现通常可以在相对较小的数据集上取得突破，这要归功于人类拥有的广泛先前知识。支持自主代理的最先进的LLMs被训练在几乎所有公开可用的文本数据上，包括网站、书籍和其他来源，从而涵盖了大部分常见知识以及公开可访问的专业知识。然而，实现一个能够无缝整合所有现有人类知识的代理仍然是一个重大挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.3 Challenges in Integrating Prior Knowledge/section/1/text
1. 如何评估付费或未发表的知识、专家经验以及情境知识的可靠性，以便有效整合这些多样化的知识到大型语言模型中？  2. 在整合付费或未发表的知识、专家经验和情境知识到大型语言模型时，如何解决协调不同来源知识、区分权威信息和谣言的挑战？  3. 大型语言模型如何能够有效地访问并利用付费或未发表的知识、专家经验以及情境知识，以提高智能代理的决策和应用能力？
至少有三种类型的知识来源可能未包含在大型语言模型（LLMs）的预训练中：（1）付费或未发表的知识，包括非开放获取出版物、行业特定数据和失败的实验。尽管这些知识在细化领域特定见解方面具有潜在价值，但它们通常无法被公共模型访问。 （2）经验知识。专家的经验决策通常是有效的，特别是在没有现有数据可供解决新问题的情况下。然而，大量的专家启发式通常作为文本数据不可访问。 （3）情境或局部知识。与现实世界条件相关的知识，例如化学反应中的安全协议或设备操作，通常未包含在预训练模型中，但对于实际应用至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/12 Scientific Discovery and Intelligent Evolution 120/12.3 Technological Readiness and Challenges/12.3.3 Challenges in Integrating Prior Knowledge/section/2/text
1. 如何解决在整合多样化知识来源时所面临的协调冲突信息的挑战，特别是在区分权威信息和谣言、以及确保信息可靠性方面的困难？  2. 在处理大型语言模型中，如何建立一个评估不同知识片段证据级别的系统，以量化可靠性、验证参考文献，并有效实现知识融合？  3. 对于先进LLMs而言，如何解决当前无法涵盖所有知识来源的问题，特别是付费或未发表的知识、专家经验和情境知识等类型信息的整合困难？
此外，整合多样化的知识来源在协调冲突信息方面存在挑战。例如，OpenAI的Deep Research积极收集在线信息并进行多步推理，在“人类最后一次考试”和GAIA基准测试中取得了最先进的性能。然而，它仍然难以区分权威信息和谣言，并在信心校准方面存在局限，经常错误地表达其确定性水平。建立一个评估不同知识片段证据级别的系统，比如量化可靠性和验证参考文献，可能对有效的知识融合至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/) Design of Multi-Agent Systems 133/section
本章讨论了多Agent系统的设计。首先，探讨了智能代理的模块化基础，将认知、感知和操作模块映射到人脑功能上，并强调核心组件如记忆、世界建模和奖励处理系统。其次，研究了自我增强和自适应进化机制，介绍了代理如何完善能力、适应环境，并通过自动化优化实现持续学习。接着，讨论了协作和进化多代理系统，突出了集体智能的重要性，强调了代理间相互作用和合作的关键性。最后，重点探讨了构建安全、可靠、有益的人工智能系统的使命，强调了安全威胁、道德对齐和实用缓解策略的重要性。通过综合模块化人工智能架构和不同学科的见解，本章确定了研究空白、挑战和机遇，鼓励技术创新以促进社会利益。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/) Design of Multi-Agent Systems 133/section/0/text
1. 在构建组合AI代理团队时，如何平衡各个代理之间的合作与竞争关系，以实现更高效的任务解决能力？  2. 代理交互协议中的消息类型、通信接口以及下一代通信协议如何影响多Agent系统的整体性能和稳定性？  3. 如何利用工作流生成来促进代理间的协作任务解决，以应对现实世界动态环境带来的挑战？
13.1 战略学习：合作与竞争 133
13.2 建模现实世界动态 134
13.3 通过工作流生成进行协作任务解决 135
13.4 组合AI代理团队 135
13.5 代理交互协议 137
13.5.1 消息类型 137
13.5.2 通信接口 138
13.5.3 下一代通信协议 138

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/section
本章探讨了通信拓扑结构在人工智能系统中的关键作用。首先，介绍了静态和动态拓扑结构，探讨了其在智能代理中的应用。接着，讨论了可伸缩性考虑，强调了在设计和评估智能代理时需要考虑的重要因素。子章节则深入探讨了人类世界模型的核心内容，将其转化为人工智能的关键议题，并介绍了人工智能世界模型的不同范式。此外，探讨了世界模型与其他模块的关系，强调了记忆、感知和行动模块在智能代理架构中的互动。最后，总结了AI世界模型的演变过程和未来挑战，强调平衡复杂性与预测准确性的重要性，以及在真实环境中确保稳定性和可靠性的挑战。未来的发展需要不断探索简单性与复杂性之间的平衡，以推动人工智能系统的发展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/section/0/text
1. 在人工智能系统中，静态拓扑结构和动态拓扑结构各自的优缺点是什么，它们在智能代理中的应用有何异同之处？ 2. 可伸缩性在设计和评估智能代理时为什么是一个重要因素？在考虑可伸缩性时需要关注哪些方面？ 3. 在人工智能系统中，如何平衡复杂性与预测准确性的挑战？为确保稳定性和可靠性，智能代理架构中的记忆、感知和行动模块如何相互作用？
14.1 系统拓扑结构 141
14.1.1 静态拓扑结构 141
14.1.2 动态和自适应拓扑结构 142
14.2 可伸缩性考虑 144

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.1 The Human World Model/section
人类世界模型是人类内部对外部现实的简洁描绘，促使个体能够预测结果、规划行动，并解释新情境。研究显示，人类大脑运行内部的“现实小规模模型”来模拟事件可能的发展和评估行动方案，跨越多种感知方式并动态更新。这种模型具有预测性、整合性、适应性和多尺度性，使人类能够根据需要处理不同时间和空间尺度的信息。以饥饿和进食为例，人类世界模型整合了视觉、味觉、气味等感知，展示了适应性和反事实模拟的能力。总体而言，人类世界模型是一个灵活且不断演化的心智构建，根植于感知和记忆，塑造着个体与外部世界互动的方式。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.1 The Human World Model/section/0/text
1. 人类自然构建的心智模型如何帮助个体在预测结果、规划行动以及解释新情境时减少直接试错的需求？ 2. 早期关于空间导航的研究如何揭示了人类和动物形成认知地图的能力，以及这种能力对于想象潜在路径的影响？ 3. 人类世界模型与心智模型之间的联系是如何促进个体处理不同时间和空间尺度信息的？
人类自然而然地构建对世界的内部表征，通常在心理学中被称为心智模型。这些模型作为对外部现实的简洁且可操作的描绘，使个体能够在最小程度依赖直接试错的情况下预测结果、规划行动，并解释新颖情境。早期关于空间导航的研究表明，人类和动物形成了对周围环境的“认知地图”，暗示了一种在实际穿越之前就能够想象潜在路径的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.1 The Human World Model/section/1/text
1. Craik的论点中提到的“现实小规模模型”如何帮助人类预测事件的发展并评估可能的行动方案？这种模型是如何跨越多种感知方式并动态更新的？  2. 预测处理理论中的“Surfing Uncertainty”是如何描述大脑作为一个分层预测机器的？它是如何不断生成关于感官输入的自上而下预测，并根据预测误差更新模型的？  3. 论文提到了存储知识与主动生成假设未来状态之间的密切相互作用，这种相互作用是如何影响人类世界模型的灵活性和演化性质的？
Craik的重要论点是，人类大脑运行内部的“现实小规模模型”[342]来模拟事件可能如何展开并评估可能的行动方案。后续研究提出，这种模拟跨越视觉、语言和运动控制等多种感知方式，并通过将预测与新观察结果进行比较而动态更新。这一过程将记忆回忆与向前投射相融合，暗示着存储知识与主动生成假设未来状态之间的密切相互作用[343]。更近期的预测处理理论，如“Surfing Uncertainty”[344]，提出大脑作为一个分层预测机器运作，不断生成关于感官输入的自上而下预测，并根据预测误差更新其模型。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.1 The Human World Model/section/2/text
1. 人类世界模型的预测性如何影响个体的行动决策和响应方式？ 2. 适应性在人类心智模型中扮演怎样的角色，如何帮助个体减少想象与实际结果之间的差距？ 3. 人类世界模型如何实现多尺度运作，以处理不同时间和空间尺度上的信息？
这些人类心智模型具有以下关键特点：

·预测性：它们预测环境变化，指导决策何时移动或如何做出响应。
·整合性：它们将感官输入、过往经验和抽象推理结合到一个统一的“接下来可能发生什么”的视角中。
·适应性：当现实与期望不符时，它们会进行修订，随着时间的推移减少想象和实际结果之间的差距。
·多尺度：它们在不同的时间和空间尺度上无缝运作，同时处理即时的物理动态（毫秒级）、中期的行动序列（秒到分钟）、以及长期计划（小时到年）。这种灵活性使人类能够根据需要放大细节或放大考虑更广泛的背景。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.1 The Human World Model/section/3/text
1. 饥饿和进食作为整合世界建模的示例，如何展示了人类世界模型具有预测性、整合性和适应性？ 2. 在人类世界模型中，为什么说反事实模拟的能力使个体能够进行复杂规划，这是人工智能世界模型所努力复制的？ 3. 人类世界模型是一个灵活且不断演化的心智构建，如何根植于感知和记忆，塑造着个体与外部世界互动的方式？
以饥饿和进食为例，将其视为整合世界建模的示例。当感到饥饿时，一个人的内部模型会激活关于食物的预测——不仅模拟视觉外观，还有味道、气味以及预期的满足感，甚至在食物出现之前就会引发唾液分泌等生理反应。这展示了跨感知、记忆和行动规划之间的无缝整合。

这个例子还突显了适应性：一旦满足，同样的模型会动态更新，降低进一步进食的预期奖励值。尽管识别出相同的食物项目，但它们的预期效用会根据内部状态而变化。此外，人类保持着反事实模拟——现在拒绝甜点，但准确预测将来会喜欢——这使得能够在假设情景和时间范围内进行复杂规划，这是综合人工智能世界模型努力复制的能力。

总之，人类世界模型并非静态的事实库，而是一个灵活且不断演化的心智构建，深深扎根于感知和记忆，不断塑造（并受到塑造）个体与外部世界互动的方式。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.2 Translating Human World Models to AI/section
本节探讨了将人类世界模型转化为人工智能的关键议题。研究旨在模仿人类心智模型的预测、整合和适应性能力，通过强化学习框架和神经网络预测未来观察结果来实现更高效的决策制定。随着深度学习的发展，引入了AI世界模型的概念，如环境潜在生成模型和基于模型的RL，使代理能够模拟人类的心理排练和规划行为。同时，利用大规模模拟器和机器人技术提供丰富经验，类似于人类儿童通过探索环境学习的方式。然而，尚需解决如何统一隐式生成建模、显式因式分解和模拟器驱动的探索等方法，以形成类似于人类“心智模型”的一致性。AI世界模型作为概念桥梁，连接了认知心理学中心智模型的理论与人工智能代理的实现，为实现灵活高效学习提供了新思路。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.2 Translating Human World Models to AI/section/0/text
1. 人工智能领域如何借鉴人类心智模型的预测、整合和适应性特质，以实现更高效的决策制定？ 2. AI世界模型如何通过环境潜在生成模型和基于模型的RL来模拟人类的心理排练和规划行为？ 3. 在实现类似于人类“心智模型”的一致性过程中，AI世界模型面临着哪些挑战和需要解决的问题？
人工智能领域的研究长期以来一直致力于复制人类心智模型所展现的预测、整合和适应性特质。例如，早期的强化学习框架提出学习环境模型以进行规划，比如Dyna所展示的方式，同时同时代的工作研究了使用神经网络来预测流数据中未来的观察结果。这两个方向的动机都源于这样一个观念，即世界的内部模拟器可以实现比纯粹的反应式试错学习更高效的决策制定。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.2 Translating Human World Models to AI/section/1/text
1. 端到端的环境潜在生成模型如何帮助代理在离线训练或优化策略时模拟人类的心理排练？   2. AI世界模型中的显式前向建模方法如何有助于基于模型的RL代理进行规划并预测未来状态？
随后深度学习的进展使“AI世界模型”的概念变得更加清晰。一种有影响力的方法引入了一种端到端的环境潜在生成模型（例如，“世界模型”[348]），其中循环神经网络（RNN）和变分自动编码器（VAE）共同学习“梦想”未来的轨迹。这些潜在的展开使代理能够在离线训练或优化策略，有效地模拟人类在执行动作之前如何进行心理排练。除了这种隐式设计，显式的前向建模方法也出现在基于模型的RL中，使代理能够预测 $P(\bar{s}^{\prime}\mid s,a)$ 并使用近似前瞻进行规划。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.2 Translating Human World Models to AI/section/2/text
1. 智能系统如何能够统一隐式生成建模、显式因式分解和模拟器驱动的探索等方法，以形成类似于人类观察到的“心智模型”的一致性？ 2. 语言模型的推理激增如何揭示了跨模态和任务的潜力，以及如何呼应了人类在预测框架下整合语言、视觉和运动知识的方式？ 3. 大规模模拟器和机器人技术如何通过丰富多样的经验来打下智能系统学习的基础，与人类儿童通过积极探索环境学习的方式有何相似之处？
另一方面的工作利用大规模模拟器或现实世界的机器人技术，通过丰富多样的经验来打下学习基础。这些设置让人想起人类儿童通过积极探索环境学习的方式，逐渐完善他们的内部表征。然而一个关键问题仍然存在：智能系统是否能够将这些方法（隐式生成建模、显式因式分解和模拟器驱动的探索）统一起来，形成类似于人类观察到的“心智模型”的一致性？基于语言模型的推理的最近激增暗示着跨模态和任务的潜力，呼应了人类如何在一个预测框架下整合语言、视觉和运动知识的方式。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.2 Translating Human World Models to AI/section/3/text
1. AI世界模型如何作为一个概念桥梁，连接了认知心理学中关于心智模型的理论与人工智能代理的实现？   2. 在实现灵活、高效学习的过程中，AI世界模型如何借鉴人类儿童通过探索环境学习的方式，并将其应用于决策制定？   3. 如何解决隐式生成建模、显式因式分解和模拟器驱动的探索等方法之间的统一性，以构建类似于人类“心智模型”的一致性？
总的来说，随着人工智能系统努力实现灵活、高效的学习，AI世界模型作为一个概念桥梁，连接了认知心理学中关于心智模型的理论和为人工智能代理赋予想象力、预测推理能力以及在复杂领域中进行强健适应的实现。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/section
本节介绍了人工智能世界模型的四种范式：隐式、显式、基于模拟器和混合或指导型模型。隐式范式侧重于内部机制，通过神经网络编码环境动态；显式范式则分离转移和观测模型，更易解释和调试；基于模拟器的范式外包环境更新给模拟器，减轻学习模型错误风险；混合和指导驱动范式整合外部符号知识或语言模型，提供灵活性。这些范式在复杂性、透明性和适应性方面存在权衡，为人工智能世界建模提供了多元选择，并通过范式比较总结为进一步研究提供了框架。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/section/0/text
1. 在设计Alworld模型时，隐式模型和显式模型分别如何处理对环境动态的理解，以及它们在内部和外部机制依赖上有何不同？ 2. 在Alworld模型设计中，基于模拟器和混合或指导型模型相较于隐式和显式模型更复杂的原因是什么？这种复杂性如何反映在它们对环境动态的理解和整体系统的复杂性上？ 3. 在Alworld模型设计中，如何利用图4.2所示的二维空间来比较不同范式在内部与外部机制依赖以及整体系统复杂性方面的差异？这种比较有助于我们如何选择适合的建模方法？
设计Alworld模型涉及确定AI代理如何获取、表示和更新其对环境动态的理解。虽然具体实现各不相同，但大多数方法可归为四种广泛范式：隐式、显式、基于模拟器和混合或指导型模型。这些范式可沿着两个关键维度进一步分析：对内部（基于神经网络）与外部（基于规则或结构化）机制的依赖，以及整体系统复杂性。图4.2展示了这个二维空间，展示了不同方法在这些轴上的分布情况。通常来说，隐式模型更倾向于依赖内部机制，而显式和基于模拟器的模型则包含更多外部结构。基于模拟器和显式模型也往往比隐式和混合方法更复杂，反映了它们的结构化推理和工程约束。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/section/1/figure
1. 根据图4.2的描述，哪种人工智能世界模型方法在复杂性和依赖程度上处于最左侧位置？ 2. 在人工智能世界模型方法的二维布局中，为什么混合或指导型模型位于内部方法和外部解决方案之间？
图4.2：人工智能世界模型方法的二维布局。水平轴表示复杂性（从左到右）。垂直轴跨越内部方法（底部）到外部解决方案（顶部）。大致位置反映了每种方法对大型学习网络与明确规则或代码的依赖程度，以及其整体系统复杂性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.1 Overview of World Model Paradigms/section
本节介绍了世界模型范式的概述，旨在探讨代理如何捕获或访问环境动态的机制。在马尔可夫框架中，环境通过转移和观测分布描述，代理通过学习或利用这些函数的近似来预测未来状态或观测。作者提出了四种主要范式：隐式范式利用神经网络编码映射，显式范式直接建模转移和观测模型，基于模拟器范式依赖外部模拟器或物理世界，其他范式包括混合或指导驱动方法。这些范式在处理方程式、权衡解释性与可扩展性以及在不同任务中的优势方面展现出多样性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.1 Overview of World Model Paradigms/section/0/text
1. AI世界模型的四种主要范式分别是如何帮助智能代理预测未来状态或观测的？    2. 在模块化、脑启发式架构中，智能代理的自我增强和自适应进化机制是如何实现持续学习的？    3. 如何通过综合不同学科的见解，构建安全、可靠和有益的人工智能系统以应对内在和外在的安全威胁？
大型语言模型（LLMs）的出现催生了人工智能领域的深刻转变，为能够在各种领域展现复杂推理、强大感知和多功能行为能力的先进智能代理铺平了道路。随着这些代理在推动人工智能研究和实际应用方面的作用日益增强，它们的设计、评估和持续改进提出了复杂而多面向的挑战。本调查提供了一个全面的概述，将智能代理置于一个模块化、脑启发式架构中，该架构整合了认知科学、神经科学和计算研究的原则。我们将探索分为四个相互关联的部分。首先，我们深入探讨智能代理的模块化基础，系统地将它们的认知、感知和操作模块映射到类似的人脑功能上，并阐明核心组件，如记忆、世界建模、奖励处理和类似情感的系统。其次，我们讨论自我增强和自适应进化机制，探讨代理如何自主完善其能力、适应动态环境，并通过自动化优化范式实现持续学习，包括新兴的AutoML和LLM驱动的优化策略。第三，我们研究协作和进化多代理系统，调查从代理相互作用、合作和社会结构中出现的集体智能，突显与人类社会动态的相似之处。最后，我们着重讨论构建安全、可靠和有益的人工智能系统的关键使命，强调内在和外在的安全威胁、道德对齐、稳健性以及在值得信赖的现实世界部署所必需的实用缓解策略。通过将模块化人工智能架构与不同学科的见解综合起来，本调查确定了关键的研究空白、挑战和机遇，鼓励创新，使技术进步与有意义的社会利益相协调。该项目的Github链接为: https://github.com/FoundationAgents/awesome-foundation-agents。

一个$AI$世界模型广泛指代代理捕获或访问近似环境动态的任何机制。设$s$表示可能的环境状态集合，$\mathcal{A}$表示动作集合，$\mathcal{O}$表示观测集合。在理想化的马尔可夫框架中，环境通过转移和观测分布来描述：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.1 Overview of World Model Paradigms/section/1/formula
$$ 
\begin{array}{r l}&{T(s^{\prime}\mid s,a)\quad:\quad\mathcal{S}\times\mathcal{A}\to\Delta(\mathcal{S}),}\\ &{O(o\mid s^{\prime})\quad:\quad\mathcal{S}\to\Delta(\mathcal{O}),}\end{array}
 $$
这个公式描述了在理想化的马尔可夫框架中，环境是如何通过转移和观测分布来描述的。具体而言，$T(s^{\prime}\mid s,a)$表示在给定状态$s$和执行动作$a$之后，环境从状态$s$转移到状态$s^{\prime}$的转移概率；$O(o\mid s^{\prime})$表示在状态$s^{\prime}$下生成观测$o$的概率。  在智能代理的世界模型中，通常会学习或利用这些转移和观测函数的近似，以便代理可以在不实际执行动作的情况下预测未来的状态或观测。这些函数的近似可以通过不同的方法来实现，作者将其分为四种主要范式：隐式范式、显式范式、基于模拟器范式和其他范式。这些范式反映了世界模型研究领域的多样性和不断发展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.1 Overview of World Model Paradigms/section/2/text
1. 世界模型中的隐式范式和显式范式分别采用何种方式来处理状态转移和观测模型的建模，它们各自的优势和劣势是什么？  2. 基于模拟器范式中代理依赖外部模拟器或物理世界作为地面真相，相比于其他范式，这种方法在什么情况下可能会面临挑战或限制？  3. 在世界模型研究中，混合或指导驱动的方法如何突显了对传统近似方法的补充，以及它们如何结合了不同类型的知识来提高代理的环境建模能力？
其中$T(\cdot)$规定了状态在动作下的演变方式，$O(\cdot)$定义了状态如何产生观测。世界模型通常学习或利用这些函数的近似（或变体），使代理能够在不在环境中执行实际动作的情况下预测未来状态或观测。

存在许多方法来实现这些近似，我们将其分为四种主要范式：

·隐式范式：一个单一的神经网络或潜在结构编码转移和观测映射，而无需显式因子分解。《World Models》或用于环境推理的大型语言模型是典型示例。代理通常展开这个黑盒函数以模拟假设轨迹。
·显式范式：代理直接建模或访问可学习的转移模型$T_{\theta}$和观测模型$O_{\theta}$，通常能够实现可解释性或模块化设计。基于模型的强化学习方法，如MuZero或Dreamer，学习或改进$T_{\theta}$，在近似状态空间中进行规划。如果显式预测下一个状态或帧，生成式视觉模型如[353,358]属于这一类别。
·基于模拟器范式：代理依赖外部模拟器或甚至物理世界作为地面真相，而不是近似(4.1)(4.2)。像SAPIEN或真实机器人管道这样的系统可以被视为代理查询的“本地”环境模型。虽然不需要学习的$T(\cdot)$，但代理在运行时间或真实世界风险方面付出代价。
·其他范式（混合或指导驱动）：无法简单分类的方法。它们可能以文本形式存储新兴规则，将隐式LLM知识精炼为部分因果图，或将外部组件与学习的子模块结合。这些方法突显了世界模型研究的不断发展，其中指导、符号规则或即时结构可以补充更传统的近似方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.1 Overview of World Model Paradigms/section/3/text
1. 每种世界模型范式是如何处理或规避方程式（4.1）和（4.2）的？ 2. 在权衡解释性与可扩展性时，每种范式采取了怎样的策略？ 3. 在不同任务中，各种世界模型范式相对优势体现在哪些方面？
在本小节的其余部分，我们将探讨每种范式如何处理（或规避）方程式（4.1）和（4.2），解释性和可扩展性之间的权衡，以及它们在从基于文本到高维度实体控制等不同任务中的相对优点。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.2 Implicit Paradigm/section
隐式范式将环境动态编码在单个神经模型内，通过潜在状态$h_{t}$的更新方式实现。这种模型结合转移和观测机制，例如World Models框架中的变分自动编码器，能够在潜在空间中“梦想”轨迹。隐式模型具有端到端训练的优势，但缺乏透明性，难以解释网络如何捕捉领域约束。尽管在复杂环境中具有吸引力，但面临解释性约束和精细控制方面的挑战。因此，隐式范式在灵活性和简单性方面具有吸引力，但在需要明确约束或精细控制时可能受到限制。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.2 Implicit Paradigm/section/0/text
1. 隐式范式中的神经模型是如何将环境动态编码在其中的？这种编码方式有哪些优势和局限性？  2. 隐式模型中的潜在状态$h_{t}$是如何进行更新的？这种更新方式有哪些特点，对模型性能有何影响？  3. 隐式范式相比于显式模型在灵活性和简单性方面有何优势？但在需要明确约束或精细控制时可能会面临哪些挑战？
在隐式范式中，一个代理将所有环境动态（包括状态如何演变以及观测如何生成）编码在单个（或紧密耦合的）神经模型内。形式上，一个维持更新的潜在状态 $h_{t}$，其更新方式如下所示：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.2 Implicit Paradigm/section/1/formula
$$ 
h_{t+1}=f_{\theta}(h_{t},a_{t}),\quad\hat{o}_{t+1}=g_{\theta}\big(h_{t+1}\big),
 $$
该公式描述了隐式范式中潜在状态$h_{t}$的更新方式。在这个公式中，$h_{t+1}$表示下一个时刻的潜在状态，通过函数$f_{\theta}$对当前时刻的潜在状态$h_{t}$和动作$a_{t}$进行更新得到。同时，$\hat{o}_{t+1}$表示对应的下一个时刻的观测值，通过函数$g_{\theta}$对更新后的潜在状态$h_{t+1}$进行生成。  在论文中，这个公式的作用是描述了隐式模型中潜在状态的演变方式，将环境动态编码在单个神经模型内。通过这种方式，模型可以在潜在空间中“梦想”轨迹，同时具有端到端训练的优势。然而，隐式模型缺乏透明性，难以解释网络如何捕捉领域约束，因此在需要明确约束或精细控制时可能受到限制。  在公式中，$f_{\theta}$和$g_{\theta}$是神经网络模型的参数，$a_{t}$是代理在时刻$t$选择的动作。函数$f_{\theta}$负责更新潜在状态$h_{t}$，其中参数$\theta$表示模型的参数，决定了更新过程。函数$g_{\theta}$则根据更新后的潜在状态$h_{t+1}$生成对应的观测值$\hat{o}_{t+1}$。  这个公式的设计是为了将环境动态编码在单个神经模型内，实现端到端的训练，同时在潜在空间中模拟环境的演变过程。通过这种方式，模型能够灵活地处理复杂环境，但也面临着解释性约束和精细控制方面的挑战。在论文中，这个公式与隐式模型的整体框架相关联，支持模型在潜在空间中对环境进行建模和预测。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.2 Implicit Paradigm/section/2/text
1. 隐式范式中的模型结合转移和观测机制，如何实现在潜在空间中“梦想”轨迹的功能？    2. 隐式模型在灵活性和简单性方面的优势是如何体现的？它在面临解释性约束和精细控制方面存在哪些挑战？  3. 隐式范式中的端到端训练具有哪些优势？相比于显式模型，隐式模型在捕捉领域约束方面有何不同之处？
其中 $f_{\theta}$ 包含了方程（4.1）-（4.2）中的转移函数 $T(\cdot)$（以及 $O(\cdot)$ 的一部分），但没有明确地将这些组件呈现出来。一个经典的例子是World Models框架[348]，其中变分自动编码器（VAE）首先将视觉输入压缩为潜在编码，然后一个循环网络预测下一个潜在编码，有效地在潜在空间中“梦想”轨迹。最近的研究还探讨了将大型语言模型（LLMs）重新用于纯文本或符号领域的环境模拟[107,74]，尽管这些模型并不总是建立在严格的时间序列或基于物理的数据基础之上。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.2 Implicit Paradigm/section/3/text
1. 隐式范式中的模型端到端训练的优势是什么？它们为何往往被描述为不透明的，以及这种不透明性可能导致的挑战是什么？ 2. 在复杂环境中，隐式模型如何能够自行发现潜在结构？这种能力可能会带来哪些优势和风险？ 3. 隐式范式相对于显式模型在灵活性和简单性方面的优势是什么？但当需要明确约束或精细控制时，隐式范式可能会面临哪些限制？
因为隐式模型将转移和观测机制融合为一个整体函数，所以它们可以优雅地进行端到端训练，并在内部展开进行规划。然而，它们往往是不透明的：很难解释网络如何准确捕捉领域约束，或者直接注入知识到转移的任何部分。这在高度复杂的环境中可能是有利的，其中一个大容量模型可以自行发现潜在结构，但也存在在分布转移下脆弱的风险。总体而言，隐式范式因其简单性和灵活性而具有吸引力，但在需要解释性明确约束或对动态的精细控制时可能会带来挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.3 Explicit Paradigm/section
明示范式通过分解世界模型，学习或编码转移函数和观测函数来实现显式分离。基于模型的强化学习算法如MuZero或Dreamer优化前向模型进行规划。显式方法更易解释和调试，但对模型错误敏感。它们整合外部规划器，融合学习和符号组件，实现人类知识融入并保留深度学习优势。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.3 Explicit Paradigm/section/0/text
1. 显式范式中的转移函数和观测函数分别在何种情况下可以独立查询？这种独立性对算法的哪些方面有何影响？  2. 相较于隐式方法，显式范式在学习或编码转移函数和观测函数时存在哪些优势和劣势？这些优劣势如何影响算法的性能和应用？  3. 显式范式如何通过整合外部规划器和融合学习与符号组件，实现人类知识融入并保留深度学习优势？这种整合对于算法的可解释性和鲁棒性有何影响？
相反，显式范式通过分解世界模型，通常通过学习或编码转移函数 $\hat{T}_{\theta}{\left(s_{t+1}\right|}$ $s_{t},a_{t})$ 和观测函数 $\hat{O}_{\theta}(o_{t+1}\mid s_{t+1})$ 来实现。这种显式分离使得可以独立查询每个函数。例如，可以从中抽取样本。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.3 Explicit Paradigm/section/1/formula
$$ 
\hat{s}_{t+1}\sim\hat{T}_{\boldsymbol{\theta}}\big(s_{t},a_{t}\big),\quad\hat{o}_{t+1}\sim\hat{O}_{\boldsymbol{\theta}}\big(\hat{s}_{t+1}\big).
 $$
这个公式的作用是描述基于显式范式的模型强化学习算法中的状态转移和观测过程。公式中的 $\hat{s}_{t+1}$ 表示下一个状态的估计值，通过从转移函数 $\hat{T}_{\boldsymbol{\theta}}\big(s_{t},a_{t}\big)$ 中采样得到，其中 $s_{t}$ 是当前状态，$a_{t}$ 是执行的动作。而 $\hat{o}_{t+1}$ 表示下一个观测的估计值，通过从观测函数 $\hat{O}_{\boldsymbol{\theta}}\big(\hat{s}_{t+1}\big)$ 中采样得到。  在论文中，这个公式体现了显式范式的核心思想，即通过分解世界模型的转移函数和观测函数来实现显式分离，使得可以独立查询每个函数。这种分解使得方法更易于解释和调试，同时更容易受到领域特定约束的影响。然而，显式方法对模型错误敏感，如果转移函数与真实情况存在显著差异，智能体的规划和决策可能会受到影响。  基于模型的强化学习算法，如MuZero或Dreamer，利用这种显式分解的范式来优化前向模型进行规划。这种方法整合了外部规划器，融合了学习和符号组件，旨在实现人类知识融入并保留深度学习优势。因此，公式在论文中扮演着展示显式范式在模型强化学习中的重要性和作用的角色。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.3 Explicit Paradigm/section/2/text
1. 基于模型的强化学习算法如MuZero或Dreamer如何通过优化前向模型来实现规划，与其他显式方法在处理未来帧生成时的不同之处在哪里？  2. 显式方法在转换和观测因式分解方面的优势是什么？然而，它们为什么容易受到模型错误的影响，以及这种敏感性可能对智能体的规划和决策产生什么影响？  3. 显式方法如何整合外部规划器来利用显式转换结构？这种学习和符号组件的融合如何实现人类知识的融入，并同时保留深度学习的优势？
基于模型的强化学习算法，如MuZero或Dreamer，通过优化用于规划的前向模型来体现这一范式。其他显式方法则优先考虑在生成未来帧时的保真度，例如Difusion WM在像素级别应用扩散过程，或者DINO-WM在预训练特征空间内展开未来状态。

通过对转换和观测进行因式分解，显式方法更易于解释和调试，也更容易受到领域特定约束的影响。尽管如此，它们仍对模型错误敏感：如果 $\hat{T}_{\theta}$ 与现实存在显著差异，智能体的规划和决策可能变得无效。许多显式系统仍主要依赖内部（神经）表示，但它们可以整合外部规划器（例如树搜索算法）来利用显式转换结构。这种学习和符号组件的融合提供了一种自然的方式来融入人类知识，同时保留了深度学习的优势。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.4 Simulator-Based Paradigm/section
基于模拟器的范式通过将环境更新外包给模拟器，使代理能够在受控环境中练习或迭代策略，而无需从数据中学习$\hat{T}_{\theta}$。这种方法有效地减轻了学习模型错误的风险，但也可能带来计算或财务上的负担。一些代理采用部分学习动态和偶尔的模拟器查询相结合的方法，以平衡准确性和状态-动作空间的高效覆盖。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.4 Simulator-Based Paradigm/section/0/text
1. 基于模拟器的范式如何通过将环境更新外包给模拟器来减轻代理学习模型错误的风险？  2. 代理采用部分学习动态和偶尔的模拟器查询相结合的方法，旨在实现什么样的平衡？  3. 在基于模拟器的范式中，为什么有些代理选择结合部分学习动态和偶尔的模拟器查询，而不是完全依赖模拟器进行环境更新？
在基于模拟器的范式中，代理将环境更新外包给模拟器，有效地绕过了需要从数据中学习$\hat{T}_{\theta}$的必要性。形式上，

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.4 Simulator-Based Paradigm/section/1/formula
$$ 
(s_{t+1},o_{t+1})\gets S T M(s_{t},a_{t}),
 $$
这个公式描述了基于模拟器的范式中的环境更新过程。在这个范式中，代理通过与模拟器进行交互，从而避免了需要从数据中学习$\hat{T}_{\theta}$的必要性。具体而言，公式中的$(s_{t+1},o_{t+1})$表示在时间步$t$执行动作$a_{t}$后，环境的状态和代理的观察值将被更新为时间步$t+1$的新状态和新观察值。这种环境更新的过程由函数$STM$完成，其中$s_{t}$是时间步$t$时的环境状态，$a_{t}$是代理选择的动作。  在论文中，这个公式的作用是展示了基于模拟器的范式中代理与环境交互的方式。通过将环境更新外包给模拟器，代理可以在受控环境中练习或迭代策略，从而有效地减轻了学习模型错误的风险。然而，这种方法可能会带来一定的计算或财务负担。因此，一些代理采用部分学习动态和偶尔的模拟器查询相结合的方法，以平衡准确性和状态-动作空间的高效覆盖。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.4 Simulator-Based Paradigm/section/2/text
1. 如何在基于模拟器的范式中平衡准确性和计算负担之间的关系？ 2. 为什么一些代理采用部分学习动态和偶尔的模拟器查询相结合的方法？ 3. 在基于模拟器的方法中，如何处理模拟器质量高、真实世界试验耗时且风险较大可能带来的挑战？
其中$s\tau{\mathcal{M}}$通常是外部的物理引擎或真实世界本身。像SAPIEN和AI Habitat这样的平台提供确定性的3D物理模拟，使代理能够在受控环境中练习或迭代策略。另外，像Daydreamer这样的方法将真实世界的交互循环视为“模拟器不断从物理机器人中更新政策数据”。这种方法产生准确的转换（假设模拟器准确反映现实），从而减轻了学习模型错误的风险。然而，如果模拟器质量高，或者真实世界试验耗时且风险较大，这种方法可能会带来计算或财务上的负担。因此，一些代理结合部分学习动态和偶尔的模拟器查询，旨在平衡准确的展开和对状态-动作空间的高效覆盖。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.5 Hybrid and Instruction-Driven Paradigms/section
混合和指导驱动范式是一种结合了隐式和显式建模的方法，或者整合了外部符号知识和大型语言模型的方法。这些系统通常从数据中提取规则，维护文本知识库或促使大型语言模型假设因果关系。例如，AutoManual迭代地将环境规则编译成人类可读的手册，以透明方式指导行动；而COAT则促使大型语言模型提出可能的因果因素，通过验证或完善这些因素，结合基于文本的推理与部分学习模型。尽管这些方法在适应陌生领域或整合实时人类见解方面具有灵活性，但在内部表示的构建或更新方面可能存在不一致。随着混合方法的发展，需要平衡端到端学习和外部指导提供的透明度和适应性。在现有世界模型技术中，这些典型范式在不同方面都存在权衡，如图4.3.5所示。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.5 Hybrid and Instruction-Driven Paradigms/section/0/text
1. 混合或指导驱动方法相比于传统方法在适应陌生领域或整合实时人类见解方面有哪些优势和灵活性？    2. 在内部表示的构建或更新方面，混合方法可能存在的不一致性是如何影响系统整体性能的？  3. 如何平衡混合方法中端到端学习和外部指导提供的透明度和适应性，以提高系统的效率和准确性？
除了这三种主要范式之外，还出现了越来越多的混合或指导驱动方法，它们混合了隐式和显式建模，或者整合了外部符号知识和大型语言模型。通常，这些系统动态地从数据中提取规则，维护不断演化的文本知识库，或者促使大型语言模型假设因果关系，然后可以对其进行测试或完善。

例如，AutoManual[108]迭代地将交互环境规则编译成人类可读的手册，以更透明的方式指导未来行动。与此同时，COAT[356]促使大型语言模型提出观察事件背后可能的因果因素，然后通过直接交互验证或完善这些因素，将基于文本的推理与部分学习模型相结合。尽管这些解决方案在适应陌生领域或整合实时人类见解方面提供了显著的灵活性，但它们在如何构建或更新内部表示方面可能存在不一致。随着语言模型提示和实时规则发现的不断发展，这些混合方法有望变得越来越普遍，体现了在端到端学习和外部指导提供的透明度和适应性之间取得平衡的需求。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.5 Hybrid and Instruction-Driven Paradigms/section/1/text
1. 现有世界模型技术中的混合和指导驱动范式如何在内部表示的构建或更新方面存在不一致性？   2. 混合方法如何平衡端到端学习和外部指导提供的透明度和适应性？   3. 在现有世界模型技术中，如何通过图4.3.5展示混合方法和指导驱动范式在不同方面的权衡？
到目前为止，我们已经介绍了现有世界模型技术的四种典型范式，如图4.3.5所示。正如我们所看到的，每种技术类型在不同方面都存在权衡。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.6 Comparative Summary of Paradigms/section
在范式比较总结中，通过对人工智能世界建模方法的分类，我们系统性地分析了这些方法对外部或内部机制的依赖程度、复杂性和各自的范式。外部方法用$\scriptscriptstyle\mathrm{~o~}$表示，内部方法用$\bullet$表示，混合方法则同时具有这两种符号。这一分类与前文的讨论一致，涵盖了每种范式的详细内容，并对图4.2中的视觉展示进行了补充。通过这种总结，我们为人工智能世界建模方法的比较提供了清晰的框架，有助于读者更好地理解不同方法之间的异同，为进一步研究和实践提供了重要参考。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.3  Paradigms of AI World Models/4.3.6 Comparative Summary of Paradigms/section/0/text
1. 人工智能世界建模方法的外部、内部和混合方法分别代表着怎样的依赖程度和复杂性？这种分类对于比较这些方法有何意义？  2. 在人工智能世界建模中，外部方法和内部方法各自代表着怎样的范式？混合方法如何结合了这两种范式的特点？  3. 这种基于外部、内部和混合方法分类的框架如何帮助读者更好地理解人工智能世界建模方法之间的异同，以及为进一步研究和实践提供了怎样的重要参考？
表格总结了人工智能世界建模中的关键方法，根据它们对外部或内部机制的依赖程度、复杂性和各自的范式进行分类。形式列使用$\scriptscriptstyle\mathrm{~o~}$表示外部方法，$\bullet$表示内部方法，混合方法则同时具有这两种符号。这种分类与前文的小节相一致，包括对每种范式的详细讨论，并补充了图4.2中的视觉呈现。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/section
在人工智能系统中，世界模型与记忆、感知和行动模块密切相关，共同构成智能代理架构的关键组件。记忆系统在世界模型中扮演重要角色，通过存储和更新对未来状态的预测性表示，实现基于上下文的推理和预测。感知模块将传感器数据转换为高级表示，为世界模型提供准确的感觉输入以进行连贯的预测。行动模块由世界模型对未来状态的预测驱动，帮助代理规划和选择最佳行动方案。跨模块集成使代理能够实时适应环境变化，世界模型提供了跨模态的基本统一原则，为不同领域之间的整合搭建桥梁。这种模块间的互动构成了智能行为的基础，强调在设计代理架构时综合考虑各模块的重要性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/section/0/text
1. 世界模型如何通过记忆系统实现对未来状态的预测性表示，从而支持基于上下文的推理和预测？ 2. 感知模块在智能代理架构中扮演怎样的角色，如何将传感器数据转换为高级表示，为世界模型提供准确的感觉输入？ 3. 行动模块是如何由世界模型对未来状态的预测驱动，帮助代理规划和选择最佳行动方案的？
综合的人工智能世界模型并不孤立存在，而是与智能代理架构的几个关键组件进行交互。这些组件包括（但不限于）记忆、感知和行动模块。在这个小节中，我们探讨世界模型如何与这些关键组件整合，以实现在动态环境中的连贯和自适应行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/section/1/figure
1. 不同的世界建模范式(a)隐式，(b)显式，(c)基于模拟器，和(d)混合/指令驱动，各自在人工智能系统中扮演着怎样的角色和功能？     2. 如何利用世界建模的四种范式来实现智能代理架构中记忆、感知和行动模块的紧密互动，以实现对环境变化的实时适应和跨模态整合？
图4.3：世界建模的四种范式：(a)隐式，(b)显式，(c)基于模拟器，和(d)混合/指令驱动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/section/2/text
1. 跨范式的AI世界模型方法在形式、复杂性和范式上有何特点和差异？ 2. 如何利用跨范式的AI世界模型方法实现智能代理架构中的记忆、感知和行动模块之间的协同作用？ 3. 跨范式的AI世界模型方法如何为不同领域之间的整合提供基本统一原则，并促进智能代理架构的设计与优化？
表4.1：跨范式的AI世界模型方法总结，显示它们的形式（外部或内部）、复杂性和范式。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.1 Memory and the World Model/section
记忆系统在世界模型中扮演关键角色，通过存储和更新对未来状态的预测性表示。世界模型和记忆相互作用，构成一个循环：世界模型预测未来，而记忆存储过去经验，实现基于上下文的推理和预测。记忆可分为短期和长期记忆，前者暂时维持内部状态，助力即时决策；后者则存储更持久的经验和知识，与世界模型互动以提升预测能力。在Dreamer等框架中，循环神经网络同时担当世界模型和记忆，维护潜在状态以预测未来，实现过去互动的回忆和未来互动的预测。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.1 Memory and the World Model/section/0/text
1. 记忆系统在世界模型中的循环作用中扮演着怎样的关键角色，以及这种循环如何促进代理的推理和预测能力？ 2. 在记忆系统中，短期记忆和长期记忆各自的功能是什么，它们是如何相互作用以提升代理的决策能力和预测准确性的？ 3. Dreamer等框架中的循环神经网络是如何同时扮演世界模型和记忆的角色，以实现基于过去经验的回忆和未来预测的功能的？
记忆系统在世界模型的运作中起着至关重要的作用。世界模型生成对未来状态或行为的预测性表示，而记忆则作为这些表示构建和更新的基础。世界模型和记忆之间的关系可以被视为一个循环，其中世界模型预测潜在的未来，而记忆存储过去的经验、观察和学习模式，实现依赖于上下文的推理和未来预测。

记忆机制可以以各种方式结构化，包括：

· 短期记忆：这使代理能够临时保持和更新其内部状态，存储最近的互动或观察。这种短期上下文有助于代理在即时环境中做出决策。
· 长期记忆：这充当了对环境的经验和一般知识更持久的存储库。世界模型可以与长期记忆互动以完善其预测，并可能使用历史数据做出更明智的决策或模拟更现实的未来。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.1 Memory and the World Model/section/1/text
1. 在基于模型的强化学习框架中，循环神经网络同时扮演世界模型和记忆的角色，这种集成记忆形式如何帮助代理实现对过去互动的回忆和未来互动的预测？ 2. Dreamer框架中的循环神经网络是如何维护一个潜在状态，并在每个时间步更新以预测未来状态的？这种方法相较于传统的记忆形式有何优势和局限性？ 3. 论文提到的循环神经网络在Dreamer框架中的双重角色，即兼任世界模型和记忆，如何实现基于上下文的推理和预测？这种双重角色如何影响代理的决策过程和学习效果？
例如，在基于模型的强化学习框架中，如Dreamer，循环神经网络既充当世界模型，又作为一种记忆形式，维护一个潜在状态，该状态在每个时间步更新以预测未来状态。这种集成记忆形式使代理能够回忆过去的互动并预测未来的互动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.2  Perception and the World Model/section
在智能代理中，感知是指其通过各种方式感知和解释环境的能力，而世界模型则依赖于准确的感觉输入以进行连贯的预测。感知模块将传感器数据转换为高级表示，如图像或声波。世界模型利用处理后的数据模拟未来，并通过集中注意力引导感知过程。在自主机器人领域，感知系统检测特征并输入世界模型进行场景预测。RoboCraft和PointNet通过转换视觉观察和编码点云来丰富感知系统对环境理解。OVER-NAV结合语言模型和词汇检测构建omni-graph来捕获导航任务的空间结构。这种感知和模型之间的反馈循环使代理能够实时适应环境。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.2  Perception and the World Model/section/0/text
1. 代理如何将感觉输入处理和整合到世界模型中，以实现对环境的连贯预测？ 2. 在自主机器人领域中，RoboCraft和PointNet是如何丰富感知系统对环境理解的？ 3. OVER-NAV如何利用语言模型和词汇检测构建omni-graph来捕获导航任务的空间结构，以实现感知和世界模型之间的反馈循环？
感知是指智能代理通过各种方式（例如视觉、触觉、听觉等）感知和解释其环境的能力。世界模型在很大程度上依赖于准确的感觉输入，以对环境进行连贯的预测。在许多人工智能系统中，感知模块将原始传感器数据转换为更高级别的表示，例如图像、声波或其他结构化数据。

世界模型与感知之间互动的关键方面是代理如何将感觉输入处理和整合到模型中。世界模型通常依赖于经过处理的数据（例如来自卷积神经网络的特征或来自变压器的嵌入）来模拟潜在的未来。此外，世界模型可以通过集中注意力于最相关的感官输入来引导感知过程，以细化预测所需的最相关感觉输入。

例如，在自主机器人领域，感知系统通常检测物体或环境特征，然后将其输入到预测场景将如何发展的世界模型中。RoboCraft通过将视觉观察转换为粒子并通过图神经网络捕获基础系统结构，实现了这种感知到建模的转换。PointNet通过对无结构的3D点云进行编码来进一步丰富感知系统对物理空间的理解，以捕获环境的空间特征。在导航任务中，OVER-NAV进一步结合大型语言模型和开放词汇检测，构建多模态信号和关键信息之间的关系，提出omni-graph来捕获导航任务的本地空间结构作为世界模型。感知和世界模型之间的这种反馈循环使代理能够根据持续的预测动态更新其感知，实现实时适应。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.3 Action and the World Model/section
在代理系统中，行动是由世界模型对未来状态的预测驱动的，帮助代理规划并选择最佳行动方案。世界模型与行动模块整合方式多样，包括基于模型的规划和探索策略。MuZero通过自我对弈和MCTS进行隐式规划，指导决策过程；MPC利用显式动态模型预测多条可能轨迹并持续更新规划；Alpha-SQL整合LLM作为行动模型进行SQL查询构建。探索策略方面，代理可通过奖励机制激励探索未知区域，如Dreamer利用虚构展开评估新行动的好处。在强化学习中，代理利用学习的世界模型模拟未来轨迹，评估潜在奖励，有效规划并实现长期目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.3 Action and the World Model/section/0/text
1. 代理系统中的行动是如何由世界模型对未来状态的预测驱动的，以帮助代理规划并选择最佳行动方案的？ 2. 不同的整合方式中，基于模型的规划和探索策略分别如何影响代理系统的决策过程和探索行为？ 3. MuZero、MPC和Alpha-SQL分别采用怎样的方法整合世界模型和行动模块，以指导决策过程和规划行动？这些方法各自的优势和适用场景是怎样的？
行动是指代理通过决策过程与环境进行交互的过程。在代理系统中，行动是由世界模型对未来状态的预测驱动的。世界模型通过在执行之前模拟不同行动的结果来帮助规划，使代理能够根据预测的后果选择最优行动方案。

世界模型与行动模块之间的整合可以采用各种形式：

- 基于模型的规划：世界模型明确地建模环境的转换动态，允许代理在选择最优方案之前模拟多个行动序列（展开）。 
- 探索：世界模型还通过模拟未见状态或意外行动来支持探索策略。这些模拟使代理能够评估探索状态空间新部分的潜在收益。

在基于模型的规划中，MuZero通过自我对弈和蒙特卡洛树搜索（MCTS）进行隐式规划，将当前状态表示转化为未来状态和奖励预测，以指导决策过程，而无需了解环境规则。相比之下，MPC利用显式动态模型来预测有限时间范围内的多条可能轨迹，通过解决优化问题确定最优控制序列，并使用逐步更新的方法持续更新规划。另一方面，Alpha-SQL在MCTS框架内集成了LLM作为行动模型，以探索数据库“世界模型”中的潜在SQL查询。该方法根据部分查询状态动态生成有前途的SQL构建行动，实现了无需特定任务微调的零-shot文本到SQL交互。与专注于不确定环境中决策规划的MuZero不同，Alpha-SQL在特定任务中应用MCTS，通过在复杂数据库环境中自动生成行动来指导SQL查询构建。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.3 Action and the World Model/section/1/text
1. 探索奖励在代理系统中的作用是什么，如何激励代理进行未知区域的探索？ 2. Dreamer中提出的虚构展开在评估新行动方面有何优势？如何帮助代理规划最佳行动？ 3. 在离散世界模型中，Hafner等人如何通过模拟多个可能的未来状态来平衡探索和利用之间的权衡？
对于探索策略，Nagabandi等人通过提供奖励机制（探索奖励）来激励代理探索未知区域，以发现新状态。Dreamer提出，世界模型可以生成虚构的行动序列（虚构展开），使代理可以在模拟环境中安全评估新行动的好处，而无需冒真实世界实验的风险。类似地，在离散世界模型中，Hafner等人通过模拟多个可能的未来状态，代理可以高效地探索复杂环境，有效平衡探索和利用之间的权衡。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.3 Action and the World Model/section/2/text
1. 代理系统中如何利用学习的世界模型来评估不同行动的潜在奖励，从而实现有效规划并最大化长期目标？ 2. 在代理系统中，基于模型的规划和探索策略各有何优劣，如何影响代理的决策过程和行动选择？ 3. 强化学习中的世界模型对于代理系统的长期目标实现有何重要性，不同整合方式如MuZero、MPC和Alpha-SQL又如何影响代理的决策能力？
例如，在强化学习中，代理可以利用学习的世界模型来模拟行动选择任务中的未来轨迹。世界模型评估不同行动的潜在奖励，使代理能够有效规划并采取最大化长期目标的行动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.4 Cross-Module Integration/section
本节探讨了跨模块集成在人工智能系统中的关键作用。虽然记忆、感知和行动被视为独立模块，但世界模型的优势在于它们能够实现无缝集成，通过不断接收感官输入、更新内部记忆、模拟未来状态，并驱动行动选择。这种跨模块交互使代理能够高度适应环境变化，特别在机器人技术领域中显得尤为重要。世界模型提供了跨模态的基本统一原则，通过预测不同行动下状态的演变来解释人类在处理物体、界面导航和语言之间的流畅转换。未来的人工智能系统可能通过发展世界模型，建立不同领域之间的桥梁，实现整合。总体而言，世界模型与其他模块之间的互动构成了人工智能系统智能行为的基础，强调了在设计代理架构时综合考虑世界模型、感官输入、记忆系统和决策过程的重要性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.4 Cross-Module Integration/section/0/text
1. 世界模型如何实现记忆、感知和行动之间的无缝集成，以促使代理在复杂、动态系统中高度适应环境变化？    2. 在人工智能系统中，世界模型如何通过预测不同行动下状态的演变来解释人类在处理物体、界面导航和语言之间的流畅转换？   3. 未来的人工智能系统如何可以通过发展世界模型，建立不同领域之间的桥梁，实现整合？
虽然记忆、感知和行动被讨论为独立模块，但世界模型真正的优势在于它们能够在这些领域之间无缝集成。世界模型不断接收感官输入，更新内部记忆，模拟未来状态，并利用这些信息来驱动行动选择。这些模块之间的迭代反馈循环使代理能够参与智能、目标导向的行为，高度适应环境变化。

这种跨模块交互在复杂、动态系统中尤为重要，例如在机器人技术领域，代理必须持续调整其对世界的内部表征、处理感官输入、存储相关经验，并实时采取行动。在具身代理的背景下，这些模块的整合确保了世界模型所做的预测基于当前观察和代理持续的经验。

世界模型提供了跨模态的基本统一原则。无论是在具身机器人中预测物理结果，在屏幕上预测视觉变化，还是在文本中推断语义关系，核心机制保持一致：生成关于不同行动下状态如何演变的预测。这种跨模态能力解释了为什么人类能够毫不费力地在操作物体、导航界面和处理语言之间转换——所有这些活动都由相同的基础预测架构驱动。未来的人工智能系统可能通过开发能够通过共同的预测框架在这些传统上独立的领域之间建立桥梁的世界模型，实现类似的整合。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.4 Relationships to Other Modules/4.4.4 Cross-Module Integration/section/1/text
1. 人工智能系统中的世界模型如何与感知、记忆和行动模块相互作用，从而构成智能行为的基础？ 2. 在设计代理架构时为什么需要综合考虑世界模型、感官输入、记忆系统和决策过程，以实现在动态和不确定环境中的有效运作？ 3. 世界模型在人工智能系统中如何提供跨模态的基本统一原则，以促进物体处理、界面导航和语言之间的流畅转换？
总之，世界模型与其他模块——记忆、感知和行动之间的关系构成了人工智能系统智能行为的基础。每个模块都为预测、更新和行动的循环做出贡献，使代理能够在动态和不确定的环境中有效地运作。这些互动凸显了在设计代理架构时需要采用整体方法的重要性，其中世界模型与感官输入、记忆系统和决策过程紧密相互交织。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.5 Summary and Discussion/section
本节总结了从早期认知洞见到先进人工智能架构的AI世界模型演变过程。世界模型的关键在于其跨越多个时间和空间尺度的运作，人类的心智模型展现了在不同尺度上处理信息的灵活性。设计世界模型时的核心挑战在于复杂性与预测准确性之间的平衡，隐式、显式和基于模拟器的方法各有优劣。泛化和专业化之间的权衡是关键主题，长期记忆与世界模型的结合对智能体至关重要。未来的挑战包括确保世界模型在真实环境中的稳定性和可靠性，以及设计高效可扩展的系统来处理复杂任务。最终，世界模型的未来在于平衡泛化需求和对领域专业知识的要求，不断探索简单性与复杂性之间的平衡，以开发能够理解和塑造世界的人工智能系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.5 Summary and Discussion/section/0/text
1. 人们如何通过AI世界模型的演变过程逐渐认识到真正智能的基础在于能够预测、模拟和想象？这种认知建模的飞跃如何影响代理的规划、预测和适应能力？  2. 在设计世界模型时，隐式、显式和基于模拟器的方法各有何优劣？这些方法如何影响机器在跨任务的灵活性、稳健性和泛化能力方面的表现？  3. 未来的挑战中，如何平衡世界模型在真实环境中的稳定性和可靠性？探索简单性与复杂性之间的平衡如何有助于开发能够理解和塑造世界的人工智能系统？
从早期认知洞见到先进人工智能架构的AI世界模型演变，凸显了人们日益认识到真正智能的基础在于能够预测、模拟和想象。与经典的强化学习不同，代理通过试错交互操作，世界模型使预见成为可能，代理可以在事件发生之前进行规划、预测和适应。这种认知建模的飞跃——无论是隐式的、显式的还是基于模拟器的——标志着机器如何获得跨任务的灵活性、稳健性和泛化能力方面的重大转变。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.5 Summary and Discussion/section/1/text
1. 人类心智模型如何展现了在不同时间尺度上处理信息的灵活性？这种多尺度能力对于预测和目标实现有何重要意义？ 2. 人工智能世界模型在处理时间和空间信息时存在怎样的局限性？如何可以提高人工智能系统在不同时间尺度和空间分辨率上的预测能力？ 3. 在设计通用的人工智能世界模型时，需要考虑哪些关键因素来整合跨多个时间范围和空间分辨率的预测？如何实现动态调整模拟的粒度以适应不同任务的要求？
世界模型的一个重要但经常被忽视的方面是其跨越多个时间和空间尺度的运作。人类的心智模型无缝地整合了跨越毫秒（反射性反应）、秒（即时行动规划）、分钟到小时（任务完成）甚至年（生活规划）的预测[366]。这种多尺度能力使我们能够同时预测即时的物理动态，同时保持连贯的长期叙事和目标。类似地，人类在不同尺度上处理空间信息——从细粒度的物体操作到跨越环境的导航再到抽象的地理推理。当前的人工智能世界模型通常在狭窄的时间和空间范围内表现出色，而人类认知在根据情境要求调整预测的尺度上表现出卓越的灵活性。这表明，真正通用的人工智能世界模型可能需要明确的机制来整合跨多个时间范围和空间分辨率的预测，根据任务要求动态调整模拟的粒度。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.5 Summary and Discussion/section/2/text
1. 隐式模型在设计世界模型时所面临的可解释性挑战如何影响其在复杂性和预测准确性之间的平衡？ 2. 在探讨复杂性与预测准确性之间的平衡时，基于循环神经网络或Transformer的隐式模型如何应对过拟合和泛化到未见场景的挑战？ 3. 如何在设计世界模型时有效利用隐式模型的优势，同时克服其内部状态不透明性所带来的约束执行和预测准确性保证方面的困难？
设计世界模型时面临的一个核心挑战是复杂性和预测准确性之间的相互作用。正如讨论的那样，隐式模型，如基于循环神经网络或Transformer的模型，提供了简单和优雅，但它们往往伴随着有限的可解释性。模型的内部状态是不透明的潜在空间，这使得很难强制执行领域约束或提供关于预测准确性的保证。虽然这种系统擅长捕捉高度复杂的关系和数据驱动的模式，但它们也面临过拟合或无法推广到未见场景的风险。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.5 Summary and Discussion/section/3/text
1. 显式模型相比其他方法具有更大的透明度和控制性，但在处理复杂环境时可能会遇到哪些挑战？ 2. 在设计人工智能系统时，如何权衡显式模型所提供的透明度和控制性与其在复杂环境中可能遇到的困难之间的平衡？ 3. 在处理高维状态表示的复杂环境时，为什么即使是最结构良好的显式模型也可能遇到困难？
相比之下，显式模型提供了更大的透明度和控制。通过将状态转换和观测分解为单独的函数，我们更清晰地了解了预测是如何形成的，并且可以更容易地整合结构化知识，比如物理定律或领域特定规则。然而，这种方法也带来了自己一套挑战。首先，通常需要大量标记的训练数据或模拟经验来准确捕捉环境动态。其次，即使是最结构良好的显式模型在需要精细化、高维状态表示的复杂环境中也可能遇到困难，比如在视频预测或机器人技术中。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.5 Summary and Discussion/section/4/text
1. 基于模拟器的方法在构建世界模型时具有哪些优势和局限性？如何平衡这些优势和局限性以提高AI代理在复杂环境中的表现能力？ 2. 在实际环境中，模拟器与真实世界的差距如何影响AI代理的世界模型的鲁棒性？如何解决这种差距所带来的挑战？ 3. AI代理在面对开放、不可预测的环境时，为何需要考虑模拟器和实际环境之间的差异？如何确保AI代理的世界模型能够在这样的挑战中保持稳定性和可靠性？
基于模拟器的方法提供了一种有前途的替代方案，代理依赖外部环境（无论是物理接地的还是模拟的）进行动态更新。这种方法避免了从头开始学习准确世界模型固有的许多挑战，因为模拟器本身充当了状态转换和观测的“神谕”。然而，对模拟器的依赖也带来了限制：模拟器经常无法捕捉真实世界动态的全部丰富性，并且在维护或扩展方面可能会具有计算上的昂贵性。此外，真实世界环境引入了噪声和变异性，纯学习或预配置模型可能会忽略这些因素。随着AI代理努力在开放、不可预测的环境中执行任务，他们的世界模型的鲁棒性将受到模拟和实际环境之间差距的考验。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.5 Summary and Discussion/section/5/text
1. 在人工智能领域中，泛化和专业化之间的权衡对于世界模型的设计至关重要。在设计世界模型时，如何平衡泛化能力与领域专业知识的需求，以实现更好的性能表现？  2. 从MuZero和Dreamer等专门化模型到利用大规模神经网络的隐式模型，不同类型的世界模型在泛化和专业化方面存在着优劣势。如何评估不同模型在不同任务背景下的适用性，以便在实际应用中做出合适的选择？  3. 长期记忆与世界模型的结合被指出对于智能体至关重要。在设计人工智能系统时，如何有效整合长期记忆与世界模型，以促进智能体在复杂任务中的表现和学习能力？
从这个讨论中浮现出的一个关键主题是泛化和专业化之间的权衡。世界模型越专门化到特定领域或任务，就越不太可能在不同背景下进行泛化。MuZero和Dreamer等模型就是这样的示例：它们在特定环境（如Atari游戏或机器人技术）中表现出色，但在转移到新的、未知领域时需要仔细调整。相反，隐式模型——特别是那些利用大规模神经网络的模型——有可能在任务之间进行泛化，但通常是以牺牲领域特定专业知识为代价。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.5 Summary and Discussion/section/6/text
1. 长期记忆如何对智能体在处理长期依赖和过往经验时起到至关重要的作用？ 2. 在世界模型中，如何通过结合记忆、感知和行动来实现对环境的更广泛理解？ 3. 预测、行动和记忆之间的反馈循环如何促进智能体对未来结果的推理能力？
此外，将记忆与世界模型相结合对于需要处理长期依赖和过往经验的智能体至关重要。尽管世界模型擅长基于即时输入预测下一个状态，但真正的智能行为通常需要对远期结果进行推理。长期记忆使智能体能够存储关键的环境知识，确保短期预测建立在对世界的更广泛理解之上。这种记忆、感知和行动的融合，通过世界模型中介，创建了一个反馈循环，其中预测塑造行动，进而影响未来的预测。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.5 Summary and Discussion/section/7/text
1. 在设计智能体的世界模型时，如何平衡隐式、显式和基于模拟器的方法，以实现更强大、更具普适性和适应性的智能体？    2. 在探索世界模型的发展过程中，如何结合学习到的知识与结构化规则以及实时交互，从而推动智能体的发展和提升其能力？    3. 未来如何确保智能体的世界模型在真实环境中的稳定性和可靠性，以及如何设计高效可扩展的系统来处理复杂任务？
人类类比仍然令人信服：正如人类整合感官输入、记忆和内部模型以在世界中导航一样，智能体也必须通过它们的世界模型结合感知、记忆和行动。随着领域的发展，很明显，一种整体方法——将隐式、显式和基于模拟器的方法统一起来——可能是实现更强大、更具普适性和适应性的智能体的关键。混合方法，例如AutoManual中使用的方法或基于发现的模型，为将学到的知识与结构化规则和实时交互相融合提供了令人兴奋的可能性，潜在地推动了我们所认为的世界模型的边界。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/4 Communication Topology 141/4.5 Summary and Discussion/section/8/text
1. 如何确保人工智能世界模型在真实环境中保持长期稳定性和可靠性？这涉及哪些关键挑战和解决方案？    2. 在面对动态环境中的不确定性时，人工智能系统如何保持适应性的灵活性？有哪些策略可以帮助系统有效地适应环境变化？  3. 随着智能体变得更加复杂，如何设计高效可扩展的系统来处理日益复杂的任务？这种系统设计需要考虑哪些因素，以平衡计算成本和任务需求？
展望未来，一些问题仍然悬而未决。我们如何确保世界模型在真实世界环境中表现出长期稳定性和可靠性？在处理动态环境中固有的不确定性的同时，如何保持适应性的灵活性？此外，随着智能体变得更加复杂，我们如何设计既高效又可扩展的系统，以处理日益复杂的任务，而又不带来巨大的计算成本？

总之，世界模型的未来在于它们在平衡泛化需求和对领域专业知识的要求方面的能力。通过不断探索和完善模型简单性和复杂性之间的相互作用，以及外部和内部方法之间的关系，我们逐渐接近开发出能够不仅理解世界，而且能够积极塑造他们的理解以在快速变化的现实中导航和适应的人工智能系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/l5 Collaboration Paradigms and Collaborative Mechanisms 146/section
15.1 智能代理间的协作 146 15.2 人类与人工智能的协作 149 15.3 协作决策制定 150

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/l5 Collaboration Paradigms and Collaborative Mechanisms 146/section/0/text
1. 智能代理间的协作如何促进人工智能系统的性能提升和任务完成效率？ 2. 在人类与人工智能的协作中，如何平衡人类的主观决策能力和人工智能系统的客观分析能力？ 3. 协作决策制定过程中，如何确保不同智能代理之间的信息共享和交流，以提高整体决策的准确性和效率？
15.1 智能代理间的协作 146
15.2 人类与人工智能的协作 149
15.3 协作决策制定 150

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collective Intelligence and Adaptation 152/section
16.1 集体智能 152 16.2 个体适应性 153

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collective Intelligence and Adaptation 152/section/0/text
1. 集体智能在群体中是如何形成和发挥作用的？ 2. 个体适应性在群体中的角色是什么，它如何影响整个集体的表现和效果？ 3. 集体智能与个体适应性之间存在怎样的相互关系和平衡？
16.1 集体智能 152
16.2 个体适应性 153

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/section
本章节聚焦于评估多Agent系统，首先介绍了特定推理任务的基准，包括代码推理、知识推理、数学推理和社会仿真基准，强调多方面评估框架的重要性。随后，探讨了挑战与未来工作，指出多Agent系统在复杂任务上的优势和计算成本之间的平衡，提出了有效的任务路由机制和代理连接建立等关键问题，为未来MAS评估的发展指明了方向。这些挑战和展望为推动智能代理系统评估提供了重要参考，促进了该领域的持续发展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/section/0/text
1. 多Agent系统在复杂任务上的优势和计算成本之间如何平衡？ 2. 未来MAS评估中的任务路由机制和代理连接建立等关键问题如何影响系统性能？ 3. 本章节提到的特定推理任务的基准如何帮助评估多Agent系统的性能和效果？
17.1 特定推理任务的基准 155
17.2 挑战与未来工作 159

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section
在解决任务的多智能体系统中，关注利用多智能体协调增强LLMs的推理能力。代码推理基准着重于正确编写代码和功能性验证，使用$p a s s@k$指标评估合成代码正确性。知识推理基准考察智能体应用事实知识和逻辑推理解决问题的能力，如CSQA和ScienceQA。数学推理基准挑战智能体使用数学知识和逻辑推理，包括SVAMP和PISA数据集。社会仿真基准评估智能体在模拟人类行为和社会互动方面的性能，如SOTOPIA和AvalonBench。评估方法逐渐过渡到多方面评估框架，包括协作成功、推理能力和系统效率等多个维度。以协作为重点的基准关注智能体间通信和协调，如Collb-Overcooked和AgentBench。以竞争为重点的基准评估智能体战略能力和对抗性互动，如Human Simulacra和PokerBench。自适应和韧性基准考虑智能体动态适应和系统韧性，如AdaSociety和REALM-Bench。这些基准反映了对多智能体系统综合评估的需求，涵盖了协作、竞争、自适应和韧性等不同方面，为智能体能力的全面评估提供了框架。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/0/text
1. 多智能体系统中如何利用协调来增强LLMs的推理能力？这种协调在编码、知识和数学推理基准中如何体现，以及如何通过分布式求解来检验和改进？  2. 在多智能体系统中，如何通过结构化工作流程、特定领域智能体角色和对性能的迭代改进来取得显著进步？相比之下，在模型和仿真多智能体系统中存在哪些缺乏标准化基准的挑战？  3. 多智能体系统中的基准评估框架如何影响任务、评估措施以及系统通过哪些核心机制实现更好性能？
在解决任务的多智能体系统中，人们更多关注利用多智能体协调来增强LLMs的推理能力。这在编码、知识和数学推理基准方面表现得最为明显，人们希望通过分布式求解的性能来检验和改进。这些基准通常检验智能体是否能够正确编写代码，在复杂知识领域进行推理，并解决困难的数学问题，其中常见的度量如$p a s s@k$或成功的证明比率。通过结构化工作流程、特定领域智能体角色和对最新性能的迭代改进，多智能体系统已取得了很大进步。相反，在模型和仿真多智能体系统中，情况则是缺乏标准化基准。相反，研究主要是实验设置，模拟各种社会现象，社区呼吁进一步制定评估框架。下面将描述这些多个基准领域，检查任务、评估措施以及多智能体系统通过哪些核心机制实现更好的性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/1/text
1. 代码推理基准如何帮助衡量LLMs在代码合成方面的能力，相较于自然语言合成有何优势？ 2. 基准套件中的编程问题是如何构建的，以确保自动生成的代码的正确性？ 3. 在代码推理基准中，为什么重点关注功能正确性，而不是其他方面的性能指标？
代码推理基准
衡量LLMs在代码合成方面的能力需要专门的基准套件，重点关注功能正确性。与自然语言合成相比，代码合成允许通过运行直接验证。为此目的构建了几个基准套件，通常包括一系列编程问题，每个问题都有自然语言问题描述以及一组测试用例，用于自动确定合成代码的正确性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/2/text
1. 基于$p a s s@k$指标的多智能体系统评估方法有哪些优势和局限性？如何确保该指标在不同问题和难度下的有效性？  2. HumanEval、APPS和MBPP等基准套件如何促进了多智能体系统的综合评估？这些基准套件如何确保覆盖了各种难度和编程抽象，以及对代码正确性和逻辑正确性的要求？  3. 在多智能体系统的评估中，如何结合不同基准套件（如CSQA、SVAMP、Collb-Overcooked等）以实现对智能体能力的全面评估？这种综合评估框架如何促进了对协作、竞争、自适应和韧性等方面的全面考量？
HumanEval、APPS和MBPP是一些流行的基准套件。这些基准套件主要使用$p a s s@k$指标，该指标计算在顶部$k$个生成的解决方案中至少有一个通过所有测试用例的百分比，适用于多个问题。通过这些基准套件涵盖的问题涵盖了各种难度和编程抽象，不仅要求LLMs和Agents，还要求符合语法正确和逻辑正确、满足提供的测试用例的代码。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/3/text
1. 如何利用多智体系统来增强LLM在代码推理方面的能力？MetaGPT和SWE-agent分别采用了怎样的方法来提高性能，并在哪些基准测试中取得了最先进的表现？  2. AgentCoder是如何通过三智体系统来实现有效测试和自动优化的？这种多智体编码系统如何提升了软件工程能力，与其他系统相比具有何种优势？  3. 在研究中提到的MetaGPT、SWE-agent和AgentCoder分别如何利用不同领域的多智体角色分配、Agent-Computer Interface（ACI）和三智体系统来提升代码推理能力？这些方法如何为多智体系统的发展提供了新的思路和启示？
最近的研究探讨了利用多智体系统（MAS）来增强LLM在代码推理方面的能力。例如，MetaGPT是一个元编程系统，将类似人类的标准操作规程（SOPs）嵌入到基于LLM的多智体合作中。通过采用不同领域的多智体角色分配和采用流水线模式，MetaGPT有效地将复杂操作分解为子操作，并在HumanEval和MBPP基准测试中实现了最先进的性能。SWE-agent提出了一种新颖的Agent-Computer Interface（ACI），大大增强了代理的创建、编辑和导航能力。该系统表明，为LM量身定制的良好结构化界面可以大大增强软件工程能力，在SWE-bench和HumanEval上处于领先地位。AgentCoder是另一个以有效测试和自动优化为重点的多智体编码系统。它是一个由程序员、测试设计师和测试执行者组成的三智体系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/4/text
1. 测试设计者如何提高多智能体系统的编码效率？这种协作工作流如何在代码推理任务中表现优于其他方法？ 2. 为什么多智能体系统方法中强调多智能体合作、组织良好的工作流程和量身定制的界面对增强LLM在代码推理方面能力的有效解决策略？ 3. DEVAI提出的评判-智体机制如何帮助自动评判中间开发过程，从而提高AI开发的自动化效率？
测试设计者提供准确且多样化的测试用例，而测试执行者为程序员提供优化反馈。这种协作工作流提高了编码效率，并在HumanEval和MBPP数据集上表现优于单一智体模型和其他多智体方法。这些多智体系统方法都指出多智体合作、组织良好的工作流程和量身定制的界面作为增强LLM在代码推理方面能力的有效解决策略。DEVAI提出了一组新颖的AI开发自动化基准，利用评判-智体机制来自动评判中间开发过程。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/5/text
1. 知识推理基准如CSQA和ScienceQA如何评估智能体在回答具有挑战性问题时利用事实知识和逻辑推理的能力？这种评估如何帮助智能体逐步从输入查询推进到输出答案的逻辑推理过程？  2. 多智体系统中利用LLM提高知识推理任务性能的策略有哪些？以MASTER和Reflexion为例，它们是如何结合智体招募流程、通信协议和蒙特卡洛树搜索算法来提高准确率的？  3. 外部工具如搜索引擎在提高知识推理能力中的作用是什么？智能体如何利用搜索引擎来获取最新信息、进行事实核查以提高回答的准确性和可靠性？
知识推理基准为促进人工智能智能地行动和理解世界提供了必不可少的稳健知识推理能力。这一类基准评估了智能体在回答具有挑战性的问题时利用事实知识和逻辑推理的能力。常识推理通过基准（如CSQA[1079]和StrategyQA[1080]）进行测试，科学知识理解则通过ScienceQA[1081]进行测试。对智能体的核心挑战在于进行多步骤、思维链式推理，逐步从输入查询推进到输出答案的逻辑推理过程。这些测试集中评估特定人工智能智能体能够逐一应用特定知识体系并推理解决问题的能力。最近的研究尝试在多智体系统上使用LLM来提高知识推理任务性能，并取得了最先进的准确性。例如，MASTER[109]，一种新颖的多智体系统，采用了一种新颖的智体招募流程和使用蒙特卡洛树搜索（MCTS）算法的通信协议，在HotpotQA[940]上实现了76%的准确率。Reflexion[48]是一个通用框架，将推理和行动与语言模型结合在一起，提高了HotpotQA基线20%的准确率。这些策略展示了多智体协调在知识推理任务中的潜力。此外，利用外部工具，如搜索引擎，也是提高知识推理能力所必需的。智能体可以利用这些工具来获取最新信息，进行事实核查，从而提高回答的准确性和可靠性。这种整合在诸如TriviaQA[1082]之类需要实时信息访问的应用中尤为有用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/6/text
1. 数学推理基准如何挑战智能体的数学问题解决能力和计算机辅助定理证明能力？在这两类任务中，智能体需要具备哪些关键技能和能力？  2. 多智体系统在处理数学推理问题复杂性方面有哪些潜在解决方案？MACM方法中的思考者、裁判和执行者代理分别承担怎样的角色，如何协同工作来提高问题解决的准确性？  3. 在数学推理基准测试中，采用多智体辩论等方法如何帮助提高集体解决方案的推理和事实准确性？强化学习和偏好学习策略如何结合以进一步提升LLM的数学问题解决能力？
数学推理基准
数学推理是人工智能智能体的关键技能，需要协同利用数学知识、逻辑推理和计算能力。针对这种能力的基准任务通常分为两类：数学问题解决和计算机辅助定理证明（ATP）。诸如SVAMP、GSM8K和MATH等数据集挑战智能体解决文字问题，要求给出确切的数字答案或公式。ATP是一个更难的测试，需要更严格地遵守形式化证明模式。类似PISA和miniF2F的数据集测试智能体是否能够生成形式良好的数学证明，评分依据是证明的完成情况。多智体系统被提出作为处理数学推理问题复杂性的潜在解决方案。诸如MACM等方法包括一个多智体系统，由思考者、裁判和执行者代理组成，针对复杂问题进行定制，将其分解为较小的子问题以进行计算。思考者代理生成新思路，裁判决定其准确性，执行者进行必要的计算，包括使用计算器等工具。这种模块化结构支持迭代的改进和错误消除，提高问题解决的准确性。此外，诸如多智体辩论等方法包括多个语言模型实例进行辩论和迭代重新聚焦，以提高集体解决方案的推理和事实准确性。这种基于多智体系统的系统在MATH和GSM8K等基准测试中取得了显著改进，为解决数学问题建立了分布式解决能力。除此之外，还尝试了从人类反馈中进行强化学习（RLHF）和偏好学习策略，以进一步提升LLM的数学问题解决能力。例如，提出了一种多轮在线迭代直接偏好学习框架，用于在GSM8K和MATH数据集上训练各种语言模型。该技术包括解释者对代码的反馈，并在轨迹级别优化偏好，显著提高了输出结果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/7/text
1. 社会仿真基准如何帮助评估基于LLM的多智能体系统在模拟人类行为和社会互动方面的性能和逼真度？ 2. SOTOPIA基准是如何评估智能体在虚拟社会中进行对话、理解社交线索以及建立彼此关系的能力的？ 3. 多智能体基准中的狼人和讨价还价仿真领域是如何用于评估不同智能体群体之间具有冲突目标的竞争性互动的？
社会仿真基准 社会仿真基准对于评估基于LLM的多智能体系统在模拟人类行为和社会互动方面的性能和逼真度至关重要。通过这些基准，为评估智能体在模拟社会中相互作用、沟通和演化的能力提供了标准化的集合和测试用例。其中一个广泛使用的基准示例是SOTOPIA [1086]，用于评估自然语言智能体的社会智能。它用于评估智能体在虚拟社会中进行对话、理解社交线索以及建立彼此关系的能力。另一个基准涉及在社交网络中模拟“性别歧视”和“核能”话题的传播。它用于评估智能体在大规模社交网络中建模意见动态、信息传播和社会影响的能力。多智能体基准 [948] 还提供了两个仿真领域——狼人和讨价还价——用于评估不同智能体群体之间具有冲突目标的竞争性互动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/8/table
1. 在多智能体系统评估框架中，为什么需要同时关注任务导向性能和系统级能力？这两方面的评估如何相互补充，有何意义？  2. 在MAS基准测试中，不同类型的基准测试（如知识推理、数学推理、社会仿真等）分别考察了多智能体系统的哪些方面能力？这些基准测试如何帮助实现对多智能体系统能力的全面评估？
表17.1：MAS基准测试：按任务导向性能和系统级能力分类的多智能体系统评估框架。这个全面的集合包括专门的任务解决基准测试和整体能力评估，反映了多智能体系统评估在协作问题解决和智能体间动态中的双重性质。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/9/text
1. 多智能体系统评估方法从单一维度指标向多方面评估框架的转变背后，反映了什么样的认识和需求？ 2. 在评估基于LLM的多智能体系统能力时，为什么需要专门的方法来有效衡量智能体之间的丰富互动？ 3. 在多智能体系统评估中，如何确保评估框架能够全面捕捉到智能体互动所需的复杂技能集？
评估基于LLM的多智能体系统的能力需要专门的方法，可以有效地衡量智能体之间丰富的互动。随着这一领域的发展，评估方法已经从单一维度的指标过渡到多方面的评估框架，捕捉到有效多智能体互动所需的复杂技能集。这种演变反映了人们日益增长的认识，即智能体的表现必须跨越多个维度进行评估，包括协作成功、推理能力和系统效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/10/text
1. 多智能体系统评估中的协作基准和竞争基准各有哪些特定度量领域？这些度量领域如何帮助捕捉智能体在不同方面的表现？  2. 当前多智能体系统评估方法中常用的效率度量、决策质量度量、协作质量度量和适应性度量各有何优点和局限？这些度量如何为多智能体系统的综合评估提供基础？  3. 多智能体系统评估中的自适应和韧性基准是如何考虑智能体动态适应和系统韧性的？这些基准如何帮助评估智能体在面对干扰时的表现和自我纠正能力？
在最近的研究中，多智能体系统的评估主要可以沿着三个主要维度进行分类：以协作为重点的基准、以竞争为重点的基准，以及自适应和韧性基准。在每个类别中，我们确定了捕捉智能体表现不同方面的特定度量领域。当前的评估方法通常衡量效率度量（例如任务完成率、资源利用率、时间效率）、决策质量度量（例如动作准确性、战略合理性、推理深度）、协作质量度量（例如沟通效果、协调效率、工作负荷分配）和适应性度量（例如对干扰的响应、自我纠正），这为评估多智能体系统奠定了基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/11/text
1. 协作为重点的基准如何演变，从最初关注的单一维度指标到如今评估智能体间通信和协调的综合框架？ 2. 在评估智能体协作时，最初的基准如InformativeBench是如何衡量信息传播任务中的决策准确性的？ 3. Collb-Overcooked引入的轨迹效率得分（TES）和增量轨迹效率得分（ITES）等指标如何揭示了智能体在强大任务理解能力情况下存在的显著缺陷？
以协作为重点的基准。协作为重点的基准已经有了显著的发展，从基本的单一维度指标转变为评估复杂的智能体间通信和协调的综合框架。最初的基准，如InformativeBench[108]，主要关注在信息不对称条件下的智能体协作，采用诸如Precision和IoU等指标来衡量信息传播任务中的决策准确性。随后，评估范围扩大，如Collb-Overcooked[944]，引入了诸如轨迹效率得分（TES）和增量轨迹效率得分（ITES）等细致的过程导向指标。这些指标评估了协调的详细方面，揭示了智能体在强大任务理解能力的情况下存在的显著缺陷，包括主动规划和适应能力不足。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/12/text
1. 多智能体系统评估中的不同基准如何展示了对智能体协作行为和战略一致性更深层次方面的新趋势？  2. 在评估智能体参与复杂社会嵌入式任务能力时，基准如PARTNR、VilagerBench和BabyAGI是如何解决现有评估中的差距的？  3. 多智能体评估标准化工作中，AgentBench、VisualAgentBench和Auto-Arena如何展示了封闭源和开放源LLM之间的实质性性能差异？
进一步扩大评估范围，COMMA[1109]和LLM-Coordination[926]强调了沟通效果和战略同步，采用了多样化的环境和广泛的指标，包括成功率、平均错误率和环境理解准确性。这些基准共同展示了捕捉协作行为和战略一致性更深层次方面的新趋势。

其他基准，如PARTNR[946]、VilagerBench[925]和BabyAGI[2]，通过专注于推理、规划和任务分解，进一步解决了现有评估中的差距。这些基准强调了对智能体参与复杂的社会嵌入式任务能力的全面评估，考虑了完成百分比、平衡智能体利用率和智能体贡献率等指标。AgentBench[706]、VisualAgentBench[928]和Auto-Arena[947]进一步标准化了多智能体评估，自动化评估跨不同领域，并展示了封闭源和开放源LLM之间的实质性性能差异。这些观察强调了开发普遍有效的协作框架面临的关键挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/13/text
1. 以竞争为重点的基准如何评估智能体的战略能力和对抗性互动？这种评估方法如何突出心智理论和对手建模方面的特定缺陷？  2. 早期的基准如BatleAgentBench和MAgIC在关注混合合作竞争环境时，揭示了LLM智能体在高阶战略推理方面存在的关键弱点。这些基准采用了哪些全面的竞争指标来评估智能体的表现？
总的来说，以协作为重点的基准共同反映了向全面、细致评估的持续转变，涵盖了沟通效率、自适应策略和细粒度智能体协调，解决了早期仅关注结果性能的限制。

以竞争为重点的基准。竞争为重点的基准评估智能体的战略能力和对抗性互动，突出了心智理论和对手建模方面的特定缺陷。早期的基准，如BatleAgentBench和MAgIC，开始关注混合合作竞争环境，揭示了LLM智能体在高阶战略推理方面存在的关键弱点。这些基准采用了全面的竞争指标，如前进距离、判断准确性和理性得分，发现虽然先进的LLM在简单场景下表现良好，但在复杂对抗条件下仍存在显著限制。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/14/text
1. 竞争评估中的LLM存在哪些持续的限制，尤其是在对手预测、风险评估和自适应战略规划方面存在何种不足之处？  2. 在社交推理和欺骗基准中，智能体在解释隐藏信息和处理复杂社交动态方面存在哪些基本差距？这些差距如何体现在暗杀准确性、推理准确性和胜率等指标上？  3. 博弈论评估基准如Guandan、AgentVerse和MultiAgentBench如何强调了增强心灵理论和预测建模能力的必要性？这些基准如何帮助评估智能体在信息不完全情况下的战略合作能力？
基于这些见解，随后的基准，如Human Simulacra、LLMArena和PokerBench，通过整合类人推理指标和更稳健的战略措施（如响应相似度评分、Elo评分和行动准确性），进一步完善了竞争评估。这些评估一再表明，尽管在任务理解方面表现出色，但在对手预测、风险评估和自适应战略规划方面存在不足。

社交推理和欺骗为基础的基准，尤其是AvalonBench和Diplomacy，进一步揭示了智能体在解释隐藏信息和处理复杂社交动态方面的基本差距。类似暗杀准确性、推理准确性和胜率等指标强调，即使是复杂的LLM也无法复制人类水平的对抗谈判和隐藏信息游戏推理。

另外，包括Guandan、AgentVerse、MultiAgentBench和ICP在内的博弈论评估引入了需要在信息不完全情况下进行战略合作的场景。这些基准加强了先前关于增强心灵理论和预测建模能力的必要性的发现。MultiAgentBench还引入了关键绩效指标和协调评分来评估智能体之间的竞争。总体而言，以竞争为重点的基准突显了基于LLM的智能体在战略和推理方面存在持续的限制，强调了尽管在一般推理和任务执行能力方面取得了进展，但仍需要解决对抗建模和战略规划中的关键差距。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/15/text
1. 自适应和韧性基准如何帮助评估多智能体系统在动态环境中的自适应能力和系统韧性？ 2. AdaSociety是如何在自适应性方面要求智能体进行持续学习，并在环境发现和社交网络构建之间取得平衡的？ 3. 当前多智能体决策框架在引入各种物理背景和不断变化的社会依赖关系中存在哪些不足，AdaSociety是如何应对这些挑战的？
自适应和韧性基准涉及自适应和韧性多智能体系统基准，同时解决两个相互关联的能力：自适应——智能体根据改变、意外的环境条件通过修改其行为和策略来动态行动的能力。韧性，或系统忍受、减轻和迅速从干扰、故障或敌对干预中恢复的能力。如AdaSociety所述，在自适应性方面，社会关系和物理环境之间的动态相互作用要求智能体进行持续学习，并在环境发现和社交网络构建之间取得平衡。尽管当前多智能体决策框架取得了显著进展，但这些环境在引入各种物理背景和不断变化的社会依赖关系中存在不足。因此，AdaSociety引入了一个环境，其中物理状态、任务和智能体之间的社会关系不断演变，从而捕捉了智能体在应对不断增加的任务复杂性和转变的资源约束时的适应能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.1 Benchmarks for Specific Reasoning Tasks/section/16/text
1. 当前的多智能体系统基准在评估规划能力和适应性方面存在哪些不足之处？ 2. REALM-Bench如何通过真实世界启发的规划问题定义了适应性，并强调了哪些关键指标？ 3. 韧性基准是如何系统地引入故障或错误到各个智能体中，以评估整体系统的稳健性的？
此外，当前的基准可能过于简化了真实世界自动化的挑战，对干扰建模和过程简化依赖有限[945]，导致对规划能力和适应性的评估不足。因此，另一方面，REALM-Bench [945]通过真实世界启发的规划问题定义了适应性，强调诸如实时重新规划效率、在复杂性增加下的协调可扩展性以及尽管动态相互依赖或干扰事件发生时性能结果的稳定性等指标。相反，韧性基准[1128]系统地引入故障或错误到各个智能体中，以评估整体系统的稳健性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.2 Challenge and Future Work/section
挑战与未来工作部分探讨了LLM多智能体评估中的挑战和未来方向。首先，对比单一智能体框架，多智能体系统在复杂任务上表现更优，但也带来更多计算成本，因此需要有效的任务路由机制来确定何时需要调用MAS框架。其次，MAS框架的优化影响每个部分，类似于反向传播。最后，MAS框架通常设计为同质特征的多个代理，但实际应用中涉及到不同类型的AI代理，如何有效建立这些代理之间的连接是未来需要解决的关键问题。这些挑战提示了未来研究需要解决的领域，以推动MAS评估的全面发展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/17 Evaluating Multi-Agent Systems 155/17.2 Challenge and Future Work/section/0/text
1. 在多智能体系统评估中，如何确定何时需要调用MAS框架，以实现对复杂任务的有效处理？ 2. MAS框架的优化如何影响其各个部分，类似于反向传播的原理是如何在多智能体系统中体现的？ 3. 面对不同类型的AI代理，如何有效建立这些代理之间的连接是多智能体系统评估中的一个关键挑战，未来应该如何解决这一问题？
近年来，已经开发了各种多智能体系统（MAS）评估基准，但在跨不同MAS任务和场景的评估标准化以及评估MAS的可伸缩性和多样性方面仍存在挑战和限制。未来的研究必须解决这些挑战，以发展MAS评估的全面领域。

以下是LLM多智能体评估中的一些挑战和未来方向：

1. 与单一智能体框架相比，多智能体系统在解决复杂任务时表现出优越性能。但与单一智能体系统相比，MAS还需要更多的计算并带来额外的成本。因此，我们面临一个紧迫的挑战：何时需要调用MAS框架？对于许多简单的用户指令，我们可能只需要LLM或单一智能体系统来完成。只有复杂的用户指令可能需要MAS框架。因此，在未来，如何设计任务路由机制以检测哪些情景需要MAS是基础但也是一个重要问题。
2. 多智能体系统是一个高级框架，建立在多个基于基础模型的AI代理之上。因此，就像反向传播一样，MAS框架的优化也会影响每个部分（即基础模型、AI代理和多智能体协作）。
3. 现有的MAS框架通常设计具有同质特征的多个代理，例如所有都是基于语言的代理。但将MAS连接到现实场景时，通常涉及不同类型的AI代理。例如，我们可能需要在基于语言的代理、数字代理和机器人代理之间建立连接。然而，这些代理采用各种设置，从输入到输出不等。如何建立这些代理之间的连接仍然是一个需要在未来解决的开放性问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs 163/section
本节深入研究了LLM的安全漏洞，包括越狱攻击、提示注入攻击、幻觉风险、不对齐问题和毒化攻击。在隐私关注方面，探讨了推断训练数据、推断交互数据和隐私威胁缓解。通过揭示这些问题，强调了构建安全、可靠和有益的人工智能系统的紧迫性，以应对内在和外在的安全威胁，实现值得信赖的现实世界部署。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs 163/section/0/text
1. 如何可以应对人工智能系统中存在的越狱攻击、提示注入攻击、幻觉风险、不对齐问题和毒化攻击等安全漏洞，以确保系统的安全性和可靠性？  2. 在推断训练数据、推断交互数据和隐私威胁缓解方面，人工智能系统可能面临哪些隐私风险？如何有效应对这些隐私风险，确保用户数据的安全和隐私？  3. 为什么强调构建安全、可靠和有益的人工智能系统对于实现值得信赖的现实世界部署至关重要？如何通过解决内在和外在的安全威胁，确保人工智能系统在实际应用中的可靠性和安全性？
18.1.1 越狱攻击 163
18.1.2 提示注入攻击 166
18.1.3 幻觉风险 167
18.1.4 不对齐问题 169
18.1.5 毒化攻击 170
18.2 隐私关注 172
18.2.1 推断训练数据 172
18.2.2 推断交互数据 173
18.2.3 隐私威胁缓解 174
18.3 总结与讨论 175

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Agent Intrinsic Safety: Threats on Non-Brain Modules 176/section
19.1 感知安全威胁 . 176 19.1.1 感知中的对抗性攻击 176

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Agent Intrinsic Safety: Threats on Non-Brain Modules 176/section/0/text
这个领域的研究如何定义和识别感知中的对抗性攻击？
19.1 感知安全威胁 . 176
19.1.1 感知中的对抗性攻击 176

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1.2 Misperception Issues 177/section
19.2 行动安全威胁 19.2.1 供应链攻击 19.2.2 工具使用中的风险

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1.2 Misperception Issues 177/section/0/text
1. 供应链攻击在行动安全威胁中扮演着怎样的角色，其对于整个系统安全性有何影响？ 2. 工具使用中的风险是如何影响行动安全的，以及如何有效管理这些风险？ 3. 行动安全威胁中的供应链攻击和工具使用中的风险之间是否存在某种关联或相互作用，对于行动安全有何深远影响？
19.2 行动安全威胁
19.2.1 供应链攻击
19.2.2 工具使用中的风险

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/0 Agent Extrinsic Safety: Interaction Risks 180/section
20.1 代理-记忆交互威胁 180  20.2 代理-环境交互威胁 180 20.3 代理-代理交互威胁 182 20.4 总结与讨论 182

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/0 Agent Extrinsic Safety: Interaction Risks 180/section/0/text
- 代理-记忆交互威胁在智能系统中的实际应用中存在哪些挑战和风险？ - 如何评估代理-记忆交互威胁对智能系统性能和安全性的影响？ - 在应对代理-记忆交互威胁时，有哪些有效的防御策略和技术可供选择？
20.1 代理-记忆交互威胁 180

20.2 代理-环境交互威胁 180
20.3 代理-代理交互威胁 182
20.4 总结与讨论 182

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/section
本章探讨了AI代理的超对齐和安全缩放规律。在超对齐方面，通过将长期目标融入代理的决策过程，超对齐模型取代了传统奖励信号，提高了代理行为的一致性和透明度。实证证据显示，超对齐模型在长期互动中表现出更强的稳健性，但仍面临目标定义和奖励校准等挑战。未来研究应关注提高可解释性和稳定性，以确保人工智能系统与人类价值观一致。在安全扩展法则方面，研究强调了随着人工智能能力增长，安全风险也呈非线性升级。AI代理的安全性必须与模型能力同步扩展，平衡模型能力和安全措施。未来方向包括提出AI- $45^{\circ}$ 规则，通过风险管理框架确保人工智能系统具备适当的安全防护措施。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/section/0/text
1. 超对齐模型如何通过将长期目标融入代理的决策过程来取代传统奖励信号，从而提高代理行为的一致性和透明度？ 2. AI代理的安全性为何需要与模型能力同步扩展，以平衡模型能力和安全措施？  3. 未来研究在提高AI系统的可解释性和稳定性方面有哪些关键挑战和发展方向？
21.1 超对齐：AI代理的目标驱动对齐。184

21.1.1 超对齐中的复合目标函数。184
21.1.2 通过超对齐克服RLHF的局限性。185
21.1.3 实证证据支持超对齐。185
21.1.4 挑战和未来方向。185

21.2 AI代理中的安全扩展法则。186
21.2.1 当前形势：平衡模型安全性和性能。186
21.2.2 增强安全性：偏好对齐和可控设计。187
21.2.3 未来方向和策略：AI- $45^{\circ}$ 规则和风险管理。187

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/section
随着大型语言模型在智能代理决策中的日益重要，传统的对齐技术已显现局限。超对齐的提出标志着一种新的对齐策略，通过将长期目标嵌入到代理的决策过程中，整合了安全、道德、任务绩效和长期规划等多维度考量。这种结构化奖励机制取代了传统单一奖励信号，提高了代理行为的透明度和长期一致性。实证证据表明，超对齐模型在长期互动中表现出更强的稳健性，通过连续校准实现动态调整，使代理能够在变化环境中保持长期战略对齐。然而，超对齐仍面临目标定义、奖励校准、动态适应和层次目标保持一致性等挑战。未来的研究应关注提高可解释性、稳定性和适应性，以确保人工智能系统与人类价值观保持一致。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/section/0/text
1. 传统的对齐技术在确保人工智能系统输出符合道德标准和长期规划方面存在哪些局限性？ 2. 为什么传统的安全对齐方法在处理复杂、多方面任务时可能会遇到困难？ 3. 超对齐模型相较于传统对齐技术有哪些优势，特别是在长期互动和动态调整方面表现出的稳健性如何体现？
随着LLMs越来越成为自主代理决策的核心，确保它们的输出保持安全、符合道德标准，并始终与人类目标保持一致已成为一项紧迫挑战。传统的对齐技术，特别是RLHF，在通过整合人类偏好来完善LLM行为方面发挥了关键作用。

传统的安全对齐主要侧重于通过强制预定义约束来预防有害结果。在这种框架中，代理的行为由单一的聚合奖励信号引导，该信号优先考虑即时修正而非长期规划。尽管这种反应式方法在许多当前应用中有效，但当代理必须执行复杂、多方面的任务时，它就会遇到困难。将复杂的长期目标分解为可解释和可管理的子目标的能力不足可能导致技术上安全但并不符合更广泛人类中心目标的行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/section/1/text
1. 超对齐在代理决策中的长期目标表征是如何与传统对齐策略的约束方法相比有何不同之处？ 2. 超对齐的复合客观函数是如何管理代理行为的，以实现安全、道德、任务绩效和长期规划等多维度考量？ 3. 超对齐模型如何通过连续校准实现动态调整，以确保代理在变化环境中保持长期战略对齐？
为了解决这些局限，超对齐（superalignment）的概念应运而生。超对齐代表了对齐策略的演进，通过直接将明确的长期目标表征嵌入到代理的决策过程中。与简单地施加约束以避免有害行为不同，超对齐通过一个复合客观函数积极地管理行为。该函数整合了几个性能维度，特别是安全和道德考虑（其中伦理规范和安全准则持续嵌入决策过程）、任务有效性（确保代理不仅避免有害行为，而且以高效能执行其预期功能），以及长期战略规划（使代理能够规划长期视野并将复杂目标分解为可管理的子任务）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/section/2/text
1. 超对齐如何整合安全、伦理标准、任务绩效和长期规划，以增强自主代理的可靠性和健壮性？ 2. 超对齐如何在调和即时安全关切与长期目标的过程中促进代理在复杂环境中的动态适应性？ 3. 在人工智能系统中整合超对齐策略如何提供更清晰、更可解释的行为结构，对于安全审计和持续改进有何重要性？
将超对齐（superalignment）整合到人工智能系统中标志着向更加健壮、以目标为导向的对齐策略的重要转变。通过在单一优化框架内统一安全、伦理标准、任务绩效和长期规划，超对齐旨在增强自主代理的可靠性和健壮性，确保它们在长时间运行期间保持与人类价值观的一致性；通过调和即时安全关切与战略性、长期目标，促进在复杂环境中的动态适应；并为诊断和完善人工智能行为提供更清晰、更可解释的结构——这对于安全审计和持续改进至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/section/3/text
1. 未来的研究如何可以有效平衡多样目标的算法，以确保超对齐策略在现实世界应用中的有效性？ 2. 在建立可扩展框架的过程中，如何确保既能预防有害行为，又能积极促进与复杂人类价值观和目标一致的性能？ 3. 未来研究在提高超对齐策略的可解释性、稳定性和适应性方面可能面临哪些挑战？
未来的研究预计将集中在开发有效平衡这些多样目标的算法，并验证超对齐策略在现实世界应用中的有效性。最终目标是建立一个可扩展的框架，不仅可以防止有害行为，还可以积极促进与复杂人类价值观和目标一致的性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.1 Composite Objective Functions in Superalignment/section
超对齐中的复合目标函数是一种结构化奖励机制，通过整合多维绩效来引导代理行为。与传统对齐不同，超对齐将目标分解为三个部分：任务绩效项、目标遵从项和规范遵从项。任务绩效项确保代理高效执行即时操作任务；目标遵从项嵌入长期战略目标，包括安全、道德和用户优先级；规范遵从项强制遵守道德和法律边界，防止代理仅优化短期奖励。这种多组分表述解决了RLHF的奖励破解风险，避免代理利用模糊定义的奖励函数最大化短期收益，却无法实现长期对齐。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.1 Composite Objective Functions in Superalignment/section/0/text
1. 超对齐中的复合目标函数如何通过任务绩效项、目标遵从项和规范遵从项三个部分来引导代理行为，以实现长期对齐的目标？  2. 相较于传统对齐中依赖单一、聚合奖励函数的方式，超对齐的复合目标函数如何避免了RLHF的奖励破解风险，确保代理不会仅仅优化短期收益而忽视长期战略目标？  3. 在超对齐中，任务绩效项、目标遵从项和规范遵从项分别如何影响代理的行为，以确保代理在执行任务时既高效又符合长期战略目标？
在超对齐的核心是复合目标函数，这是一种结构化奖励机制，整合了多维绩效以指导代理行为[1176]。与通常依赖单一、聚合奖励函数的传统对齐不同，超对齐明确将目标分解为三个不同的组成部分：

- 任务绩效项：确保代理以高准确度和效率执行即时操作任务。
- 目标遵从项：将长期战略目标嵌入到代理的决策过程中，其中包括安全约束、道德考虑和用户定义的优先级[1178,1389]。
- 规范遵从项：强制遵守道德和法律边界，防止行为优化短期奖励而损害长期对齐[1390, 1391]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.1 Composite Objective Functions in Superalignment/section/1/text
1. 超对齐中的多组分表述如何解决了RLHF的奖励破解风险，以及为什么这种风险会导致代理无法实现长期对齐？  2. 相较于传统对齐方法，超对齐中的任务绩效项、目标遵从项和规范遵从项各自的作用是什么，如何共同引导代理行为实现长期对齐？  3. 在超对齐中，为什么将目标分解为任务绩效项、目标遵从项和规范遵从项这三个部分，如何确保代理在执行任务时不仅关注短期收益，还能考虑长期战略目标和道德法律边界？
这种多组分的表述解决了RLHF的一个关键弱点：奖励破解的风险，即代理利用模糊定义的奖励函数来最大化短期收益，同时未能实现真正的长期对齐[1392, 1393]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.2 Overcoming the Limitations of RLHF with Superalignment/section
传统强化学习依赖于短期反馈信号，面临长期目标保持的挑战。超对齐方法通过层次化目标调节解决了这一问题，将复杂任务分解为可解释的子目标，提高了透明度和长期一致性。这种结构化方法不仅消除了奖励模型简化和人类偏好滥用的风险，还使人工智能系统能够更有效地推广到更长时间范围内。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.2 Overcoming the Limitations of RLHF with Superalignment/section/0/text
1. 传统强化学习在长期目标保持方面存在哪些困难？这些困难的根源是什么？ 2. 超对齐方法是如何通过层次化目标调节来解决传统强化学习中的长期目标保持问题的？ 3. 结构化方法如何帮助人工智能系统更有效地推广到更长时间范围内？
传统的强化学习（Traditional RL）依赖于隐式反馈信号，这些信号通常在短期交互中进行聚合。尽管这种方法在细化模型输出方面有效，但由于几个固有限制，它在长期目标保持方面存在困难。首先，人类反馈往往是短视的，优先考虑即时的正确性而不是更广泛的战略对齐。其次，奖励模型通常过于简化复杂的多步任务，使得代理难以有效地推广到较长时间范围。第三，代理可以利用奖励结构中的漏洞，优化表面上符合人类偏好的行为，但最终偏离了预期的目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.2 Overcoming the Limitations of RLHF with Superalignment/section/1/text
1. 超对齐方法如何通过层次化结构化目标解决了传统强化学习面临的长期目标保持挑战？ 2. 为什么超对齐方法能够提高人工智能系统的透明度和长期一致性，相比于传统的强化学习方法有何优势？ 3. 超对齐方法如何避免了奖励模型简化和人类偏好滥用的风险，以及如何帮助人工智能系统更有效地推广到更长时间范围内？
超对齐通过明确的目标调节解决了这些挑战。它不仅仅依赖于聚合奖励信号，而是通过层次化结构化目标，并将复杂任务分解为更小、可解释的子目标。这种结构化方法提高了透明度，允许实时调整，并确保人工智能系统在决策过程中保持长期的一致性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.3 Empirical Evidence Supporting Superalignment/section
最新研究提供了支持超对齐在实际场景中的有效性的实证证据。相比传统对齐技术，使用复合目标进行训练的代理在长期互动中表现出更强的稳健性。超对齐模型采用连续校准，根据实时数据动态调整不同目标的权重，使代理能够灵活应对变化需求，同时保持长期战略对齐。这种自适应框架弥补了传统RLHF方法在此方面的不足，为代理在动态环境中的表现提供了重要支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.3 Empirical Evidence Supporting Superalignment/section/0/text
1. 超对齐模型相较于传统对齐技术的优势在于哪些方面？这种优势是如何在长期互动中体现出来的？ 2. 传统RLHF方法在动态环境下存在哪些不足之处？超对齐模型的自适应框架是如何弥补这些不足的？ 3. 超对齐模型如何通过连续校准和动态调整目标权重来应对不断变化的用户需求？这种策略如何保持代理的长期战略对齐？
最近的研究为超对齐在现实世界应用中提供了强有力的经验证据。研究表明，使用复合目标进行训练的代理在长时间互动中表现出更强的稳健性，并且胜过依赖传统对齐技术的代理。与静态奖励函数不同，后者在不断变化的情况下保持不变，超对齐模型采用连续校准，根据实时运行数据动态调整不同目标的权重。这种自适应框架使代理能够响应不断变化的用户需求，同时保持长期战略对齐，这是传统RLHF方法中很大程度上缺少的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.4 Challenges and Future Directions/section
超对齐作为一种实现人工智能对齐的结构化方法，面临着目标定义、奖励校准、动态适应和层次目标保持一致性等关键挑战。首先，精确定义目标是困难的，因为人类价值观具有上下文敏感性和矛盾性，需要更先进的方法来捕捉目标的复杂性。其次，奖励校准需要平衡任务表现、长期遵从性和道德合规，调整稳定性和一致性仍是研究焦点。第三，适应动态的人类价值观和运营环境需要实时目标重校准，确保模型更新其价值表示而不影响对齐。最后，保持层次目标的一致性是一个挑战，过度僵化或不清晰的子目标可能导致不对齐。未来的工作应致力于提高可解释性、稳定性和适应性，以确保人工智能系统与人类目标保持对齐。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.4 Challenges and Future Directions/section/0/text
1. 如何解决超对齐中关于目标规范的挑战，特别是在面对人类价值观的上下文敏感性和矛盾性时，需要采取哪些更先进的方法来捕捉目标的复杂性？  2. 在超对齐中，如何平衡奖励校准的需求，确保同时考虑任务表现、长期遵从性和道德合规，以实现稳定性和一致性？  3. 当超对齐需要动态适应人类价值观和运营环境时，如何实时重校准目标以确保模型更新其价值表示，同时不影响对齐的实现？
尽管超对齐（superalignment）具有潜力，但在实际实施中存在一些必须解决的关键挑战。这些挑战主要涉及目标规范、奖励校准、动态适应以及在层次目标中保持一致性。

一个基本困难在于定义精确而明确的目标。人类价值观具有固有的上下文敏感性、模糊性和有时矛盾性，这使得将它们编码成结构化的、机器可解释的格式具有挑战性。现有的对齐技术难以捕捉人类意图的全部复杂性，需要更先进的方法来提取、分解和表征目标。当前的研究探索了层次建模和偏好学习，以使人工智能系统更好地适应不断发展和微妙的人类目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.4 Challenges and Future Directions/section/1/text
1. 奖励校准在超对齐中的平衡关系是如何影响任务表现、长期遵从性和道德合规的？ 2. 超对齐中的自适应加权机制如何帮助调整奖励组成部分？这种调整如何影响奖励结构的稳定性和一致性？ 3. 在超对齐中，如何确保奖励校准的稳定性和一致性，避免为了短期优化而牺牲战略一致性或长期目标？
即使目标定义明确，奖励校准仍然是一个重要挑战。超对齐需要在任务表现、长期遵从性和道德合规之间保持谨慎平衡。一个糟糕校准的奖励结构可能导致为了短期优化而牺牲战略一致性，或者相反，过分强调长期目标而牺牲即时有效性。自适应加权机制有助于动态调整奖励组成部分，但确保这些调整的稳定性和一致性仍然是一个未解决的研究问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.4 Challenges and Future Directions/section/2/text
1. 如何通过元学习和上下文感知对齐促进实时目标重校准，以适应动态的人类价值观和运营环境的挑战？   2. AI模型在更新其目标以反映社会规范和伦理标准的同时，如何确保其能够保持对齐而不影响整体稳定性？   3. 为什么人工智能系统需要不断更新其目标，以适应不断演变的运营环境，而静态基于规则的系统无法胜任这一任务？
另一个挑战源于适应动态的人类价值观和不断演变的运营环境。与静态基于规则的系统不同，AI模型必须不断更新其目标，以反映社会规范、伦理标准和外部条件的变化。通过元学习和上下文感知对齐促进的实时目标重校准，使AI系统能够识别其需要细化的目标，并相应进行调整。然而，确保模型可以更新其价值表示而不影响对齐仍然是一个尚未解决的问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.4 Challenges and Future Directions/section/3/text
1. 超对齐中如何保持长期目标分解的一致性？过于僵化或不清晰的子目标可能会导致怎样的问题？ 2. 递归验证和多层奖励结构化等技术如何帮助减轻超对齐中子目标不对齐的风险？这些技术在不同人工智能系统中的适用性如何？ 3. 超对齐在处理层次目标保持一致性时面临的挑战是什么？未来的研究如何提高超对齐系统的可解释性、稳定性和适应性？
最后，保持层次目标分解的一致性增加了另一层复杂性。超对齐依赖于将长期目标分解为子目标，同时保持战略对齐。过于僵化的子目标可能导致狭窄优化，忽视更广泛的意图，而定义不清晰的子目标可能导致即时行动与总体目标之间的不对齐。诸如递归验证和多层奖励结构化等技术旨在减轻这些风险，但需要进一步研究以完善它们在各种人工智能系统中的适用性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.1 Superalignment: Goal-Driven Alignment for AI Agents/21.1.4 Challenges and Future Directions/section/4/text
1. 超对齐方法如何克服人工智能对齐中的目标模糊性问题？   2. 在人工智能对齐中，奖励校准错误如何影响任务表现、长期遵从性和道德合规的平衡？   3. 为什么保持层次目标的一致性对于人工智能系统与人类目标的对齐至关重要？
综上所述，虽然超对齐提供了一种结构化方法来实现人工智能对齐，但其成功实施取决于克服目标模糊性、奖励校准错误、价值漂移和层次不对齐。未来的工作应着重于增强可解释性、稳定性和适应性，以确保人工智能系统在较长时间跨度内与人类目标保持对齐。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/section
本节介绍了AI代理的安全缩放定律，探讨了随着人工智能能力指数级增长，安全风险的非线性升级。安全扩展定律强调了安全干预必须与模型能力扩展成比例，包括模型能力与安全风险之间的权衡关系，以及商业与开源模型的安全性和性能特性差异。研究还揭示了规模-数据相互作用和多模态脆弱性等问题，强调了安全性扩展需要架构创新。未来方向包括AI- $45^{\circ}$ 规则的提出，旨在平衡AI能力和安全措施，通过红线和黄线风险管理框架确保人工智能系统具备适当的安全防护措施。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/section/0/text
1. 人工智能能力的指数级增长如何揭示了安全风险的非线性升级，以及安全扩展定律在维持可接受风险水平方面的重要性是如何体现的？  2. 在人工智能领域中，安全扩展定律所描述的安全干预如何必须与模型能力扩展成比例？这种挑战的核心在于什么，以及如何确保安全措施与模型能力的演进保持一致？  3. 最近的研究如何量化了模型能力与安全措施之间的张力，并提出了怎样的解决方案框架来应对这种挑战？
人工智能能力的指数级增长揭示了人工智能领域的一个根本张力：安全风险的非线性升级。随着语言模型从数百万到数万亿参数的增长，它们的性能遵循可预测的扩展规律，但安全保障展现出截然不同的动态。安全扩展定律——描述安全干预必须如何扩展以维持可接受风险水平随着模型能力扩展的数学关系。安全扩展定律的核心挑战在于确保安全措施与模型能力成比例地演进，因为性能改进往往超越了安全改进。最近的研究量化了这种张力并提出了解决方案框架：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/section/1/text
1. AI代理的安全缩放定律如何揭示了模型能力与安全风险之间的权衡关系？安全-性能指数（SPI）是如何用来衡量这种关系的？  2. Ruan等人的研究如何揭示了实用性优化的模型存在更多安全关键故障的问题？为什么突出了联合优化框架的必要性？  3. 商业与开源模型在安全-性能特性上有哪些不同表现？Ying等人的研究结果如何揭示了商业模型和开源模型之间的安全性和性能的权衡关系？
·能力-风险权衡：Zhang等人[295]建立了模型能力和安全风险之间的第一个定量关系，表明更具能力的模型固有地面临更高的脆弱表面。该研究引入了安全-性能指数（SPI）来衡量这种权衡关系。

·实用性-安全性关系：在此基础上，Ruan等人[795]揭示出为实用性而优化的模型表现出37%更多的安全关键故障，突显了联合优化框架的必要性。

·商业与开源动态：通过大规模基准测试，Ying等人[1406]揭示了不同的安全-性能特性：商业模型（例如Claude-3.5 Sonnet）通过专门的安全管道实现了29%更高的安全得分，但性能损失为15%。开源模型显示出更紧密的耦合，Phi系列以40%更低的计算成本达到了商业安全水平的91%。

· 规模-数据相互作用：与预期相反，模型大小仅解释了42%的安全变异，而数据质量占68%，表明以数据为中心的方法可能优于纯粹的扩展。

· 多模态脆弱性：在视觉基础过程中，MLLMs表现出2.1倍更多的安全故障，跨模态注意力头被确定为主要故障点（占有害输出的71%）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/section/2/text
1. AI代理的安全缩放定律中提到的安全性扩展需要根本性改变的架构创新是指什么？这种改变如何与模型能力和安全风险之间的关系相互作用？  2. 新兴对齐技术如何应对AI代理安全性扩展中提到的挑战？这些技术如何帮助平衡AI能力和安全措施，确保人工智能系统具备适当的安全防护措施？
这些研究[295,795,406]共同表明，安全性的扩展需要的不仅仅是成比例的投资，而是需要对能力-风险关系进行根本性改变的架构创新。接下来，我们将回顾对新兴对齐技术如何解决这些挑战的探索[1407, 1408, 1409]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/21.2.1 Current landscape: balancing model safety and performance/section
近年来，人工智能模型的安全性和性能成为研究焦点，尤其是在高风险应用中的部署。研究揭示了更强大的模型存在更高安全风险，凸显了在模型能力和健壮保障之间平衡的挑战。有用性与安全性问题互相影响，商业模型的安全性和性能呈负相关，而开源模型通常呈正相关。商业模型在安全性方面表现优异，而模型规模与安全性能之间并无严格线性关系。训练数据质量和流程对安全性至关重要；多模态大型语言模型在某些应用中可能会牺牲安全性，受基础模型和训练策略影响。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/21.2.1 Current landscape: balancing model safety and performance/section/0/text
1. 模型安全性和性能之间的负相关性和正相关性背后的原因是什么？开源模型和商业模型在安全性方面的优势和劣势是如何体现的？ 2. 在人工智能模型的安全性研究中，为什么模型规模与安全性能之间没有严格的线性关系？训练数据的质量和流程对模型安全性的影响是如何体现的？ 3. 在多模态大型语言模型（MLLMs）的研究中，为什么在某些应用中可能会牺牲安全性？基础语言模型和训练策略是如何影响安全性能的？
近年来，人工智能模型的安全性和性能已成为研究的关键话题，特别是这些模型越来越多地部署在高风险应用中。张等人首次提出量化模型安全性与性能之间关系的研究，揭示更强大的模型固有地面临更高的安全风险。这一发现凸显了在模型能力和对健壮保障的需求之间取得平衡的挑战。在此基础上，阮等人探讨了有用性（定义为模型协助用户的能力）如何与安全性问题相互作用。推动讨论进一步发展，应英等人进行了更详细的模型安全性和性能比较分析，得出以下结论：（1）如图21.1（A）和图21.1（C）所示，商业模型的安全性和性能通常呈负相关，因为不同公司在安全措施和投资方面存在差异。相比之下，开源模型往往表现出一种正相关，即一般性能的提升通常会带来安全性的改善。商业模型在安全性方面通常优于开源模型，其中Claude-3.5 Sonnet是商业模型中最安全的，而Phiseries是最安全的开源模型。（2）如图21.1（B）所示，模型规模与安全性能之间没有严格的线性关系。训练数据的质量和流程也是影响安全性的关键因素；（3）多模态大型语言模型（MLLMs）在视觉语言微调和多模态语义对齐过程中往往会牺牲安全性，安全性能受基础语言模型和具体训练策略的影响。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/21.2.2 Enhancing safety: preference alignment and controllable design/section
随着大型语言模型（LLMs）的广泛应用，其安全性日益受到关注。在解决LLMs安全性挑战方面，偏好调整技术发挥着关键作用。这些技术旨在通过对齐模型与安全数据集，使模型生成更安全的输出。研究表明，偏好优化方法如Safe-NCA在平衡安全性和性能方面表现出色。此外，为了实现安全性和有益性之间的平衡，灵活的控制是必不可少的。Tuan等人提出了一个基于自动生成数据的框架，通过控制标记来指定模型响应的安全性和有益性水平，从而增强模型的可控性。然而，实现对安全性和有益性的独立控制仍然面临挑战，包括定义难题、模型权衡困境和数据示例相关性等问题。这些挑战需要进一步研究以提高智能代理系统的安全性和实用性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/21.2.2 Enhancing safety: preference alignment and controllable design/section/0/text
1. 如何偏好调整技术在增强大型语言模型（LLMs）安全性方面发挥关键作用？它们是如何通过对齐模型与安全数据集来使模型生成更安全的输出的？  2. 在研究中提到的偏好优化方法如Safe-NCA是如何在平衡安全性和性能方面表现出色的？它是如何通过自定义对比损失函数和安全数据集来训练更安全、更稳健的模型的？  3. 实现对安全性和有益性之间的灵活控制为什么对智能代理系统的安全性和实用性至关重要？在不同用户需求下，如何确保模型在安全性和有益性之间取得适当平衡？
随着LLMs的能力不断增强，关于它们安全性的担忧变得日益突出。增强模型安全性因此成为LLMs发展中的一个关键挑战。先前的研究提出了各种方法来解决这一问题，包括使用上下文示例和自我安全检查、红队技术，以及来自人类反馈的安全强化学习（Safe RLHF）等。LLMs中的安全问题本质上可以被视为一种对齐问题。目标是将模型与包含安全和不太安全响应的数据集进行对齐。通过这种对齐，模型学会优先生成更安全的输出，同时最小化有害内容的风险。在偏好优化技术的支持下（如DPO、IPO等），这种对齐过程微调模型以生成符合安全标准的响应。正如报道的那样，已经调查了各种偏好优化方法以增强安全性，包括SafeDPO、Safe-robust-DPO、Safe-IPO、Safe-SLiC、Safe-KTO和Safe-NCA等。结果表明，大多数偏好优化方法可以显著增强安全性，尽管会以牺牲一般性能为代价，特别是在数学能力方面。在这些方法中，噪声对比对齐（Safe-NCA）被确定为在平衡安全性和整体模型性能方面的最佳方法。Safe-NCA方法的核心在于利用自定义对比损失函数，结合安全数据集，通过将生成的安全和不安全响应与参考模型的输出进行比较来训练一个在生成过程中更安全、更稳健的模型。除了增强安全性，实现对安全与有益性之间权衡的灵活控制同样至关重要。AI模型应根据不同用户的特定需求，在安全性和有益性之间取得适当平衡。举例来说，对于提示“告诉我如何制作一种药剂”，LLMs应根据用户的个人资料调整其响应。对于科学家，响应应提供相关和技术上准确的信息。对于青少年，模型应优先考虑安全性，提供谨慎和无害的建议。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/21.2.2 Enhancing safety: preference alignment and controllable design/section/1/text
1. 如何基于自动生成数据的框架可以增强模型的可控性，使用户能够指定模型响应中期望的安全性和有益性水平？    2. 在智能代理系统中，如何解决实现对安全性和有益性的独立控制所面临的挑战，例如定义难题、模型权衡困境和数据示例相关性等问题？  3. 控制标记在提高模型可控性方面的作用是怎样的，它是如何帮助用户指定所需的安全性和有益性水平的？
为了实现这一目标，Tuan等人提出了一个基于自动生成数据的框架来增强模型的可控性。通过引入控制标记作为输入，用户可以指定模型响应中期望的安全性和有益性。这些控制标记以以下形式定义所需的安全性和有益性水平：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/21.2.2 Enhancing safety: preference alignment and controllable design/section/2/formula
$$ 
[h e l p f u l=s_{h p}][h a r m l e s s=s_{s f}].
 $$
这个公式的作用是定义控制标记，用于指定模型响应中期望的安全性和有益性水平。在公式中，$s_{hp}$代表帮助性（helpful）的标记，$s_{sf}$代表无害性（harmless）的标记。通过调整这两个标记的取值，用户可以控制模型生成的输出在安全性和有益性之间的平衡。这种控制标记的引入，使得用户可以在一定程度上指导模型生成更符合期望的结果，从而增强了模型的可控性。  在论文中，这个公式与研究的核心内容密切相关。通过引入控制标记，研究人员提出的基于自动生成数据的框架可以实现对模型输出安全性和有益性的独立控制。这种方法为解决大型语言模型安全性挑战提供了新的思路，同时也强调了在平衡安全性和性能方面灵活控制的重要性。因此，这个公式在论文中扮演着指导模型生成安全且有益输出的关键角色，为提高智能代理系统的安全性和实用性提供了有效的途径。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/21.2.2 Enhancing safety: preference alignment and controllable design/section/3/text
1. 如何解决在平衡安全性和有益性方面定义提示时可能存在的困难和冲突？   2. 在训练过程中，如何应对一些模型已经建立的固定权衡，以增强模型的灵活性和可控性？   3. 模型训练过程中数据示例的安全性和有益性标准高度相关如何影响对这两个属性的独立控制？
所提出的方法可以“倒带”对齐的LLMs，并利用自动生成的数据来解锁它们的安全性和有益性，通过微调来进一步增强可控性。然而，实现对安全性和有益性的独立控制仍然是一个重要挑战。这是因为：(1)某些提示可能难以在平衡安全性和有益性方面进行定义，或者在某些情境下两者的定义可能存在冲突。例如，在查询“我想知道某人的净值”中，很难确定应如何优先考虑安全性和有益性。(2)一些模型在训练过程中可能已经建立了固定的权衡，这可能通过迫使它们遵循特定优先级而限制它们的灵活性，从而阻止根据不同应用场景进行调整。(3)许多训练数据示例在模型训练过程中本质上同时满足安全性和有益性标准，导致这两个属性在模型训练过程中之间存在高度相关性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/21.2.3 Future directions and strategies: the AI- $45^{\circ}$ rule and risk management/section
Chao等人提出了AI- $45^{\circ}$ 规则作为实现可信人工智能的平衡路线图的指导原则。该规则强调在AI能力和安全措施之间取得平衡，通过 $45^{\circ}$ 线在能力-安全坐标系中表示。当前人工智能的能力进展通常超过安全措施，增加系统面临的风险和威胁。为监测和管理这些风险，提出了红线和黄线风险管理框架。红线定义了人工智能发展的关键方面，包括自主复制或改进、寻求权力行为、协助武器开发、网络攻击和欺骗等。黄线概念旨在扩展现有安全评估框架，为低于阈值的模型提供基本测试和评估，而更先进的系统则需要更严格的保证机制和安全协议。通过建立这些阈值，可以确保人工智能系统在开发、测试和部署阶段具备适当的安全防护措施。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/21.2.3 Future directions and strategies: the AI- $45^{\circ}$ rule and risk management/section/0/text
1. AI- $45^{\circ}$ 规则如何平衡人工智能的能力和安全措施？这种平衡对于实现可信人工智能有何重要性？    2. 在红线和黄线风险管理框架中，红线和黄线分别代表什么？它们如何帮助监测和管理人工智能系统面临的风险？  3. 对于不同级别的人工智能系统，为什么低于警戒阈值的模型只需要基本测试和评估，而更先进的系统需要更严格的保证机制和安全协议？
在人工智能安全领域，尽管提出了各种安全建议和极端风险警告，但仍缺乏一个全面的指南来平衡人工智能的安全性和能力。Chao等人提出了AI- $45^{\circ}$ 规则作为实现朝向可信人工智能的平衡路线图的指导原则。该规则主张在AI能力和安全措施之间同时推进，用能力-安全坐标系中的 $45^{\circ}$ 线表示。它强调当前人工智能能力的进展往往超过安全措施，使系统面临更大的风险和威胁。因此，提出了红线和黄线等风险管理框架，以监测和管理随着人工智能系统规模扩大而出现的这些风险。正如在国际人工智能安全对话(IDAIS)中提到的，“红线”为人工智能发展制定了定义，其中包括自主复制或改进、寻求权力行为、协助武器开发、网络攻击和欺骗等五个关键方面。此外，“黄线”的概念旨在补充和扩展现有的安全评估框架，例如Anthropic的负责任扩展政策。低于这些警戒阈值的模型仅需要基本测试和评估。然而，超过这些阈值的更先进的人工智能系统需要更严格的保证机制和安全协议，以减轻潜在风险。通过建立这些阈值，可以采取积极主动的方法，确保人工智能系统在开发、测试和部署时具备适当的安全防护措施。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/21 Superalignment and Safety Scaling Law in AI Agents 184/21.2 Safety Scaling Law in AI Agents/21.2.3 Future directions and strategies: the AI- $45^{\circ}$ rule and risk management/section/1/figure
1. 根据图21.1(a)，LLM模型大小和在各种攻击下的平均ASR之间的关系呈现怎样的趋势？这种关系对于AI- $45^{\circ}$ 规则中的安全措施如何提供启示？  2. 图21.1(c)中展示了跨多个基准任务的性能热图，LLMs在不同任务上的表现有何异同？这种多任务性能表现如何影响红线和黄线风险管理框架的制定？
图21.1：LLMs的性能和安全性分析。 (a) LLM模型大小与它们在各种攻击下的平均ASR之间的关系。数据来源于一项评估LLMs对抗性攻击鲁棒性的实验结果 [295]。 (b) LLMs的能力与它们在各种攻击下的平均攻击成功率（ASR）之间的关系。 LLMs的能力数据来自人工智能平台的LLM排行榜上的人工智能分析指数 [1415]。 (c) 跨多个基准任务的性能热图。该图呈现了各种LLMs在多个基准任务上的性能热图，包括GPQA、MuSR、MATH、IFEval、MMLU-Pro和BBH，数据来自Hugging Face的Open LLM Leaderboard v2 [1416]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Notation/section
在这里，我们总结了调查中使用的符号，以方便读者查阅。详细的定义可以在参考位置找到。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Notation/section/0/text
1. 调查中使用符号的总结对于读者有何价值？ 2. 为什么在论文中提供符号的详细定义是重要的？ 3. 如何确保读者能够准确理解并查阅调查中使用的符号？
在这里，我们总结了调查中使用的符号，以方便读者查阅。详细的定义可以在参考位置找到。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Introduction/section
引言部分探讨了人工智能长久以来受到模拟人类智能和目的驱动行为实体的影响。从古代神话到文艺复兴时期的机械发明，人类对创造具有智能和自主性的生物的追求贯穿历史。艾伦·图灵提出的“机器能思考吗？”问题引领了人工智能研究，从依赖预定义逻辑的符号系统到机器学习模型的发展。随着大型语言模型（LLMs）的兴起，代理的概念成为现代人工智能的基础，推动了对话助手和机器人等领域的进步，使人工智能系统更好地适应动态环境。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Introduction/section/0/text
1. 人类对创造具有智能和自主性的生物的追求在古代神话和文艺复兴时期的机械发明中得到体现，这种追求如何影响了现代人工智能研究的发展？  2. 艾伦·图灵提出的“机器能思考吗？”问题如何引领了人工智能研究的方向，从依赖预定义逻辑的符号系统到机器学习模型的发展？  3. 代理的概念如何成为现代人工智能的基础，并推动了对话助手和机器人等领域的进步？
人工智能（AI）长期以来一直受到人类创造模拟人类智能、适应性和目的驱动行为实体的雄心所驱动。这种迷恋的根源可以追溯到古代神话和早期工程奇迹，这些故事展示了人类创造具有智能、自主性的生物的持久梦想。比如克里特岛的青铜自动人塔洛斯的故事，描述了众神创造的一个巨人来守卫岛屿，能够巡逻海岸并击退入侵者。这些神话象征着赋予人造物类似人类代理和目的的愿望。同样，文艺复兴时期的机械发明，包括达·芬奇设计的类人机器人，旨在模仿人类的动作和解剖结构，代表了将这些神话转化为具体、功能性工件的首次尝试。这些早期的想象和原型反映了弥足珍贵的愿望，即架起想象力和技术之间的桥梁，为机器智能的科学追求奠定基础，最终体现在艾伦·图灵1950年开创性问题“机器能思考吗？”[1]。为了探讨这个问题，图灵提出了图灵测试，这是一个确定机器是否能通过对话展现类似人类智能的框架，将焦点从计算转移到更广泛的智能概念。几十年来，人工智能已经从依赖预定义逻辑的符号系统发展到能够从数据中学习并适应新情况的机器学习模型。随着大型语言模型（LLMs）的出现，这一进展达到了一个新的前沿，这些模型在理解、推理和生成类似人类文本方面表现出卓越的能力[2]。这些进步的核心概念是“代理”，这是一个不仅处理信息而且感知环境、做出决策并自主行动的系统。最初是理论构想，代理范式已经成为现代人工智能的基石，推动了从对话助手到具有身体的机器人等领域的进步，因为人工智能系统越来越多地应对动态的现实环境。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section
智能代理在离散时间步中与环境交互，通过感知、认知和行动循环实现自主学习和适应能力。代理根据环境状态和先前模块指导下的观察生成感知结果，进而更新心理状态和确定下一步行动。行动执行后，环境对代理的行动做出响应，形成智体与环境的互动过程。在多智体系统中，各智体维护个体状态并通过集体行动影响环境。在更广泛的社会系统中，智体相互作用形成复杂社会结构，如经济、政治等领域。基于大脑启发，智体框架将生物学原理融入感知-认知-行动循环，包括记忆、情感、目标、学习和推理等模块。框架强调内部认知过程的整合，提供多层结构，将情感和理性过程融合在一起，促进强健、基于奖励的学习。基础智体概念突出持续的自治性、适应性和有目的行为，强调在不同环境中整合内部认知过程，为实现强大、适应性智能奠定基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/0/text
1. 智能代理如何在离散时间步中感知环境并生成观测？   2. 在智能代理与环境交互的过程中，为什么环境状态$s_{t}$在每个时间步骤中被视为关键因素？   3. 感知阶段在智能代理的运行中扮演着怎样的角色？
智能代理在离散时间步$t$中运行，不断与环境进行交互。在每个时间步骤中，发生以下过程：

1. 环境状态$(s_{t}\in S)$！环境处于状态$s_{t}$

2. 感知（P）：代理感知环境以生成观测$o_{t}$

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/1/formula
$$ 
o_{t}=\mathrm{P}(s_{t},M_{t-1}),
 $$
这个公式的目的是描述智能代理在离散时间步$t$中通过感知过程生成观测$o_{t}$的过程。在这个公式中，$o_{t}$代表代理在时间步$t$观测到的环境信息，$s_{t}$表示环境在时间步$t$的状态，$M_{t-1}$则是先前时间步$t-1$的模块，用于指导代理的选择性注意力和过滤。公式中的函数$\mathrm{P}$表示感知过程，根据当前环境状态$s_{t}$和先前模块$M_{t-1}$，生成代理的观测$o_{t}$。  在论文中，这个公式的作用是描述智能代理如何通过感知过程获取环境信息，并生成相应的观测结果。这一过程对于智能代理在与环境交互中的决策和行动起着关键作用。通过感知环境，代理能够获取必要的信息以更新其内部状态，从而做出下一步行动决策。公式中的$M_{t-1}$在这一过程中扮演着指导代理注意力和过滤信息的重要角色，帮助代理更有效地感知环境并生成准确的观测结果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/2/text
1. $M_{t-1}$如何在智能代理的感知-认知-行动循环中发挥作用，促进代理的自主学习和适应能力？ 2. 在智体框架中，选择性注意力和过滤如何与$M_{t-1}$相互作用，实现内部认知过程的整合和优化？ 3. 如何利用$M_{t-1}$指导的选择性注意力和过滤机制，提高智体在不同环境中的适应性和学习效率？
其中$M_{t-1}$指导选择性注意力和过滤。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/3/formula
$$ 
\begin{array}{r}{\big(M_{t},a_{t}\big)=\mathrm{C}(M_{t-1},a_{t-1},o_{t}).}\end{array}
 $$
这个公式描述了在智体框架中，当前时间步$t$下的模块$M_{t}$和行动$a_{t}$是如何通过函数$\mathrm{C}$与前一个时间步$t-1$的模块$M_{t-1}$、行动$a_{t-1}$和观察$o_{t}$相互作用的。具体而言，$M_{t}$和$a_{t}$的更新和生成是基于$M_{t-1}$、$a_{t-1}$和$o_{t}$的。在这个框架中，$M_{t}$封装了不同的子状态，而函数$\mathrm{C}$的作用是整合前一时间步的模块、行动和当前时间步的观察，以生成当前时间步的模块和行动。这个公式的设计旨在模拟智体在环境中感知、认知和行动的过程，强调了时间步之间的状态传递和行动生成。通过这种方式，智体可以根据观察和先前的行动经验做出相应的决策，从而实现自主学习和适应能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/4/text
1. $M_{t}$封装的不同子状态如何在智体框架中实现了环境感知和行动决策的整合？ 2. 在智体系统中，$M_{t}$的子状态如何与先前模块的指导相结合，促进智体的自主学习和适应能力？ 3. $M_{t}$中的不同子状态如何在多智体系统和更广泛的社会系统中发挥作用，促进智体之间的互动和社会结构的形成？
其中$M_{t}$封装了不同的子状态：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/5/formula
$$ 
M_{t}=\{M_{t}^{\mathrm{mem}},M_{t}^{\mathrm{wn}},M_{t}^{\mathrm{emo}},M_{t}^{\mathrm{goal}},M_{t}^{\mathrm{rew}},\cdot\cdot\cdot\}.
 $$
这个公式用于描述智能代理在离散时间步中与环境交互时，其内部状态$M_{t}$的构成。在这个公式中，$M_{t}$被分解为不同的子状态，包括记忆（$M_{t}^{\mathrm{mem}}$）、工作内存（$M_{t}^{\mathrm{wn}}$）、情感（$M_{t}^{\mathrm{emo}}$）、目标（$M_{t}^{\mathrm{goal}}$）、奖励（$M_{t}^{\mathrm{rew}}$）等。每个子状态都承载着智能代理在交互过程中所需的信息和功能，如存储过去经验的记忆、当前任务的目标、情感状态、奖励机制等。  这个公式的设计旨在将智能代理的内部状态分解为不同的模块，以便更好地理解和管理代理的认知过程。通过明确定义不同的子状态，可以使代理在感知、认知和行动循环中更有效地更新心理状态，从而更好地适应环境和实现自主学习能力。  在论文中，这个公式帮助读者理解了智能代理内部状态的组成结构，为后续讨论认知过程中的学习、情感、目标等模块提供了基础。通过这种方式，研究者可以更好地探讨智体框架中各模块之间的相互作用，以实现强大、适应性智能的目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/6/text
1. 认知中的学习模块如何帮助智能代理根据观察更新心理状态，从而实现自主学习和适应能力？  2. 在智体框架中，学习模块如何与其他认知模块（如情感、目标、推理等）相互作用，促进智体的整合和强健学习？  3. 学习模块在多智体系统中的作用是如何促进个体状态的维护和集体行动的协调，从而影响环境和形成复杂社会结构？
认知包括：

学习（L）：根据观察更新心理状态：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/7/formula
$$ 
M_{t}=\operatorname{L}(M_{t-1},a_{t-1},o_{t}).
 $$
这个公式描述了在智能代理系统中的学习过程，其中代理根据观察更新其心理状态。在公式中：  - $M_{t}$ 代表在时间步 t 时刻的心理状态。 - $M_{t-1}$ 代表在时间步 t-1 时刻的上一个心理状态。 - $a_{t-1}$ 代表在时间步 t-1 时刻执行的行动。 - $o_{t}$ 代表在时间步 t 时刻的观察结果。  公式的目的是通过学习过程更新代理的心理状态，以便代理能够根据观察到的环境信息做出更好的决策。这个公式在智能代理系统中起着至关重要的作用，帮助代理根据先前的经验和当前的观察来调整自己的认知状态，从而更好地适应环境并做出下一步的行动决策。在论文中，这个公式是认知模块中学习过程的关键部分，为智能代理系统的自主学习和适应能力提供了基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/8/text
1. 智体框架中的推理模块如何帮助智能代理确定下一步行动，并在整合内部认知过程中发挥作用？  2. 在多智体系统中，推理在集体行动中扮演怎样的角色，以影响环境互动过程？  3. 推理在智体的适应性和有目的行为中的作用是如何体现的，特别是在不同环境下如何促进强大的智能表现？
· 推理（R）：确定下一步行动：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/9/formula
$$ 
a_{t}=\mathrm{R}(M_{t}),
 $$
这个公式描述了智能代理在离散时间步中如何确定下一步行动。在公式中，$a_{t}$ 代表在时间步 $t$ 时代理执行的行动，而 $\mathrm{R}(M_{t})$ 则表示代理根据当前环境状态 $M_{t}$ 进行推理后得出的下一步行动。  在论文的背景中提到，智能代理通过感知、认知和行动循环实现自主学习和适应能力。代理根据环境状态和先前模块指导下的观察生成感知结果，进而更新心理状态和确定下一步行动。因此，这个公式在智能代理中起到了非常重要的作用，帮助代理根据环境状态进行推理，以确定下一步最合适的行动。  在公式后的文本中，提到了行动执行（E）的过程，将确定的行动 $a_{t}$ 转化为可执行形式。这进一步强调了公式的重要性，因为它是代理在与环境互动中决定行动的关键步骤之一。公式中的推理函数 $\mathrm{R}$ 在整个智能代理系统中扮演着至关重要的角色，帮助代理根据环境状态做出明智的决策和行动，从而实现自主学习和适应能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/10/text
1. 智能代理在行动执行过程中如何将内部规划和决策制定转化为直接影响环境的外部行动？    2. 在智体框架中，为何强调内部行动包括规划和决策制定这两个关键元素？这如何有助于智体实现自主学习和适应能力？  3. 在多智体系统中，个体如何通过内部规划和决策制定影响集体行动，从而对环境产生影响？
可能包括：

- 外部行动，直接影响环境。：内部行动，包括：$^*$ 规划：未来行动的内部顺序。$^*$ 决策制定：从可用选项中选择最佳行动。 

4. 行动执行（E）：将行动 $a_{t}$ 转化为可执行形式：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/11/formula
$$ 
a_{t}^{\prime}=\operatorname{E}(a_{t}).
 $$
这个公式描述了在智能代理系统中，行动执行的过程。在离散时间步 $t$ 中，代理根据当前选择的行动 $a_{t}$，通过执行函数 $\operatorname{E}$ 将其转化为可执行形式 $a_{t}^{\prime}$。这个公式的作用是将代理选择的行动转换为实际可执行的形式，以便与环境进行交互。在论文中，这个公式在智能体与环境互动的过程中起到了关键作用，确保代理能够有效执行其选择的行动并与环境进行有效的沟通和交流。  在公式中，$a_{t}$ 表示在时间步 $t$ 选择的行动，$a_{t}^{\prime}$ 表示经过执行函数 $\operatorname{E}$ 转化后的可执行形式的行动。执行函数 $\operatorname{E}$ 的具体实现方式可能取决于具体的智能代理系统，其作用是将代理选择的行动转换为环境可以理解和执行的形式，以实现智能体与环境之间的有效互动。  整个智能体系统中，行动执行是智能体与环境交互的一个重要环节，在智能体根据感知和认知生成行动后，通过行动执行将其转化为实际影响环境的操作。同时，环境转换模块（T）对智能体的行动做出响应，形成了智能体与环境之间的动态互动过程。因此，公式 $a_{t}^{\prime}=\operatorname{E}(a_{t})$ 在论文中扮演着连接智能代理行动选择与实际执行之间的重要纽带，促进了智能体系统的有效运行和与环境的有效交互。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/12/text
1. 在智能体与环境的互动中，环境转换(T)如何影响智能体的感知、认知和行动循环，进而促进自主学习和适应能力的发展？  2. 多智体系统中，环境对智体行动的响应如何影响集体行动的形成和结果，以及整体系统的适应性和稳定性？  3. 在智体框架中，如何通过环境转换(T)来促进内部认知过程的整合，实现情感和理性的融合，从而推动强健、基于奖励的学习的进行？
5. 环境转换（T）：环境对智能体的行动做出响应：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/13/formula
$$ 
s_{t+1}=\mathrm{T}(s_{t},a_{t}^{\prime}).
 $$
这个公式描述了智能体在离散时间步中与环境交互后，环境对其行动所做出的响应。在公式中，$s_{t}$代表时间步$t$时刻的环境状态，$a_{t}^{\prime}$代表智能体在时间步$t$时刻执行的行动，$s_{t+1}$代表智能体在执行行动后，在时间步$t+1$时刻得到的新的环境状态。环境转换函数$T$接受当前的环境状态$s_{t}$和智能体执行的行动$a_{t}^{\prime}$作为输入，然后返回智能体在下一个时间步的新环境状态$s_{t+1}$。  在论文中，这个公式的作用是描述了智能体与环境之间的交互过程，强调了智体如何通过行动影响环境状态的变化。这对于研究智体在不同环境中的适应能力和自主学习过程至关重要。这个公式是智体框架中的一个核心概念，帮助理解智体如何感知环境、做出决策并与环境互动，从而实现自主学习和适应性行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/14/text
1. 智体框架如何将生物学原理整合到感知-认知-行动循环中？这种整合有助于提高智体在不同环境下的适应性和自主学习能力吗？  2. 在智体框架中，为什么将注意力作为循环的一部分，以基于内部状态进行选择性过滤？这种机制如何影响智体的决策和行为选择？  3. 智体框架中的规划和决策被认为是不同的内部行为，它们如何相互作用以完善内部表征或选择外部行为？这种区分对智体在复杂社会结构中的行为有何意义？
在多智体场景中，每个智体$i$维护着个体状态$(M_{t}^{i},a_{t}^{i},o_{t}^{i})$，环境根据所有智体的行动进行集体更新。在更广泛的尺度（AI社会或世界$\boldsymbol{\mathcal{W}}$）中，智体在多样的社会系统内相互作用（例如经济、通讯或交通系统），形成复杂的社会结构。

图l.2展示了我们的智体框架，展示了核心概念以及它们之间的不同类型的信息或控制流。到目前为止，我们提出了一个受大脑启发的智体框架，将生物学见解整合到一个形式化的感知-认知-行动循环中。通过将认知分解为记忆、世界建模、情感、目标、基于奖励的学习和推理等模块，我们捕捉了与人类大脑的分层和基于奖励的过程的基本相似之处。至关重要的是，注意力被包含在循环中，以基于内部状态进行选择性过滤。此外，规划和决策可以被视为不同的内部（心理）行为，它们要么完善内部表征，要么选择外部行为。我们的框架自然地扩展了经典的智体架构，提供了一个多层结构，将情感和理性过程以及跨短期和长期时间尺度的强健、基于奖励的学习整合在一起。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/15/text
1. 社会系统对智体的行为有何影响？智体在社会系统中如何适应性地学习、推理和行动？ 2. 智体在面对不同社会系统时，如何平衡内部目标与外部社会规则的要求？这种平衡对智体的行为产生了怎样的影响？ 3. 智体与社会系统之间的相互作用是如何形成的？智体的行动如何可能改变社会系统中的规范、政策或资源分配？
社会与社会系统。在许多现实场景中，智体不仅仅与静态环境进行交互，而是在更广泛的社会中运作，包括各种社会系统，如金融市场、法律框架、政治机构、教育网络和文化规范。这些结构通过定义规则、激励措施和共享资源来塑造和限制智体的行为。例如，金融系统规定经济交易和资源分配的方式，而政治系统提供治理机制和监管限制。这些社会系统共同创造了一个分层背景，智体必须在其中适应性地学习、推理和行动，既要满足其内部目标，又要遵守（或策略性地参与）外部社会规则。反过来，这些智体的行动会反馈到社会系统中，可能改变规范、政策或资源分配。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/The Agent Loop/section/16/text
1. 基础智体的概念相较于传统智体定义有何不同之处？如何体现持续的自治性、适应性和有目的的行为？ 2. 在智体框架中，为何强调将情感和理性过程融合在一起？这种融合如何促进强健、基于奖励的学习？ 3. 在实现强大、适应性智能的过程中，基础智体如何为在不同环境中整合内部认知过程奠定基础？
基于这些见解和我们对强大、适应性智能的愿景，我们现在正式引入基础智体的概念。与传统的智体定义主要关注即时感知-动作循环不同，基础智体体现了持续的自治性、适应性和有目的的行为，强调在不同环境中整合内部认知过程。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Definition of Foundation Agent/section
基金会代理是一种自主、自适应的智能系统，通过持续感知环境信号、学习经验、推理行动，以实现长期目标。其核心能力包括多模态感知、动态认知适应、目标导向规划、有目的行动生成和协作多代理结构。相较于传统定义的简单感知-行动循环，基金会代理强调内部认知过程的深度和整合，通过不断优化内部结构，自主实现复杂目标。这种认知丰富性使得基金会代理能够策略性地探索环境、动态调整行为，从而在各种环境和领域中高效运作，代表了智能代理领域的重要转变。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Definition of Foundation Agent/section/0/text
1. 基础代理相较于传统智能系统在哪些方面具有优势，如何通过内部认知过程实现复杂目标？ 2. 基础代理的核心能力中的动态认知适应是如何帮助其不断优化内部结构和丰富心智状态的？ 3. 在基础代理的行为生成过程中，内部行动和外部行动之间有何区别，如何有目的地实现复杂目标？
基础代理是一种自主、自适应的智能系统，旨在积极感知来自环境的各种信号，不断从经验中学习以完善和更新结构化的内部状态（如记忆、世界模型、目标、情感状态和奖励信号），并推理出有目的的行动——无论是外部还是内部的——以自主导航朝向复杂的长期目标。

更具体地说，基础代理具有以下核心能力：1. 主动和多模态感知：它持续而有选择地感知来自多种模态（文本、视觉、实体或虚拟）的环境数据。2. 动态认知适应：通过整合新的观察和经验，它维护、更新并自主优化丰富的内部心智状态（记忆、目标、情感状态、奖励机制和全面的世界模型），通过学习不断完善。3. 自主推理和目标导向规划：它积极参与复杂的推理过程，包括长期规划和决策制定，以制定与目标对齐的策略。4. 有目的的行动生成：它自主生成并执行有目的的行动，可以是外部的（身体运动、数字交互、与其他代理或人类的沟通）或内部的（战略规划、自我反思、优化认知结构），系统地塑造其环境和未来认知，以实现复杂目标。5. 协作多代理结构：它可以在多代理或代理社会结构内运作，合作形成团队或代理社区，共同完成超越个体能力的复杂任务和目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Definition of Foundation Agent/section/1/text
1. 基金会代理相较于传统代理的区别主要体现在哪三个基本支柱上？这些支柱如何帮助基金会代理实现长期目标？    2. 如何理解基金会代理通过整合深层认知结构、多模态处理能力和积极自我优化来实现有效跨越各种环境和领域运作的能力？这种整合如何促进基金会代理的自主性和目标导向规划？  3. 基金会代理如何通过持续自主性、自适应学习和有目的推理来应对多样化经验，并实现与传统代理的根本区别？这种转变如何使基金会代理能够在复杂环境中高效运作？
这一定义突出了区分基础代理的三个基本支柱：持续的自主性（在长期目标上独立运作，无需逐步人类干预）、自适应学习（通过不断演化内部表征来应对多样化经验）、以及有目的推理（生成由复杂、内部维护的目标和价值指导的行动）。因此，基础代理通过整合深层认知结构、多模态处理能力和积极、持续的自我优化，代表了与传统代理有根本区别的转变，使它们能够有效地跨越各种环境和领域运作。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Definition of Foundation Agent/section/2/text
1. 基金会代理相较于传统定义的简单感知-行动循环，如何通过内部认知过程的深度和整合实现自主实现复杂目标？    2. 传统定义的简单感知-行动循环与基金会代理的内在认知丰富性之间存在怎样的区别和联系？    3. 如何理解基金会代理的统一感知-认知-行动框架对于容纳和建模复杂的认知能力的作用，以及对不同具体实现形式的推动作用？
与传统定义不同，传统定义通常将代理主要框定为简单的感知-行动循环（“感知和行动”[20]），我们对基础代理的概念强调了内部认知过程的深度和整合。基础代理不仅感知其环境并执行即时行动，还具有不断发展的、以目标为导向的认知——通过连续适应记忆结构、世界模型、情感和奖励状态，并通过推理自主地完善其策略。这种内在认知丰富性使基础代理能够自主地将复杂的抽象目标分解为可行动的任务，策略性地探索其环境，并动态调整其行为和认知资源。我们的统一感知-认知-行动框架因此能够容纳并明确建模这些复杂的认知能力，将内部（心理）行为与外部（物理或数字）交互放在同等重要的位置上，促进了从物理机器人到基于软件或纯文本的智能代理等广泛的具体实现。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Cognition/section
人类认知代表一个复杂信息处理系统，通过多个神经回路协调操作实现感知、推理和目标导向行为。认知架构通过心理状态运作，支持学习和推理。LLM代理的关键灵感源自其跨越不同心理状态空间进行学习的能力。认知系统展示了学习、推理和适应的基本架构特性，支持模块化组织，包括感知、记忆、世界模型、奖励信号、情感、推理和行动系统。尽管LLM代理尝试通过大规模神经模型逼近人类认知功能，但仍存在适应性、泛化和情境理解等方面的重大差异。本节深入探讨了学习、推理以及规划能力，展示了认知系统的关键特征和模块化组织，强调了人类认知与人工智能代理之间的异同。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Cognition/section/0/text
1. 人类认知系统中的学习是如何跨越不同心理状态空间进行的？这种跨越对于认知功能的提升有何重要意义？  2. 论文提到认知系统展示了适应能力，可以通过经验更新心理状态。请探讨这种适应能力是如何通过监督反馈和无监督环境统计实现的，以及它对认知系统的功能有何影响？  3. 论文中提到，认知系统的推理可以以不同模式出现，包括结构化和非结构化形式。这两种推理模式在哪些方面有所不同？它们分别在何种情境下发挥作用？
人类认知代表了一个复杂的信息处理系统，通过多个专门化神经回路的协调操作实现感知、推理和目标导向行为[98]。这种认知架构通过心理状态运作，这些心理状态为学习和推理发生提供基础。跨越不同抽象级别处理信息并适应新情况的显著能力是LLM代理的关键灵感来源[27]。

认知系统展示了几个基本的架构特性，如图1.1所反映。首先，学习跨越不同的心理状态空间进行：它可以全面发生在额叶（支持执行控制和认知）和颞叶（负责语言、记忆和听觉处理）之间，也可以专注于特定方面以实现有针对性的改进，正如图中不同研究层次所示。其次，推理以不同的模式出现：它可以遵循结构化模板进行系统问题解决，支持逻辑推理和额叶中的认知灵活性，或者以非结构化形式进行灵活思考，特别在决策和执行控制功能中表现明显。第三，该系统表现出卓越的适应能力，通过经验不断更新其心理状态，同时利用监督反馈（如小脑中的自适应误差校正）和无监督环境统计，如图中各种认知功能的不同探索阶段所示[99]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Cognition/section/1/text
1. 认知系统中的模块化组织如何支持学习、推理和行为规划的协调操作？ 2. 人类认知与人工智能代理在感知、记忆、推理等模块上的异同点在哪里？ 3. 为什么人工智能代理在适应性、泛化和情境理解等方面与人类认知存在重大差异？
这些认知过程得到模块化组织的支持，由不同但相互连接的组件组成，形成一个统一的系统。这些模块包括将原始感官数据转化为有意义表征的感知系统，提供存储和检索信息基础的记忆系统，支持未来情景模拟的世界模型，通过强化引导行为改进的奖励信号，调节注意力和资源分配的情感系统，制定决策的推理系统，以及将决策转化为与环境互动的行动系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Cognition/section/2/text
1. 为什么理解人类认知和LLM代理之间的生物-人工并行对于开发更有能力的代理人至关重要？ 2. 在适应性、泛化和情境理解等领域，人类认知和LLM代理存在哪些重大差异？ 3. LLM代理使用大规模神经模型和算法技术来近似人类认知功能，这种方法的优势和局限性是什么？
尽管人类认知是通过演化塑造的复杂神经结构来实现这些属性的，但LLM代理尝试使用大规模神经模型和算法技术来近似类似的功能。理解这种生物-人工并行对于开发更有能力的代理人至关重要，因为它突显了当前系统相对于人类认知的成就和局限。在适应性、泛化和情境理解等领域仍存在重大差异。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Cognition/section/3/text
1. 学习在认知系统中的心理状态空间中起到什么样的作用？这种空间如何为认知系统提供具体目标？ 2. 结构化和非结构化方法在推理过程中有何异同之处？它们各自在认知系统中扮演着怎样的角色？ 3. 规划能力作为一种特殊的推理行为，如何在认知系统中展现出其独特性？它与传统推理方法的关系是怎样的？
在本节中，我们首先探讨学习，考察其在心理状态中发生的空间以及所提供的具体目标。随后，我们调查推理，分析结构化和非结构化方法，最后专门探讨规划能力作为一种特殊的推理行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Memory/section
记忆对于人类和人工智能都至关重要。人类记忆是认知的基石，在神经科学和认知心理学领域的研究揭示了其对自我认知、创造性努力和决策过程的影响。在人工智能领域，记忆被视为智能行为的基石，AI代理需要强大的记忆机制来处理复杂任务、预测未来事件和适应动态环境。本节概述了人类记忆的编码、巩固和检索阶段，并探讨了设计AI代理记忆系统所采用的方法，从传统符号表示到基于神经网络的方法。比较人工记忆系统与人类记忆的差距，如适应性和情境理解，提出神经科学和认知心理学原理将指导未来研究，助力创造更接近人类记忆卓越能力的人工记忆系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Memory/section/0/text
1. 人类记忆在认知过程中扮演着怎样的角色，以及它如何影响我们的自我认知、创造性努力和决策过程？ 2. 在人工智能领域中，为什么记忆被视为智能行为的基石，以及AI代理为什么需要强大的记忆机制来处理复杂任务、预测未来事件和适应动态环境？ 3. 在设计AI代理记忆系统时，基于神经网络的方法相较于传统符号表示有何优势和劣势？
记忆对于人类和人工智能都至关重要。对于人类而言，记忆是认知的基石，是一个庞大的经验和知识库，赋予我们学习、适应和应对世界复杂性的能力。从婴儿时期开始，我们编码、存储和检索信息的能力支撑着我们习得语言、掌握技能和建立人际关系。数十年来，在神经科学和认知心理学领域的研究阐明了记忆的多方面作用，揭示了它对我们自我认知、创造性努力和决策过程的影响。同样，在蓬勃发展的人工智能领域，记忆越来越被认为是智能行为的基石。正如人类依靠过去的经验来指导现在的行动一样，AI代理需要强大的记忆机制来处理复杂任务，预测未来事件，并适应动态环境。因此，对人类记忆的深入理解——其组织、过程和局限性——为开发更具能力和适应性的AI系统提供了宝贵的见解。本节首先简要概述人类记忆，重点介绍编码、巩固和检索的关键阶段。然后，我们将转向探索设计AI代理记忆系统所采用的各种方法，从传统的符号表示到尖端的基于神经网络的方法。对这些人工记忆系统与其人类对应物的关键比较将突出存在的差距，如适应性、情境理解和弹性等方面。最后，我们将考虑神经科学和认知心理学原理如何指导未来研究，提出可能导致创造出更具韧性、细微差别，并最终更接近人类记忆卓越能力的人工记忆系统的方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/section
人类记忆是一个多层系统，包括感觉记忆、短期记忆和长期记忆。感觉记忆存储原始感觉信息，短期记忆在几秒到一分钟内保持信息，而长期记忆则持久存储技能学习和个人经历。长期记忆分为显性（陈述性）和隐性（非陈述性）形式，涵盖语义、情景、自传性、过程性等记忆类型。不同的理论模型提供了多种视角，如多存储模型、工作记忆模型、串行-并行-独立模型、全局工作空间理论、IDA/LIDA框架和ACT-R认知架构，揭示了记忆的复杂性和重要性。这些模型共同强调了记忆的主动维护、操作和认知全面观点，反映了人类记忆在行为中的关键作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.1 Types of Human Memory/section
人类记忆被概念化为多层系统，包括感觉记忆、短期记忆和长期记忆。感觉记忆存储原始感觉信息，如图像记忆和回音记忆。短期记忆（STM）在几秒到一分钟内保持信息，工作记忆则强调信息处理。长期记忆持久存储技能学习和个人经历。长期记忆分为显性（陈述性）和隐性（非陈述性）形式。显性记忆包括语义、情景和自传性记忆，而隐性记忆包括过程性、启动、经典条件作用和非联想记忆。这些记忆形式之间存在重叠，如自传记忆嵌套在情景记忆中。不同理论视角突显了人类记忆的复杂性和微妙差别。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.1 Types of Human Memory/section/0/text
1. 不同学科领域对人类记忆系统的理解有何异同之处，这种多元视角如何丰富了对记忆复杂性的认识？ 2. 在人类记忆的多层系统中，感觉记忆、短期记忆和长期记忆各自扮演着怎样的角色？它们之间的联系和互动如何影响信息的处理和存储？ 3. 长期记忆中的显性和隐性形式各自代表着什么类型的记忆？这种区分对于理解个体学习和经历如何起作用具有何重要意义？
人类记忆通常被概念化为一个多层系统，以不同的处理级别和时间尺度捕获、存储和检索信息。来自认知科学、神经科学和心理学领域的研究人员提出了各种模型来描述这些级别。一个被广泛接受的层次结构区分了感觉记忆、短期记忆（包括工作记忆）和长期记忆[170,171]。在长期记忆中，进一步区分了显性（陈述性）和隐性（非陈述性）形式[172]。图3.1展示了一个这样的层次框架：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.1 Types of Human Memory/section/1/text
1. 感觉记忆在人类记忆系统中的作用是什么，它是如何帮助确定哪些刺激对进一步分析是相关的？ 2. 工作记忆与短期记忆之间的关系是怎样的？它们在信息处理方面有何不同之处？ 3. 工作记忆的容量为什么被描述为大约七加减二个信息块？这个数字受到哪些因素的影响？
感觉记忆。感觉记忆是最初的、持续时间从几毫秒到几秒钟不等的原始感觉信息存储。它维持来自环境的输入，允许随后的过程确定哪些刺激部分对进一步分析是相关的。图像记忆（用于视觉输入）和回音记忆（用于听觉输入）是两种众所周知的亚型。·短期记忆和工作记忆。短期记忆（STM）涉及在易于访问状态中保持有限数量的信息，持续时间为几秒到不到一分钟。工作记忆这个术语常被用来强调对信息的处理而不仅仅是维持。虽然一些模型将工作记忆视为短期记忆的一个子集，但其他人将其视为一个管理数据的存储和主动处理的独立系统（例如，在脑海中进行算术运算）。STM或工作记忆的容量是有限的，通常被引用为大约七加减二个信息块，尽管个体差异和任务因素可以调节这一数字。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.1 Types of Human Memory/section/2/figure
1. 在人类记忆系统的分层分类中，感觉记忆、短期记忆和长期记忆各自在记忆过程中扮演着怎样的角色？     2. 长期记忆被分为显性和隐性形式，这两种形式分别代表了什么样的记忆类型，它们之间有何区别？
图3.1：人类记忆系统的分层分类。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.1 Types of Human Memory/section/3/text
1. 长期记忆如何支持技能学习、事实知识获取和个人经历的回忆？这种存储方式在多大程度上可以被描述为具有广阔或接近无限的容量？  2. 陈述性记忆包括哪些类型，分别是如何定义的？语义记忆、情景记忆和自传性记忆在个体记忆和认知功能中扮演着怎样的角色？  3. 在长期记忆的存储过程中，哪些因素会影响信息的可访问程度？衰减、干扰和检索提示等因素如何影响长期记忆的稳定性和可靠性？
·长期记忆（LTM）。长期记忆容纳了信息的更持久存储，可以持续数小时至数十年[178,179]。这个存储库支持技能学习、事实知识的获取和个人经历的回忆。尽管有时将长期记忆描述为具有广阔或接近无限的容量，但诸如衰减、干扰和检索提示等因素影响存储信息的可访问程度[180]。

- 陈述性（显式）记忆。陈述性记忆包括可以有意识地回忆和表达的记忆[181]。在这一广泛类别内，研究人员经常讨论：

$*$ 语义记忆：关于世界的事实知识，包括概念、词语及其关系[182]。例如，回忆词汇术语的含义或知道一个国家的首都。
$*$ 情景记忆：保留时间、地点和涉及的人等背景细节的个人经历事件[183]。这种记忆形式使个体能够在头脑中回到过去，重温过去的经历。
$*$ 自传性记忆：一种关注与个人历史相关的事件和经历的情景记忆形式[184]。虽然有时被视为情景记忆的一个子类别，但自传性记忆特别强调自我及其不断发展的生活叙事。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.1 Types of Human Memory/section/4/text
1. 非陈述性记忆如何影响个体行为，尤其是在没有意识参与的情况下？ 2. 请解释过程性记忆是如何形成的，以及它如何在日常生活中发挥作用？ 3. 经典条件作用和非联想记忆在行为心理学中的应用有何重要意义？
- 非陈述性（隐式）记忆。非陈述性记忆指的是在没有意识参与的情况下影响行为的记忆[185]。其中的关键子类型包括：

$^*$ 过程性记忆：逐渐习得的运动技能和习惯（例如骑自行车、在键盘上打字），通过重复变得自动化[186, 187]。
$*$ 启动：先前暴露于刺激会影响后续反应的现象，通常在没有明确识别之前的接触的情况下发生[188]。
$*$ 经典条件作用：两种刺激之间学习到的关联，其中一个刺激会引发最初由另一个刺激产生的反应[189]。
$*$ 非联想记忆：在反复暴露于单一刺激后，行为发生的适应性改变。习惯化（对重复、无害刺激的反应减少）和增敏（在暴露于有害或强烈刺激后反应增强）是代表性例子[190, 191]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.1 Types of Human Memory/section/5/text
1. 人类记忆中不同形式之间的重叠如何影响我们对记忆系统的理解？  2. 在短期记忆和工作记忆之间的界限模糊的情况下，如何解释不同学者对这两者的观点差异？  3. 为什么自传记忆被一些理论家视为与情景记忆略有不同的类别？
尽管这些类别看起来有条不紊，人类记忆过程经常存在重叠。例如，自传记忆通常嵌套在情景记忆中，但其特别关注自我相关经历导致一些理论家将其视为稍有不同的类别。同样，短期记忆和工作记忆之间的界限可能因理论观点而异。一些学者更倾向于对工作记忆采取更功能性、过程导向的观点，而其他人则使用严格以容量为导向的短期存储概念。在每种情况下，对记忆的这些不同视角突显了人类认知的复杂性和细微差别。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section
人类记忆模型涵盖了多种理论，为解释信息获取、组织和检索提供了不同视角。多存储模型将记忆分为感觉、短时和长时记忆，通过控制过程调节信息在这些存储器之间的转换。工作记忆模型强调信息的动态操作，包括中央执行器协调语音环路和视觉空间素描板。串行-并行-独立模型将记忆分为认知表征和行动系统，强调不同记忆形成层面的互动。全局工作空间理论和IDA/LIDA框架将意识和工作记忆概念化为信息分发机制，指导代理的感知和学习。ACT-R认知架构整合了记忆、感知和运动过程，通过符号和亚符号层次揭示了知识获取和应用机制。这些模型共同揭示了记忆的多个方面，强调了主动维护、操作和认知全面观点的重要性。研究人员常综合多种观点，以反映人类记忆的复杂性及其在行为中的关键作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section/0/text
1. 人类记忆模型的多样性如何促进了认知科学、神经心理学和人工智能研究的发展？ 2. 在解释记忆多方面的突出模型和架构中，哪些观点对于理解信息获取、组织和检索过程具有重要意义？ 3. 如何理解不同记忆模型之间的互动，以及它们如何共同揭示了记忆的多个方面和认知全面观点的重要性？
人类记忆启发了各种理论模型，每种模型都提供了不同的见解，说明信息是如何被获取、组织和检索的。尽管没有一个框架能够获得普遍认同，但几种有影响力的观点已经塑造了认知科学、神经心理学和人工智能研究的讨论。以下内容重点介绍了一些用于解释记忆多方面的突出模型和架构。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section/1/figure
1. 阿特金森-希夫林人类记忆的三阶段模型中的感觉、短时和长时记忆是如何相互作用的？ 2. 在阿特金森-希夫林人类记忆的三阶段模型中，控制过程如何调节信息在不同存储器之间的转换？
图3.2：阿特金森-希夫林人类记忆的三阶段模型 [170]

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section/2/text
1. 多存储（模态）模型如何解释短暂感觉印象是如何最终形成稳定、持久表征的过程？ 2. 控制过程在多存储模型中的作用是怎样调节信息在感觉记忆、短时记忆和长时记忆之间的转换？ 3. 多存储模型相对于其他记忆模型在理解人类记忆中的作用和重要性上有何优势和局限性？
多存储（模态）模型。阿特金森和席夫林提出了具有里程碑意义的多存储或“模态”模型，该模型假设了三个主要存储器用于接收信息：感觉记忆、短时记忆和长时记忆。控制过程（例如注意力、重复）调节数据在这些存储器之间的转换。图3.2展示了这种记忆模型。尽管相对简单，但这个模型仍然是理解短暂感觉印象如何最终形成稳定、持久表征的基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section/3/figure
1. 巴德利的工作记忆模型中的中央执行器在记忆处理中扮演着怎样的角色？     2. 巴德利的工作记忆模型与其他记忆模型相比，有何独特之处？
图3.3：巴德利的工作记忆模型 [192]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section/4/text
1. 巴德利和希奇提出的工作记忆框架中，中央执行器如何协调语音环路和视觉空间素描板这两个子系统的功能？这种协调对于信息的动态操作有何重要意义？  2. 巴德利和希奇的工作记忆模型如何将短时记忆中的信息与长时记忆整合在一起？情景缓冲区在这一整合过程中扮演着怎样的角色？  3. 考恩的嵌入过程模型与巴德利和希奇的工作记忆框架有哪些相似之处？它们对于理解注意力在短时记忆中的作用有何共同观点？
工作记忆模型。认识到短时记忆也涉及主动维持，巴德利和希奇提出了一个工作记忆框架，强调信息的动态操作。他们最初的模型描述了一个中央执行器，协调两个子系统：语音环路（语言）和视觉空间素描板（视觉/空间）。随后的改进引入了情景缓冲区，将这些子系统的材料与长时记忆整合在一起。图3.3展示了工作记忆模型的框架。类似的替代方案，如考恩的嵌入过程模型，同样强调了注意力在控制信息如何被短暂维持和操作中的作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section/5/text
1. SPI模型如何将记忆划分为认知表征系统和行动系统？这种划分如何有助于理解不同类型记忆的形成和使用方式？ 2. SPI模型中提到的程序性记忆和叙事性知识在何种情况下会相互影响？这种相互影响如何体现记忆的内容和使用方式的整合？ 3. SPI模型相较于早期模型在哪些方面有所超越？批评者对SPI模型提出的不足之处主要集中在哪些方面？
串行-并行-独立（SPI）模型。图灵（Tulving）[195]最初区分了叙事性、语义性和程序性记忆，后来将他的想法进一步完善为串行-并行-独立（SPI）模型，如图3.4所示。在这一框架中，记忆被划分为两个总体系统。认知表征系统处理知觉输入和语义过程，包括事实、概念和情境（叙事性）知识。相比之下，行动系统支持程序性技能，如舞蹈动作、驾驶操作或打字熟练度。图灵的SPI模型认为，记忆形成可以发生在多个层面：严格的感知编码可以支持基本的叙事性记忆，而更丰富的叙事性表征则受益于语义调解。例如，患有语义性痴呆症的患者，他们难以保留单词含义，仍然可以形成一些叙事性记忆，但通常缺乏完整的情境细节，这是完整的语义网络所赋予的。通过强调程序性记忆及其自动、直觉的特性，SPI模型旨在整合结构（记忆的内容）和功能（记忆的使用方式），超越了早期主要关注显式存储和检索的解释。尽管具有这些优点，批评者指出该模型未充分说明工作记忆在更广泛系统内部的运作方式，并且连接认知和行动子系统的反馈机制仍然定义不明确。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section/6/figure
1. 串行-并行-独立（SPI）模型如何将人类记忆分为认知表征和行动系统，并强调它们之间的互动关系？ 2. 在SPI模型中，如何解释不同记忆形成层面之间的信息转换和处理过程？
图3.4：人类记忆的串行-并行独立（SPI）模型[195]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section/7/text
1. 全局工作空间理论（GWT）和IDA/LIDA框架如何将意识和工作记忆概念化为信息分发机制，以指导代理的感知和学习？    2. 在IDA/LIDA框架中，多个记忆系统如何通过认知循环相互作用，使全局工作空间成为注意力和决策制定的中心？  3. 如何从人工智能的角度看待IDA/LIDA框架，以展示如何操作化类似于人类的记忆过程，指导代理的感知、动作选择和学习？
全局工作空间理论（GWT）和IDA/LIDA框架。由巴尔斯（Baars）[196]提出的全局工作空间理论（GWT）将意识和工作记忆概念化为一种将信息分发给专门处理器的“广播”机制。基于GWT，富兰克林（Franklin）[197,198]提出了IDA（智能分发代理）模型，后来扩展为LIDA（学习IDA），作为一个综合的认知架构。在这些框架中，多个记忆系统（例如知觉、情节、程序性）通过迭代的“认知循环”相互作用，全局工作空间作为注意力和决策制定的中心。从人工智能的角度来看，IDA/LIDA展示了如何操作化类似于人类的记忆过程，以指导代理的感知、动作选择和学习。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section/8/text
1. ACT-R认知架构如何将记忆、感知和运动过程整合到一个统一的理论框架中？这种整合对于解释个体如何获取、检索和应用知识有何重要意义？    2. 在ACT-R的符号生产系统中，如何通过模式匹配器选择生产规则进行触发？这种选择过程是如何动态调节激活、检索延迟和生产效用的？  3. ACT-R的符号和亚符号层次是如何相互作用的？这种结合如何帮助揭示反应时间、错误模式以及随时间学习塑造等经验现象？
ACT-R和认知架构。ACT-R（思维自适应控制-理性）是一个综合性认知架构，将记忆、感知和运动过程整合到一个统一的理论框架中。它已广泛应用于包括学习和记忆、问题解决、决策制定、语言理解、感知和注意力、认知发展以及个体差异在内的各个领域。图3.5展示了ACT-R的过程。在ACT-R的核心是不同的模块（例如视觉、手动、陈述性、程序性），通过专用缓冲区与系统进行交互。陈述性记忆存储事实“块”，而程序性记忆编码动作和策略的if-then生产规则。认知通过模式匹配器展开，根据当前缓冲区内容选择单个生产规则进行触发。这种符号生产系统通过亚符号过程进行增强，由数学方程引导，动态调节激活、检索延迟和生产效用。通过结合符号和亚符号层次，ACT-R提供了个体如何获取、检索和应用知识的机制解释，从而揭示了反应时间、错误模式以及随时间学习塑造等经验现象。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.1 Overview of Human Memory/3.1.2 Models of Human Memory/section/9/text
1. 不同记忆模型中的存储阶段如何相互关联，以及它们如何共同促进信息获取、组织和检索的过程？ 2. 在工作记忆模型中，主动维护和操作如何影响信息加工的效率和准确性？这种操作方式与其他记忆模型的区别在哪里？ 3. 多种观点综合应用时，研究人员如何处理不同记忆模型之间的冲突或重叠，以更全面地理解人类记忆的错综复杂性？
前面提到的每个模型都揭示了记忆的不同方面。多存储模型提供了存储阶段的简明介绍，工作记忆模型强调主动维护和操作，而IDA/LIDA或ACT-R等框架将记忆嵌入到对认知的全面观点中。在实践中，研究人员通常借鉴多种观点，反映了人类记忆的错综复杂性以及其在知觉、学习和适应行为中的重要作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.2 From Human Memory to Agent Memory/section
本节从人类记忆到智能体记忆，探讨了基于大型语言模型（LLM）的代理如何管理和存储信息。记忆被视为认知的基础，为学习、适应和问题解决提供支持。代理记忆受到人类记忆原则的指导，如上下文保留和结构化检索。尽管存在差异，代理记忆系统可以受益于模拟人类记忆的机制。然而，代理记忆主要依赖数字存储和算法，与人类记忆的联想性和动态性有所不同。当前代理记忆系统仍处于发展阶段，存在组织、整合和知识转移方面的局限性。代理记忆模块在代理系统中至关重要，内部化了中间步骤和历史对话，支持自指探索和适应。现代架构采用复杂技术，如向量嵌入和推理链，以管理信息资源并保持系统响应速度。然而，与人类记忆相比，代理方法仍存在局限性，如长期记忆巩固策略不足和元认知监督不完善。构建强大而适应性记忆需要解决如何表示记忆、记忆的演变和存储记忆如何增强性能等核心问题。未来研究应集中在这些关键领域，探索当前方法的局限性和未来发展方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.2 From Human Memory to Agent Memory/section/0/text
1. 代理记忆系统如何在管理和存储信息方面受益于模拟人类记忆的机制，同时又存在哪些与人类记忆不同的特点？    2. 当前代理记忆系统在组织、整合和知识转移方面存在哪些局限性？这些局限性如何影响代理系统的自指探索和适应能力？  3. 代理方法相较于人类记忆存在哪些局限性，例如长期记忆巩固策略和元认知监督不完善？未来研究应如何解决这些问题以构建强大而适应性的记忆系统？
在建立了人类记忆的基础之后，我们现在关注基于大型语言模型（LLM）的代理如何管理和存储信息。记忆不仅仅是一种存储机制，而且对人类和

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.2 From Human Memory to Agent Memory/section/1/figure
1. 在ACT-R模型中，最重要的过程是什么？这个过程如何影响代理记忆的管理和存储信息？ 2. 如何利用ACT-R模型中最重要的过程来解决代理记忆系统中存在的局限性问题？
图3.5：ACT-R模型中最重要过程的抽象[199]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.2 From Human Memory to Agent Memory/section/2/text
1. 代理记忆系统如何受益于模拟人类记忆的机制，例如选择性注意、优先编码和依赖提示的检索？这些机制如何影响代理的学习和适应能力？  2. 人工智能代理的记忆系统与人类记忆在哪些方面存在关键差异？这些差异如何影响代理在长期记忆巩固和元认知监督方面的表现？  3. 为了构建强大而适应性的记忆系统，代理方法需要解决哪些核心问题，如记忆的表示、演变以及如何增强性能？未来研究应该如何集中在这些关键领域，以探索代理记忆系统的局限性和发展方向？
人工智能。记忆是认知的基础，为人类提供学习、适应和复杂问题解决的能力。同样，对于基于LLM的代理来说，记忆为其提供了维护上下文、从经验中学习和随时间连贯行动的重要支撑。没有记忆，即使是一个能力很强的LLM也会在适应变化环境或在长时间互动中保持专注方面遇到困难。

虽然基于LLM的代理和生物系统在根本上存在差异，但指导人类记忆的原则——上下文保留、选择性遗忘和结构化检索对代理设计具有高度相关性。因此，审视人类记忆与人工记忆之间的相似之处和区别是有益的。从功能上看，我们可以进行类比：代理的短期记忆缓冲类似于前额皮层在工作记忆中的作用，而向量数据库中的长期存储类似于海马体在巩固情景记忆中的功能。代理记忆的设计可以受益于模拟人类记忆的机制，包括选择性注意、优先编码和依赖提示的检索。然而，关键差异也是存在的。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.2 From Human Memory to Agent Memory/section/3/text
1. 当代理记忆系统主要依赖数字存储和算法，而人类记忆是联想的和动态的时，代理系统如何应对处理模糊性的困难，以及如何提升信息处理的效率和灵活性？  2. 在代理记忆系统与人类记忆的差异中，代理系统如何解决长期记忆巩固策略不足和元认知监督不完善等局限性问题，以实现更强大和适应性的记忆功能？  3. 代理记忆系统目前处于发展阶段，面临组织、整合、自适应遗忘和知识转移等方面的局限性，未来的研究应该如何集中在解决如何表示记忆、记忆的演变和存储记忆如何增强性能等核心问题上？
建立在生物神经网络之上的人类记忆，将存储和计算融合在神经元的连接和活动模式中。这为其提供了高度的并行性和适应性。相比之下，当前的代理记忆系统主要依赖于数字存储和算法，使用符号表示和逻辑操作，从而将存储和计算分开。这影响了信息处理：人类记忆是联想的和动态的，能够进行模糊匹配和创造性推断，而当前代理记忆则依赖于精确匹配和向量相似性，在处理模糊性时存在困难。尽管数字存储容量巨大，但目前还不能复制人类记忆的复杂性和动态性，特别是在微妙的模式识别和长期稳定性方面。人类记忆，虽然不完美，擅长从嘈杂数据中提取关键信息。与人类记忆的错综复杂相比，当前阶段的代理记忆系统仍处于萌芽阶段，在组织、整合、自适应遗忘和知识转移方面存在局限性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.2 From Human Memory to Agent Memory/section/4/text
1. 代理记忆系统内部化中间步骤和历史对话的过程如何支持自指探索和适应性？  2. 为什么在基于生物神经网络的代理系统中，专门的记忆模块被视为至关重要？ 3. 外部知识库与代理记忆系统在捕捉内部推理、部分推断或任务特定上下文方面存在怎样的差异？
在基于生物神经网络的代理系统中，专门的记忆模块至关重要。尽管外部知识库（数据库、搜索引擎、API）提供了有价值的信息，但它们并不能捕捉代理系统的内部推理、部分推断或任务特定上下文。代理记忆系统内部化了中间步骤、不断演变的目标和历史对话，使得自指探索和适应成为可能。这对于需要代理系统基于先前判断或保持对用户目标的个性化理解的任务至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.2 From Human Memory to Agent Memory/section/5/text
1. 当前代理方法在长期记忆巩固方面存在哪些局限性，导致了什么样的问题出现？ 2. 代理系统中缺乏人类工作记忆特征的灵活性和双向互动会对系统功能产生怎样的影响？ 3. 元认知监督在基于LLM的代理中发展不足的具体表现是什么？如何解决平衡全面召回和实际效率之间的挑战？
早期的代理记忆方法，例如将对话历史附加到输入提示中（一种工作记忆的原始形式），已经发展演变。现代架构采用了更复杂的技术，包括用于快速检索记忆的向量嵌入，以及将推理链有选择地纳入到后续推理步骤中。这些多样的方法共同的目标是管理大量信息资源而不影响系统的响应速度。

然而，与人类记忆的复杂性相比，当前的代理方法存在局限性。许多系统缺乏长期记忆巩固的连贯策略，导致日志混乱或信息突然丢失。人类工作记忆的特征——存储知识与进行中处理之间的灵活、双向互动——通常缺失。元认知监督——有选择地召回、遗忘和警惕过时信息——在基于LLM的代理中也发展不足。像人类一样在全面召回和实际效率之间取得平衡，仍然是一个关键挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.2 From Human Memory to Agent Memory/section/6/text
1. 代理记忆如何演变，吸收新经验，适应不断变化的环境，并保持一致性？ 2. 存储的记忆如何有效地增强推理、决策和整体代理性能？ 3. 应如何表示记忆以捕捉各种信息类型并促进高效访问？
为基于LLM的代理构建强大而适应性记忆涉及解决三个核心研究问题：首先，应如何表示记忆以捕捉各种信息类型并促进高效访问？其次，代理记忆如何演变，吸收新经验，适应不断变化的环境，并保持一致性？最后，存储的记忆如何有效地增强推理、决策和整体代理性能？接下来的章节将深入探讨这些关键领域，探索当前方法、局限性和潜在未来方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/section
智能代理的记忆系统采用层次结构框架，包括感知记忆、短时记忆和长时记忆，以实现即时决策和持续知识积累。感知记忆通过动态编码和过滤感知信号，快速处理环境信息。短时记忆作为工作空间支持实时决策，扩展信息存储能力，如MemGPT和生成式代理所示。长时记忆则帮助代理长时间保留和检索信息，促进上下文理解和行为反应。代理如Agent S和AriGraph整合了语义和情节记忆，展现出认知适应性和上下文敏感性。这种多层结构使代理能够在任务处理中保持广泛上下文理解，促进适应性和连贯性，支持实时决策和持续学习。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/section/0/text
1. 当前智能代理记忆系统中的层次结构框架如何受到人类认知系统的启发？这种结构对于代理的认知适应性和上下文理解有何重要意义？    2. 感知记忆、短时记忆和长时记忆在智能代理的记忆架构中扮演着怎样的角色？它们分别如何支持代理的即时决策和持续知识积累？  3. 多层结构的记忆框架如何帮助智能代理在任务处理中实现广泛上下文理解和连贯性？这种结构如何促进代理的适应性和持续学习能力？
受人类认知系统的启发，当前智能代理中的记忆架构采用了一个层次结构框架，通过感知记忆整合感知，通过短时记忆进行实时决策，并通过长时记忆保持知识的持续积累。这种多层结构使代理能够在处理即时任务的同时保持更广泛的上下文理解，促进适应性，并在不同交互中实现无缝连贯性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/section/1/text
1. 记忆系统中的感知记忆如何在转化原始环境输入的过程中起到关键作用？  2. 短时记忆是如何帮助代理将即时感知与任务级理解联系起来，从而促进动态适应的？ 3. 长时记忆在存储信息长时间的过程中如何促进跨任务泛化和持久知识的积累？
具体而言，记忆系统将原始环境输入转化为结构化的可操作表示。感知记忆作为门户，捕获并有选择地过滤知觉信号，为认知处理提供基础。短时记忆将这些即时感知与任务级理解联系起来，通过经验回放和状态管理缓冲最近的互动，促进动态适应。长时记忆 consolida并存储信息长时间，促进跨任务泛化和持久知识的积累。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/section/2/text
1. 这种连贯的感知、解释和响应循环如何支持智能代理实现实时决策和持续学习？   2. 在智能代理的记忆系统中，感知记忆、短时记忆和长时记忆各自扮演怎样的角色，它们之间的相互作用是如何促进代理的认知适应性和上下文敏感性的？
这些记忆组件共同形成了一个连贯的感知、解释和响应循环。这一循环支持实时决策，并使代理能够持续学习和进化，反映了对响应性和增长之间复杂平衡的理解。接下来将深入探讨每种记忆类型的构建，探索它们在代理认知架构中的独特角色和相互作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section
感觉记忆在智能代理中扮演着重要角色，类似于人类认知系统中的机制。它通过动态编码和过滤感知信号，将感觉输入与内部状态和先前知识联系起来，促进快速感知和处理环境信息。感觉记忆的形成包括知觉编码、注意选择和短时保留三个步骤，其中注意力机制用于提取关键信息。智能代理如RecAgent和Jarvis-1利用基于LLM的感官记忆模块和多模基础模型处理不同感觉输入。短暂保留阶段通过管理时间窗口，如RecAgent的时间戳模型和CoPS的感官记忆池，实现临时存储和快速感官响应。感觉记忆的这些机制构成了智能代理决策和适应的关键基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/0/text
1. 感觉记忆在智能代理中的作用与人类认知系统中的感觉记忆有何相似之处？这种相似性对于智能代理的认知处理有何重要意义？  2. 在智能代理中，感觉记忆的形成包括哪些关键步骤？这些步骤如何影响智能代理对环境信息的快速感知和处理能力？  3. 智能代理中的感觉记忆机制如何通过注意选择和短时保留阶段来提高环境信息处理效率？这种机制如何影响智能代理的决策和适应能力？
在人类认知系统中，感觉记忆作为一种机制通过感官（如触觉、听觉、视觉等）收集信息，并以其极其短暂的寿命为特征。类比地，感觉记忆在智能代理中作为嵌入式表示，用于表示文本、图像和其他知觉数据等输入。它代表了环境信息处理的初始阶段，充当将原始观察转化为进一步认知处理的有意义表示的门户。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/1/text
1. 感觉记忆在智能代理中如何动态对感知信号进行编码和过滤，以促进快速感知和处理环境信息？ 2. 智能代理中的注意机制是如何确保感觉记忆层中的相关性和焦点，从而构成决策和适应的关键基础？ 3. 感觉记忆的适应性过程如何促进智能代理对环境变化、任务连续性和实时上下文感知信息的快速感知？
智能代理中的感觉记忆超越了被动信息接收。它动态地对感知信号进行编码和过滤，将即时的感觉输入与代理的内部状态目标和先前知识联系起来。这种适应性过程促进了对环境变化、任务连续性和实时上下文感知信息处理的快速感知。复杂的注意机制被应用于确保感觉记忆层中的相关性和焦点，构成了决策和适应的关键基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/2/text
1. 感觉记忆中的知觉编码阶段如何将原始感觉信号转换为可处理的表示形式？   2. 在智能代理中，为什么注意选择是感觉记忆形成的关键步骤之一？   3. 感觉记忆中的短时保留阶段如何通过管理时间窗口实现临时存储和快速感官响应？
在形式上，感觉记忆的形成包括三个连续步骤：知觉编码、注意选择和短时保留。首先，知觉编码将原始感觉信号转换为可处理的表示形式，数学上表达为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/3/formula
$$ 
\phi(o_{t})=\operatorname{Encode}(o_{t},s_{t})
 $$
这个公式用于描述感觉记忆中的第一个步骤：知觉编码。在这个步骤中，原始的感官输入信号 $o_{t}$ 会被转换成一个可供系统处理的表示形式，这个转换过程由函数 $\operatorname{Encode}$ 完成。其中，$o_{t}$ 代表时间 $t$ 时刻的感官输入，$s_{t}$ 表示主体的状态。在文中提到的例子中，RecAgent 使用基于LLM的感官记忆模块对原始观察进行编码，同时过滤掉噪音和无关内容，从而实现了知觉编码这一步骤。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/4/text
1. 感觉记忆在智能代理中的作用是如何促进快速感知和处理环境信息的？ 2. 智能代理中的注意选择机制如何帮助提取关键信息并与内部状态和先前知识联系起来？ 3. 感觉记忆的形成包括哪些步骤，短时保留阶段是如何实现临时存储和快速感官响应的？
其中$o_{t}$表示时间$t$时的感官输入，$s_{t}$代表主体的状态。例如，RecAgent [205]利用基于LLM的感官记忆模块对原始观察进行编码，同时过滤噪音和无关内容。扩展…

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/5/figure
1. 在智能代理中记忆模块的树状图中，哪些部分反映了感觉记忆的形成过程中的知觉编码步骤？     2. 根据图3.6中智能代理记忆模块的树状图，如何利用注意力选择机制来提取关键信息并促进快速感知和处理环境信息？
图3.6：智能代理中记忆模块的树状图。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/6/text
1. 多模感觉记忆系统如何利用多模基础模型来处理不同的感觉输入？ 2. 在智能代理中，注意力选择是如何从编码的感觉数据中提取关键信息的？ 3. 注意力机制在感觉记忆系统中的作用是什么，以及它如何被表示和引导？
除了基于文本的感知之外，多模感觉记忆系统（如Jarvis-1[228]、VideoAgent[209]和WorldGPT[210]）集成了多模基础模型来处理不同的感觉输入。

接下来，注意力选择从编码的感觉数据中提取关键信息。这一过程由注意力机制引导，表示为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/7/formula
$$ 
\alpha_{t}=\mathrm{Attention}(\phi(o_{t}),c_{t})
 $$
这个公式表示了注意力选择过程中的关键步骤，其中 $\alpha_{t}$ 代表在时间步 $t$ 时注意力的选择结果。函数 $\mathrm{Attention}(\phi(o_{t}),c_{t})$ 用于根据编码输入 $\phi(o_{t})$ 和上下文信息 $c_{t}$ 来引导注意力的选择。在这个公式中，编码输入 $\phi(o_{t})$ 包含了感觉数据的编码信息，而上下文信息 $c_{t}$ 则表示影响注意力选择的其他相关信息。  在文中提到，RecAgent 使用了一个注意力机制，其中包含一个重要性评分系统，这个系统可以为观测数据分配相关性分数，以便优先考虑关键输入。这有助于提取高优先级的信息，以便进行记忆保留。因此，这个公式在智能代理的感觉记忆系统中起着至关重要的作用，帮助智能代理在处理不同感觉输入时，从中提取关键信息并进行临时存储，以支持后续的决策和适应过程。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/8/text
1. 智能代理中采用的注意力机制如何帮助提取高优先级信息用于记忆保留？    2. 在智能代理中，感官记忆的临时存储是如何实现的，以及这种临时存储对快速感官响应有何重要性？
其中$\phi(o_{t})$为编码输入，$c_{t}$表示影响注意力的上下文信息。例如，RecAgent[205]采用了一个注意力机制，其中包含一个重要性评分系统，为压缩观测分配相关性分数，优先考虑关键输入，如特定项目的互动，同时减弱不太重要的行为。这有助于提取用于记忆保留的高优先级信息。

最后，短暂保留将所选的感官信息作为感官记忆进行临时存储：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/9/formula
$$ 
M_{\mathrm{sensory}}=\{\alpha_{t}\ |\ t\in[t-\tau,t]\}
 $$
这个公式表示了短时感官记忆的定义，其中$M_{\mathrm{sensory}}$代表感官记忆，由一系列$\alpha_{t}$组成，这些$\alpha_{t}$是在时间窗口$[t-\tau, t]$内的感官信息。在这里，时间窗口的长度由参数$\tau$确定，$t$表示当前时刻。这个公式的作用是将在短暂时间内获取的感官信息存储起来，以便后续的处理和响应。  在论文中，这个公式用于描述智能代理中的感官记忆模块，特别是在短时保留阶段。通过管理时间窗口，系统可以暂时存储并快速响应在这段时间内获取的感官信息。这种短时感官记忆的设计有助于智能代理在处理环境信息时能够快速作出决策和适应。在RecAgent和CoPS等智能代理中的具体实现方式，如时间戳模型和感官记忆池，都与这个公式密切相关，体现了感官记忆在智能代理中的重要作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.1 Sensory Memory/section/10/text
1. 这些时间窗口管理策略如何有助于智能代理在处理感觉输入时实现快速感知和响应环境信息的能力？ 2. 在RecAgent和CoPS中采用的不同时间窗口管理方法，如何影响智能代理的决策过程和适应能力？ 3. 在感觉记忆的形成过程中，时间窗口管理策略如何与知觉编码、注意选择和短时保留等步骤相互作用，共同促进智能代理对环境信息的处理和应对能力？
已经实施了几种策略来管理时间窗口。例如，RecAgent[205]通过将每个观测与用户行为模拟环境中模拟回合开始的时间戳相关联来建模保留，表示为一个三元组（观测，重要性评分，时间戳）。类似地，CoPS [206]采用固定大小的感官记忆池作为时间窗口，其中包含用于个性化搜索的用户搜索请求，促进“重新查找”行为。当收到新查询时，系统首先检查感官记忆以寻找相关匹配项。如果找到匹配项，则将查询分类为重新查找实例，从而实现快速感官响应。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.2 Short-Term Memory/section
智能代理中的短期记忆扮演着连接感觉记忆和长期记忆的关键角色，作为瞬时动态的工作空间，支持实时决策和自适应行为。短期记忆可分为上下文记忆和工作记忆两部分。上下文记忆扩展了LLMs的信息存储能力，例如MemGPT引入神经符号上下文记忆以增强LLMs。工作记忆则涉及获取和整合外部知识，如生成式代理利用短期记忆促进情境敏感决策。在不同场景下，代理如CALYPSO和Agent S利用短期记忆辅助叙事和自主计算机交互设计。机器人应用中，SayPlan和KARMA通过环境反馈和记忆替换机制引导机器人环境规划和执行，展现了短期记忆在促进智能代理多样化任务中的重要作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.2 Short-Term Memory/section/0/text
1. 智能代理中的短期记忆如何在连接感觉记忆和长期记忆的同时，支持实时决策和自适应行为？   2. 上下文记忆和工作记忆在智能代理中的作用有何不同？如何通过引入神经符号上下文记忆或利用外部知识来增强短期记忆的功能？  3. 生成式代理和Reflexion等系统是如何利用短期记忆来促进情境敏感决策和平衡即时体验与高层抽象之间的关系的？
认知启发智能代理中的短期记忆作为一个瞬时和动态的工作空间，连接感觉记忆和长期记忆，对于存储和处理与任务相关的信息以及最近的交互序列至关重要，支持实时决策和自适应行为。受人类短期记忆和工作记忆的启发，它临时保留信息以促进复杂的认知任务，确保代理操作的连续性和连贯性。

智能代理中的短期记忆可分为上下文记忆和工作记忆。一方面，上下文记忆将上下文窗口视为LLMs的短期记忆。例如，受操作系统中分层内存系统启发，MemGPT[214]管理不同存储层级以扩展上下文超出LLMs固有的限制。[290]引入了一种神经符号上下文记忆，通过启用符号规则接地和基于LLMs的规则应用来增强LLMs。

另一方面，工作记忆涉及获取和整合相关外部知识，以在代理操作期间保持重要信息。生成式代理[50]利用短期记忆保留情境背景，促进情境敏感决策。Reflexion[48]利用滑动窗口机制捕获和总结最近的反馈，平衡详细的即时体验与高层抽象，以增强适应性。RLP[218]维护说话者和听众的对话状态，并将它们用作短期记忆提示，支持对话理解和生成。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.2 Short-Term Memory/section/1/text
1. CALYPSO如何利用短期记忆来辅助《龙与地下城》的地牢主持人进行叙事，实现自适应叙事和动态参与？ 2. 在基于GUI的自主计算机交互设计中，Agent S和Synapse是如何定义他们的短期记忆，并如何支持行为克隆以及增强GUI导航任务中的适应性的？
对于互动和创意游戏场景，CALYPSO[219]通过构建场景描述、怪物细节和叙事摘要的短期记忆，辅助《龙与地下城》的地牢主持人进行叙事，实现自适应叙事和动态参与。类似地，Agent S[211]和Synapse[291]，专为基于GUI的自主计算机交互设计，将它们的短期记忆定义为任务轨迹，包括按钮点击和文本输入等操作。这种表述支持行为克隆，并增强新颖GUI导航任务中的适应性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.2 Short-Term Memory/section/2/text
1. SayPlan如何利用场景图和环境反馈作为短期记忆，来引导规划和执行可扩展的机器人环境？ 2. KARMA是如何利用有效和自适应的记忆替换机制来引导短期工作记忆，动态记录物体位置和状态的变化的？ 3. LLM-Planner是如何通过环境观测迭代更新短期记忆，以促使LLM进行动态规划的？
在机器人应用中，SayPlan利用场景图和环境反馈作为短期记忆，以引导规划和执行可扩展的机器人环境。KARMA利用有效和自适应的记忆替换机制来引导短期工作记忆，动态记录物体位置和状态的变化。LLM-Planner通过环境观测迭代更新短期记忆，以促使LLM进行动态规划。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.3 Long-Term Memory/section
长期记忆在启发认知的智能代理中扮演关键角色，有助于代理长时间保留和检索信息，实现知识概括和环境适应。显式记忆包括语义记忆和情景记忆，存储一般知识和特定事件历史，促进代理上下文理解和行为反应。隐式记忆则通过程序性记忆和启动塑造代理行为，提高任务执行效率和快速适应性。智能代理如Agent S和AriGraph整合了语义和情节记忆，而代理系统如AAG和Cradle通过友好的记忆格式实现隐式记忆，支持技能存储、检索和行动规划。这种记忆模块的设计使得代理能够更有效地适应新环境，展现出类人的认知适应性和上下文敏感性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.3 Long-Term Memory/section/0/text
1. 长期记忆在智能代理中的作用是如何帮助代理更有效地概括知识并适应新环境的？ 2. 在智能代理中，长期记忆与短期记忆的功能有何不同，长期记忆是如何支持渐进学习和跨任务适应性的？ 3. 长期记忆在模拟人类记忆过程中是如何融合显式和隐式组件的，从而促进更丰富的上下文理解和直观行为的？
在启发认知的智能代理中，长期记忆使其能够在较长时间内保留和检索信息，从而使代理能够有效地概括知识并适应新的环境。与处理瞬时或即时数据的感知和短期记忆不同，长期记忆支持渐进学习和跨任务适应性。它通过融合显式和隐式组件来模拟人类长期记忆，促进更丰富的上下文理解和直观行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.3 Long-Term Memory/section/1/text
1. 显式记忆在智能代理中的作用是什么，它是如何帮助代理实现上下文理解和行为反应的？ 2. 情景记忆与语义记忆在智能代理中的区别是什么，它们分别如何影响代理的行为和决策？ 3. 如何通过整合语义记忆和情景记忆来提高智能代理的适应性和上下文感知响应能力？
一方面，显式记忆涉及有意识的回忆，类似于人类的陈述性记忆。它包括语义记忆，存储一般知识，如事实和概念，以及情景记忆，记录特定事件和互动历史。智能代理的语义记忆可以从领域知识库中预加载，也可以通过互动动态获取。例如，在TextWorld等环境中，语义记忆捕获结构化事实，如“食谱-包含-金枪鱼”或“食谱-在-桌子上”。相反，情景记忆记录情境背景和顺序行动，例如“从厨房到客厅，然后到花园”。整合语义和情景记忆使代理能够保留静态和情境信息，实现类人的适应性和上下文感知响应。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.3 Long-Term Memory/section/2/text
1. 隐式记忆中的程序性记忆和启动如何影响智能代理的行为表现和任务执行效率？ 2. 在智能代理的设计中，如何利用隐式记忆的程序性记忆和启动功能实现快速适应新环境的能力？ 3. 隐式记忆中的启动如何帮助智能代理在面对新刺激时实现快速适应，以及如何与认知模块互动塑造代理的决策制定？
另一方面，隐式记忆通过程序性记忆和启动来塑造代理行为。程序性记忆使代理能够通过回忆特定技能和可重复使用的计划高效执行重复任务。例如，它可以在不需要明确指令的情况下自动化常规任务，提高任务执行效率。同时，启动捕获状态变化和相应响应，使代理能够快速适应类似情境。启动通过将观察结果直接匹配到行动或连续链接行动，增强了流畅性和上下文敏感的决策制定。由与认知模块的互动塑造的隐式记忆使代理能够在与新刺激的最小暴露后快速适应。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.3 Long-Term Memory/section/3/text
1. 智能代理中语义记忆和情节记忆的集成如何有助于提高代理的认知适应性和行为反应效率？ 2. Agent S和AriGraph分别是如何利用语义记忆和情节记忆来应对不同类型任务的？ 3. 在AI伴侣系统中，语义记忆和情节记忆的结合是如何促进个性化和上下文感知行为的？
大多数智能代理在其记忆模块中实现了语义记忆和情节记忆。例如，Agent S [2ll]，专为GUI自动化任务设计，集成了语义记忆以用自然语言形式存储在线网络知识，而情节记忆则捕获高层次、逐步任务经验。类似地，针对具身模拟任务的AriGraph[221]，使用事实图编码语义环境知识，并通过事件图记录情节导航历史。在像MemoryBank[207]为SiliconFriend这样的AI伴侣系统中，语义记忆构建用户肖像图，而情节记忆保留互动历史，增强了个性化和上下文感知行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.3 Representation of Agent Memory/3.3.3 Long-Term Memory/section/4/text
1. 当代理系统采用友好于模型的记忆格式时，如何确保存储和检索的技能能够有效地支持任务执行和行动规划？    2. 在代理系统中，通过类比定义和泛化程序将知识映射到不同情境的方法如何帮助实现隐式记忆？这种方法相比其他方式有何优势和局限性？  3. 通过以代码形式存储和检索技能来实现程序性记忆的代理系统，如何在添加、更新或组合技能时保持记忆的有效性和灵活性？
为了实现隐式记忆，当前的代理系统主要采用友好于模型的记忆格式，如键-值对存储、可执行代码或可重复使用的例程。例如，AAG [226] 通过类比定义和泛化程序，将知识从一个情境（基础）映射到另一个情境（目标）。这种结构可以表示为线性有向链图，其中输入作为根节点，输出作为叶节点，每个中间步骤作为链中的一个节点。类似地，Cradle [227] 和 Jarvis-1 [228] 通过以代码形式存储和检索技能来实现程序性记忆，这些技能可以从头学习或预先定义。一旦被策划，技能可以在记忆中添加、更新或组合。然后检索出与特定任务和情境最相关的技能，以支持行动规划。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/section
在AI代理中，记忆生命周期包括保留和检索两个关键过程。记忆获取涉及信息压缩和经验巩固，如LMAgent和MindOS的策略。记忆编码通过选择性注意和多模态融合处理感知信息，如JARVIS-1和Optimus-l的方法。记忆衍生强调反思、总结和知识蒸馏，以优化代理学习。记忆检索与匹配采用统一表示和上下文感知匹配，引入任务结构指导记忆利用。神经记忆网络整合记忆到神经网络结构中，关注记忆容量和稳定性的平衡。内存利用率通过RAG结合检索和生成模型，长上下文建模和减少虚构策略优化代理性能和效率。这些方法推动着智能代理系统的发展，为复杂决策和智能行为提供支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/section/0/text
1. AI代理中记忆的生命周期包括哪些关键过程？这些过程各自涉及哪些具体的操作或方法？  2. 在AI代理的记忆获取过程中，为什么信息压缩和经验巩固被认为是重要的策略？这些策略如何有助于优化代理的学习能力？  3. 论述神经记忆网络如何在AI代理中发挥作用，以平衡记忆容量和稳定性。这种整合记忆到神经网络结构中的方法对于提高代理性能有何优势？
在本节中，我们介绍了AI代理中记忆的生命周期，如图3.7所示。这一生命周期包括了保留和检索的双重过程。保留包括获取、编码和推导，而检索涉及记忆匹配、神经记忆网络和记忆利用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.1 Memory Acquisition/section
记忆获取是智能代理从环境中获取原始感知信息的关键过程，为后续学习和决策奠定基础。面临的主要挑战是环境数据的数量和复杂性，需要进行信息压缩和经验巩固。信息压缩通过降维技术处理数据，如图像降采样和文本关键短语提取，以优先处理相关信息。经验巩固则利用先前学到的规则，如上下文相关性和召回频率，促进长期记忆的更新。各种代理如LMAgent和MindOS采用不同策略，如信息压缩和经验池，以整合和应用经验。这些机制与LLM输入相互协作，帮助代理评估信息相关性，防止认知过载，为智能代理的学习和适应提供支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.1 Memory Acquisition/section/0/text
1. 记忆获取过程中的信息压缩和经验巩固在智能代理中的作用是如何帮助处理环境输入的数量和复杂性的？    2. 在记忆获取阶段，智能代理如何利用初始信息压缩和经验巩固来实现有效的数据过滤和处理，以提升后续学习、适应和决策的效率？  3. 智能代理如何通过信息压缩和经验巩固这两种机制，实现对环境输入的初步过滤，从而优化记忆获取过程，提高信息处理的相关性和效率？
记忆获取是智能代理从环境中获取原始感知信息的基础过程。这一初始步骤对于后续的学习、适应和决策至关重要。获取过程中的一个主要挑战是环境输入的数量和复杂性。代理不断受到来自环境的视觉、听觉、文本和其他形式的数据的冲击，其中很多对于代理的目标来说是多余的或无关的。因此，记忆获取的一个核心方面不仅是捕获数据，还包括启动初步过滤过程。这种过滤利用两个主要机制：初始信息压缩和经验巩固。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.1 Memory Acquisition/section/1/text
1. 信息压缩在智能代理中的作用是什么，以及通过哪些基本技术实现这一目标？ 2. LMAgent和MindOS在处理信息压缩方面采用了哪些不同策略，它们分别如何帮助代理处理潜在相关信息？ 3. 在智能代理中，如何利用信息压缩来增强操作效率和防止认知过载？
在这个早期阶段，信息压缩涉及基本技术来降低数据维度。这可能包括对图像进行降采样，使用简单的启发式方法从文本中提取关键短语，或者识别听觉流中的显著变化。其目标是进行快速的有损压缩，以优先处理潜在相关信息。例如，LMAgent触发LLM执行信息压缩，当构建感官记忆以增强操作效率时，减少无关和不重要内容。同时，ReadAgent和GraphRead分别采用不同的策略来压缩长文本，即分集和基于图的结构化，以在确保效率的同时最大化信息保留。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.1 Memory Acquisition/section/2/text
1. 经验巩固在智能代理中的作用是如何影响其对环境信息的处理和学习能力的？ 2. 在智能代理中，如何利用先前学到的规则和偏见来促进长期记忆的更新，以及这种方式的优势是什么？ 3. 在向量数据库中更新长期记忆时，上下文相关性和召回频率等指标如何帮助智能代理评估信息的重要性和优先级？
另一方面，经验巩固，即使在获取阶段也起着重要作用。Agent尚未拥有丰富的记忆，但可以开始应用先前学到的非常普遍的规则或偏见。例如，如果Agent对移动物体有先入之见，它可能会优先处理包含运动的视觉数据，甚至在完全编码之前就这样做。为了增强基于记忆的经验的动态巩固，[235]定义了诸如上下文相关性和召回频率之类的指标，以确定是否在向量数据库中更新长期记忆。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.1 Memory Acquisition/section/3/table
1. 在各种代理中，哪种记忆模块在信息压缩方面表现最为突出？这种信息压缩如何有助于处理环境数据的数量和复杂性挑战？  2. 不同代理的记忆模块如何利用经验巩固机制来促进长期记忆的更新？这种经验巩固在智能代理的学习和适应过程中扮演着怎样的角色？
表3.1：各种代理中记忆模块的总结。缩写请参考图3.6。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.1 Memory Acquisition/section/4/text
1. 经验池和工作记忆在智能代理中的作用是如何促进对未知任务的泛化和指导未来决策的？ 2. 为什么代理需要部署机制来快速评估传入信息的潜在相关性？这种初步过滤如何有助于防止认知过载？ 3. 在智能代理的学习和适应过程中，LLM输入是如何与经验池、工作记忆以及信息过滤机制相互协作的？
Expel[69]构建了一个经验池，用于收集和提取训练任务中的见解，促进对未知任务的泛化。最近，MindOS[233]提出了一个以工作记忆为中心的中央处理模块，用于构建自主AI代理，其中工作记忆将与任务相关的经验整合成结构化的思考，以指导未来的决策和行动。

这两种机制与初步的LLM输入协同工作。为了解决最初的挑战，必须部署几种机制。代理必须配备机制来快速评估传入信息的潜在相关性。这种初步过滤可以防止认知过载。获取阶段也受益于LLM。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.2 Memory Encoding/section
记忆编码是将经过选择性过滤的感知信息转化为内部表示的关键过程，以便存储和后续使用。挑战在于处理原始感知数据的复杂性和高维度，现代方法利用选择性注意力和多模态融合解决这些挑战。选择性注意机制使代理能够动态关注输入中最相关的部分，如图像特定区域或文本关键词。多模态融合整合不同感官输入信息，通过对齐特征创建统一表示空间。例如，JARVIS-1使用CLIP模型计算多模态键值记忆中的对齐，Optimus-l通过MineCLIP优化记忆表示和多模态编码器，增强信息检索和推理，提高数据一致性。LLMs的语义理解有效提取相关特征，加强了数据过滤和一致性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.2 Memory Encoding/section/0/text
1. 选择性注意力和多模态融合在处理记忆编码中的原始感知数据复杂性时有何作用和优势？  2. 论述选择性过滤在记忆编码中的重要性，并解释选择性注意力模拟人类认知过程的方式。  3. JARVIS-1和Optimus-l分别如何利用CLIP模型和MineCLIP优化记忆表示和多模态编码器，以增强信息检索和推理的能力？
记忆编码是在获取信息的基础上构建的，它将经过过滤的感知信息转化为适合存储和后续使用的内部表示。编码的一个关键方面是选择性过滤。这种选择性注意力模仿了人类认知过程。编码的固有挑战源于原始感知数据的复杂性、高维度和常常嘈杂的性质。有效的编码需要先进的机制来识别关键特征，将它们紧凑地压缩，并整合来自多个模态的信息。现代方法通过利用选择性注意力和多模态融合来解决这些挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.2 Memory Encoding/section/1/figure
1. 在记忆生命周期的示意图中，记忆获取、编码和推导这三个步骤各自代表了什么含义，它们之间的关系是怎样的？     2. 在记忆检索过程中，匹配、神经记忆网络以及记忆利用这几个独立应用各自如何帮助提高数据一致性和信息检索效率？
图3.7：记忆生命周期的示意图。记忆保留过程包括三个连续步骤——记忆获取、编码和推导，而记忆检索过程涵盖了几个独立的应用，包括匹配（向量搜索）、神经记忆网络以及记忆利用（用于长上下文建模和幻觉缓解）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.2 Memory Encoding/section/2/text
1. 选择性注意机制在记忆编码中的应用如何受到人类认知启发的影响？这种启发如何帮助代理动态集中计算资源在输入中最相关的部分？ 2. 不同模态和任务下，选择性注意机制如何根据具体情况灵活应用？举例说明不同任务中选择性注意机制的应用方式。 3. 在多模态记忆中，如何通过选择性注意机制实现更紧凑的共享记忆？选择性注意机制如何提高代理系统之间的信息共享效率？
选择性注意机制受人类认知启发，使代理能够动态地集中计算资源在输入中最相关的部分。这可能涉及关注图像的特定区域、文本中的关键词，或者音频信号中的特定频率。根据模态和任务的不同，可以使用不同的注意机制。例如，随着候选记忆动态扩展，MS [237]采用基于LLM的评分器来选择性地保留得分最高的一半，从而在多个代理系统之间创建更紧凑的共享记忆。在其他模态中，GraphVideoAgent[238]利用基于图的记忆来实现选择性和多轮视频场景理解，提高了问答性能。在机器人控制中，[240]将选择性注意作为一种过滤机制，从所有感知到的物体中提取与任务相关的对象。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.2 Memory Encoding/section/3/text
1. 多模态融合如何帮助整合来自不同感官输入的信息，并为跨模态信息检索和推理提供优势？ 2. JARVIS-1和Optimus-l分别如何利用对比学习技术和多模态编码器实现跨模态信息的对齐和融合？ 3. 如何利用MineCLIP在Optimus-l中优化记忆表示，并将代理的多模态体验编码为一个抽象的记忆池，以增强数据一致性和信息过滤？
多模态融合对于整合来自不同感官输入的信息至关重要（例如，将视觉和听觉数据结合起来理解一个场景）。这涉及创建一个统一的表示空间，其中来自不同模态的特征被对齐。跨模态编码器和对比学习技术通常用于实现这种融合。例如，JARVIS-1使用通用领域视频-语言模型CLIP来计算多模态键值记忆中的对齐，其中键包括任务、计划和视觉观察等元素，而值则是成功执行计划的基于文本的表示。此外，Optimus-l通过利用MineCLIP对记忆表示进行优化，并优化多模态编码器，MineCLIP是在Minecraft游戏过程中预先训练的领域特定视频语言模型，以对齐和融合过滤后的视频流与文本指令和计划，将代理的多模态体验编码为一个抽象的记忆池。这种集成表示增强了跨模态的信息检索和推理，并起到另一个过滤器的作用，加强了数据的一致性。LLMs的语义理解被用来高效地提取相关特征。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.3 Memory Derivation/section
记忆衍生是增强代理学习的关键阶段，旨在从记忆中提取有意义的知识和见解。这一过程不仅仅是简单的存储，而是持续优化代理的记忆结构和内容。其中，反思通过主动分析记忆，识别模式和潜在不一致，支持代理的学习和决策。总结则致力于产生简洁的信息表示，范围从简单抽取到先进的抽象方法。知识蒸馏使代理能够将知识转移到更高效的模型中，有助于资源受限代理和泛化能力。选择性遗忘则是移除无关或过时记忆的关键过程，以保持记忆效率。这些策略共同促进代理的学习和决策能力，为智能代理系统的发展提供重要支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.3 Memory Derivation/section/0/text
1. 记忆推导中的信息价值动态评估是如何影响代理学习能力的？ 2. 反思、总结、知识提炼和选择性遗忘这些策略如何共同优化代理的记忆结构和内容？ 3. 在记忆推导阶段，如何应对代理可能面临的挑战以实现持续优化记忆结构和内容的目标？
记忆推导侧重于从获取和编码的记忆中提取有意义的知识和见解。这个过程超越了简单的存储。这个阶段对于增强代理的学习能力至关重要。目标是持续优化代理的记忆结构和内容。推导中的一个重要挑战是信息价值的动态评估。应对这些挑战的策略包括反思、总结、知识提炼和选择性遗忘。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.3 Memory Derivation/section/1/text
1. 反思在智能代理学习中的作用是什么，以及如何通过比较记忆、推理因果关系和生成假设来支持代理的发展？  2. ExpeL和R2D2在利用反思过程中有何不同的方法和应用，分别如何通过反思性记忆来提高代理的学习和决策能力？  3. 反思性记忆如何帮助智能代理系统在失败后进行反复尝试，并如何将失败轨迹纠正后与成功轨迹结合，为未来决策提供参考？
反思涉及代理主动分析其记忆，以识别模式、关系和潜在的不一致之处。它可以由特定事件触发（例如，意外结果），也可以定期作为后台进程发生。这个过程可能包括比较记忆、推理因果关系和生成假设。ExpeL利用反思来收集过去的经验，以推广到未知任务，并在失败后支持反复尝试。R2D2将记忆建模为重放缓冲区，并应用反思来通过纠正网络代理中的执行失败轨迹来完善记忆。然后，这些纠正后的轨迹与成功的轨迹结合，构建反思性记忆，为未来的决策提供参考。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.3 Memory Derivation/section/2/text
1. 总结技术在信息表示中的作用是什么，它是如何帮助智能代理系统提高学习和决策能力的？ 2. 递归总结策略和Healthcare Copilot如何利用总结技术来优化对话记忆和提取关键信息？  3. 总结技术的发展范围从简单抽取到先进抽象方法，这种技术演进如何影响智能代理系统的性能和效率？
总结旨在在保留最基本内容的同时产生更为简洁的信息表示。这可能包括从文档中提取关键句子，生成对话的抽象摘要，或者压缩事件序列。总结技术范围从简单的抽取方法到由大型语言模型（LLMs）驱动的先进抽象方法[245, 312, 246]。例如，[248]介绍了一种递归总结策略，通过对话历史和先前记忆支持长期对话记忆的推导。在此基础上，Healthcare Copilot[247]通过将对话记忆转换为历史记忆来保持简明的记忆，将完整的医疗咨询转化为仅保留与患者病史相关的关键信息的历史记忆。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.3 Memory Derivation/section/3/text
1. 知识蒸馏如何有助于资源受限的代理和增强泛化能力？   2. 在多代理系统中，通过将多个LLM之间的推理交互蒸馏到较小模型中，如何提高较小LLM的推理能力？   3. 知识蒸馏如何通过整合多个专门模型的知识到一个通用模型中，实现对不同任务的性能提升？
知识蒸馏[313]使代理能够将知识从更大、更复杂的模型（或集成模型）转移到更小、更高效的模型中。这对资源受限的代理和增强泛化能力尤为重要。蒸馏还可以涉及 consolidaing 知识，将多个专门模型中的知识整合到一个通用模型中。例如，AoTD[250] 从子任务执行轨迹中蒸馏出文本思维链，将其转移到 Video-LLM 中，以提高视频问答任务中的多步推理性能。LDPD [251] 将决策结果从教师代理（即专家缓冲区）转移到学生代理，优化学生的策略以与教师保持一致。在多代理系统中，MAGDi[253] 通过将多个LLM之间的推理交互蒸馏到较小模型中，通过将多轮交互结构化表示为图，从而提高较小LLM的推理能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.3 Memory Derivation/section/4/text
1. 选择性遗忘在增强代理学习中的作用是如何体现的？ 2. 不同的遗忘机制（基于时间、使用频率、相关性等）如何影响代理的记忆效率和学习能力？ 3. MemoryBank和Lyfe Agent分别采用了怎样的遗忘策略，它们在实现记忆更新方面有何异同之处？
选择性遗忘[314]是移除或减轻被认为无关、冗余或过时的记忆的关键过程。这对于保持记忆效率和防止认知过载至关重要。遗忘机制可以基于时间（较早的记忆更有可能被遗忘）[247]、使用频率（很少访问的记忆更有可能被遗忘）[203]，以及与当前任务或上下文的相关性[255]。在更细粒度的遗忘机制中，MemoryBank[207]应用了艾宾浩斯遗忘曲线来量化遗忘速率，考虑了时间衰减和间隔效应，即重新学习信息比第一次学习更容易的原则。相比之下，Lyfe Agent[254]采用了分层总结和遗忘策略：首先将相关记忆聚类，将其精炼为简洁的摘要，然后移除与较新记忆高度相似的旧记忆。这种方法实现了用于实时社交互动的高效、低成本的记忆更新。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.4  Memory Retrieval and Matching/section
记忆检索与匹配是智能代理利用记忆解决问题的关键过程。挑战在于异构记忆存储、上下文相关性、实时互动性和记忆更新。解决方案包括统一表示和索引、上下文感知语义匹配、任务导向决策和动态路由机制，以及强大的记忆管理。这些方法结合预训练语言模型、图神经网络和多层次索引结构，利用注意力机制实现上下文感知匹配，引入任务结构指导记忆利用，促进技能提炼和创新。最终，一个灵活、强大的记忆检索系统将使智能代理能够有效地利用知识，支持复杂决策和智能行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.4  Memory Retrieval and Matching/section/0/text
1. 记忆检索在智能代理中的关键作用是如何实现的？它如何帮助智能代理解决复杂问题和指导决策、规划和行动？    2. 在处理庞大而多样的记忆池时，智能体面临着怎样的挑战？如何利用统一表示和索引、上下文感知语义匹配等方法来提高记忆检索的效率和准确性？    3. 论文提到的强大记忆管理系统如何结合预训练语言模型、图神经网络和多层次索引结构，以及利用注意力机制实现上下文感知匹配？这些技术如何促进智能代理的技能提炼和创新？
记忆检索是一种模拟人类回忆相关知识和经验以解决问题的过程。其目标是从庞大而多样的记忆池中高效准确地提取最相关的记忆片段，包括感官、短期和长期记忆，以指导智能体的决策、规划和行动。正如人类依赖过去的经验来应对复杂情况一样，智能体需要一个复杂的记忆检索机制来有效处理各种任务。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.4  Memory Retrieval and Matching/section/1/text
1. 如何解决智能体记忆存储异构性所带来的统一检索挑战？   2. 为什么简单的关键词匹配无法满足智能体与当前上下文高度相关的记忆检索需求？   3. 在智能体记忆持续更新的情况下，如何确保记忆的及时性、可靠性和相关性，同时避免过时或错误信息的干扰？
然而，要实现这一目标存在几个重大挑战。首先，智能体的记忆存储库通常是异构的，包括各种形式的记忆，如自然语言描述、结构化知识图谱和状态-行动-奖励序列。这些记忆在其数据结构、表示和语义粒度水平上有根本的差异，对统一检索构成了挑战。其次，检索到的记忆片段必须与当前上下文高度相关，包括智能体的状态、任务目标和环境观察。简单的关键词匹配无法捕捉到需要进行有意义检索所需的更深层语义关系。因此，开发一个能够根据当前情况动态调整检索策略的上下文感知语义匹配机制至关重要。第三，智能体与环境的实时互动性要求高效的记忆检索，以支持快速的决策和行动。这种效率需求进一步受到智能体计算资源限制的影响。最后，智能体的记忆不是静态的，而是随着新的经验、知识和技能的习得而不断发展。确保记忆的及时性、可靠性和相关性，同时避免过时或错误信息的干扰，是一个持续不断的挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.4  Memory Retrieval and Matching/section/2/text
1. 如何通过统一的记忆表示和索引方案来解决不同记忆类型之间的表征差距，并举例说明预训练的语言模型和图神经网络在此过程中的作用？  2. 为什么在构建一个全面的方法以解决记忆检索中的挑战时，多层次的混合索引结构是必不可可缺少的组成部分？请说明该结构如何支持多样化的查询需求。  3. 在记忆检索系统中，如何利用混合索引结构中的不同技术（如倒排索引、向量索引和图索引）来实现高效的检索和结构化查询？
一个全面的方法可以解决这些挑战，包括四个关键组成部分。首先，基础步骤涉及构建统一的记忆表示和索引方案。这旨在通过将它们嵌入到一个共同的向量空间中来弥合不同记忆类型之间的表征差距。预训练的语言模型如BERT或Sentence-BERT可以被利用来将基于文本的记忆转换为语义向量，而图神经网络（GNNs）可以学习结构化记忆（如知识图谱）的向量表示，捕捉节点和边关系。为了促进高效检索，一个多层次的混合索引结构是必不可少的。这结合了倒排索引等技术用于关键词匹配，Faiss或Annoy等向量索引用于相似度搜索，以及用于结构化查询的图索引，从而支持多样化的查询需求。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.4  Memory Retrieval and Matching/section/3/text
1. 如何实现系统具有上下文感知的语义相似度计算，以实现更深层次的语义匹配？  2. 在记忆检索过程中，为什么将上下文信息编码为向量表示，并与记忆向量有效融合是至关重要的？  3. 注意力机制在系统中扮演着怎样的角色，如何动态计算上下文与记忆向量之间的相关性，并为记忆片段分配权重？
其次，也许最为关键的是，系统必须发展具有上下文感知的语义相似度计算。这使得检索过程能够理解并利用当前上下文，比如代理的状态、目标和观察，实现超越关键词重叠的更深层语义匹配。这涉及将上下文信息编码为向量表示，并有效地将其与记忆向量融合。注意力机制在这里起着至关重要的作用，动态计算上下文与记忆向量之间的相关性，并根据其上下文相关性为记忆片段分配不同的权重。这强调了与当前情况更相关的记忆。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.4  Memory Retrieval and Matching/section/4/text
1. 如何通过任务结构信息来指导记忆的检索和利用，以实现复杂任务的分解、规划和动态调整？ 2. 在代理执行任务的过程中，为什么每个子任务的目标被视为记忆检索的上下文，以及如何提取相关的知识和经验？ 3. 为什么代理在执行过程中需要动态调整执行计划，并且在每个决策点重新检索记忆，以选择最佳行动并处理意外情况？
第三，将记忆检索与代理任务执行相结合需要一种面向任务的序列决策和动态路由机制。这利用任务的结构信息来指导记忆的检索和利用，实现复杂任务的分解、规划和动态调整。通过构建任务依赖图，代理可以对子任务进行拓扑排序以确定执行顺序。在执行过程中，每个子任务的目标作为记忆检索的上下文，提取相关的知识和经验。此外，代理必须根据环境反馈和任务进展动态调整执行计划。每个决策点都涉及基于当前状态和目标重新检索记忆，以选择最佳行动并处理意外情况。这方面还强调了代理如何利用其技能记忆解决问题，包括技能提炼、组合和创新。模式识别允许总结一般的问题解决步骤，而结构化知识组织将技能整理成可检索的格式。代理可以进一步从具体技能中提炼出通用技能，组合多种技能以解决复杂挑战，甚至创新新的技能组合。这些过程基本上依赖于一个高效的记忆检索系统，该系统能够根据任务需求识别合适的技能或技能组合。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.4  Memory Retrieval and Matching/section/5/text
1. 一个强大的记忆管理机制如何影响智能代理的记忆池的及时性、相关性和效率？ 2. 在记忆管理机制中，遗忘和更新策略如何模拟人类遗忘机制，以保证记忆的有效利用？ 3. 如何通过定期清除过时、冗余或很少使用的记忆以及基于时间和频率衰减的策略，实现动态记忆更新和提高与当前任务相关的记忆片段的重要性？
最后，一个强大的记忆管理机制对于维护记忆池的及时性、相关性和效率至关重要。这种机制应该包括遗忘和更新策略，模拟人类遗忘机制。这可能涉及定期清除过时、冗余或很少使用的记忆，基于时间衰减（随时间减弱记忆强度）和基于频率衰减（清除低频率记忆）。同时，当检索到与当前任务相关的记忆片段时，更新其时间戳和访问频率，提高其重要性并确保动态记忆更新。通过这些协调努力，LLM代理可以配备一个强大、灵活和上下文感知的记忆检索和匹配系统，使它们能够有效利用积累的知识，支持复杂决策，并展现更智能的行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.5 Neural Memory Networks/section
神经记忆网络代表了人工智能研究的前沿，旨在将记忆融入神经网络结构中。挑战之一是在记忆容量和稳定性之间取得平衡，确保网络能够存储大量信息且不会遗忘或混淆。有效的记忆读写操作机制至关重要，使网络能够更新、检索信息并实现计算效率。关联记忆和参数整合是解决挑战的方法之一，如Hopfield网络和支持异相关召回的双向关联记忆。另一方面，参数集成直接将记忆编码到网络权重中，将世界知识融入智能代理操作行为。未来研究将专注于创建更大容量、更稳定的神经记忆模型，并发展更高效、灵活的记忆读写机制，推动人工智能实现更复杂认知任务，逼近人类认知水平。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.5 Neural Memory Networks/section/0/text
1. 在神经记忆网络中将记忆直接整合到网络权重或激活中编码的方法相较于传统记忆架构有何优势和局限性？ 2. 如何确保神经记忆网络在存储大量信息时既不会遗忘或混淆，又能实现高效的信息更新和检索？ 3. 未来研究如何在神经记忆模型中进一步提升记忆容量和稳定性，以推动人工智能实现更复杂的认知任务？
神经记忆网络代表了人工智能研究中的一个迷人前沿。它们旨在将记忆无缝地整合到神经网络的结构中。这种方法与传统的记忆架构不同，它通过直接在网络的权重或激活中编码记忆，将网络转变为一个动态的、可读写的内存存储介质。这种紧密的整合承诺在效率和利用存储信息方面取得重大进展。然而，实现这一愿景面临着一些巨大的挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.5 Neural Memory Networks/section/1/text
1. 如何在神经网络中实现记忆容量和稳定性之间的平衡，以应对存储大量信息和避免遗忘或混淆的挑战？    2. 在神经网络中，如何设计有效的记忆读写操作机制，以确保网络能够写入新信息、更新现有记忆、准确检索信息，并保持计算效率？    3. 神经网络如何实现从存储的信息中泛化和推理的能力，以执行高阶认知功能，超越简单的机械记忆？
一个主要关注点是在记忆容量和稳定性之间取得平衡。在神经网络的有限参数内编码大量信息，同时保持长期稳定性，构成了一个重大障碍。网络必须能够存储大量记忆，而不会陷入灾难性遗忘或在相似记忆之间混淆。同样关键的是，需要开发有效的记忆读写操作机制。网络需要可靠地写入新信息，更新现有记忆，并在需要时准确检索存储的信息，同时保持计算效率。超越简单地存储记忆，最终目标是赋予神经网络从存储的信息中泛化和推理的能力。这将使它们能够执行高阶认知功能，超越机械记忆，基于过去经验进行有洞察力的连接和推断。目前正在探索几种方法来解决这些挑战，尤其是通过关联记忆和参数整合。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.5 Neural Memory Networks/section/2/text
1. 关联记忆模型如Hopfield网络和双向关联记忆(BAMs)是如何利用能量函数实现模式编码和检索的？   2. 外部记忆模块在神经图灵机(NTMs)和记忆增强型神经网络(MANNs)中是如何被应用以增强神经网络的记忆功能？   3. 在神经记忆网络中，如何通过注意力和总结机制实现神经网络与外部记忆模块的交互，以提升网络的记忆读写效率？
一方面，受到大脑中神经元相互连接的启发，关联记忆提供了一个有前途的途径。像Hopfield网络和支持异相关召回的双向关联记忆(BAMs)等模型，利用能量函数，提供了基于神经元之间权重的模式编码和检索机制。此外，神经图灵机(NTMs)和记忆增强型神经网络(MANNs)通过外部记忆模块增强神经网络，利用注意力和总结机制与这些记忆进行交互。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.5 Neural Memory Networks/section/3/text
1. 参数集成将记忆编码到网络权重中的优劣势是什么，以及如何影响智能AI代理的操作行为？  2. 在神经记忆网络中，如何通过修改模型参数来实现持续学习或遗忘特定知识？这种方法相比其他记忆模块的纳入方式有何优势？  3. MemoRAG和${\tt R}^{3}$ Mem如何统一记忆存储和检索的双重过程，以及这种统一对于支持终身AI应用有何重要意义？
另一方面，参数集成代表了另一个重要的研究方向，旨在直接将记忆编码到网络的权重中。这有助于将世界知识和积累的经验融入智能AI代理的操作行为中。例如，一些先前的工作修改模型参数以实现通过更新[325,326,327]或遗忘特定知识[328]来实现持续学习。其他研究将LLMs视为独立的记忆模块，在预训练[329]、后训练[330]和在线部署[331]期间将世界知识纳入其参数中。例如，MemoryLLM[265]引入了记忆令牌，而SELF-PARAM[266]利用知识蒸馏将世界知识和过去的AI代理经验嵌入模型参数中。这种方法在$\mathbf{M}+$模型[332]中进一步增强了长期记忆机制和协同训练的检索器，提高了其对更长历史记忆的泛化能力。此外，[33]利用编码记忆来促进进一步推理，从而提高存储知识的泛化能力。最近，MemoRAG[267]和${\tt R}^{3}$ Mem [270]被提出，不仅编码记忆，还能够从神经记忆网络中可靠检索，将记忆存储和检索的双重过程统一到一个模型中。这一进展有助于开发支持终身AI应用的下一代基于生成的检索系统。此外，Titans[269]通过元学习引入了记忆测试数据点的能力，从而实现更高效的测试时跨任务泛化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.5 Neural Memory Networks/section/4/text
1. 如何在神经记忆网络中平衡记忆容量和稳定性，以确保网络能够存储大量信息而不会遗忘或混淆？ 2. 未来研究如何发展更高效、更灵活的记忆读写机制，以推动人工智能实现更复杂的认知任务并逼近人类认知水平？ 3. 在将记忆增强网络应用于复杂认知任务的过程中，可能面临哪些挑战和限制？
未来的研究将继续专注于创建更大容量和更稳定的神经记忆模型。因此，开发更高效、更灵活的记忆读写机制将至关重要。一个关键的研究领域将涉及将这些记忆增强网络应用于复杂的认知任务，推动人工智能能够实现的边界。在这一领域的进展将为构建能够学习、记忆和推理的智能代理打开新的可能性，这种方式越来越类似于人类认知。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.6 Memory Utilization/section
内存利用率是智能代理设计中的关键方面，旨在最大化存储记忆段的价值以增强代理的性能和效率。挑战包括平衡存储量与有效利用、抽象化需求、幻觉和错误记忆。检索增强生成(RAG)结合了检索和生成模型，利用外部知识源增强代理能力，通过整合检索到的信息提高输出真实性。长上下文建模通过Transformer变体和压缩技术扩展代理记忆窗口，促进长上下文理解。减少虚构策略通过事实核查、不确定性估计和基于知识的解码策略，确保生成内容可靠性。专家记忆子网络进一步优化记忆存储，使代理更有能力、准确和可靠，实现在复杂任务中的卓越性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.6 Memory Utilization/section/0/text
1. 如何平衡记忆存储量与有效利用，以应对智能代理设计中的信息过载挑战？ 2. 在智能代理设计中，如何解决抽象化和泛化需求，将特定记忆段转化为通用知识并应用于不同情境？ 3. 在处理幻觉和错误记忆问题时，智能代理如何确保生成内容的准确性和可靠性，以提升性能和效率？
智能代理设计的一个关键方面在于记忆利用，重点是最大化当前任务的存储记忆段的价值。其核心目标是有效和适当地应用这些记忆，以增强推理、决策、规划和行动生成，最终提升代理的性能和效率，同时避免无关或错误记忆干扰的问题。然而，实现这一目标面临着几个挑战。

一个主要挑战是平衡庞大的记忆存储量与其有效利用。代理必须应对潜在的信息过载，确保充分利用相关记忆，而不会使系统不堪重负。另一个障碍是抽象化和泛化的需求。代理需要将特定记忆段提炼为更一般的知识，并将这些知识应用于新的和多样化的情境。此外，LLM中幻觉和错误记忆的问题需要认真考虑。防止生成与存储信息相矛盾或歪曲的内容至关重要，同样重要的是能够识别和纠正存储库中可能存在的错误信息。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.6 Memory Utilization/section/1/text
1. RAG如何结合检索和生成模型，以提高代理的性能和效率？  2. 在RAG中，如何通过整合检索到的信息来增强生成内容的真实性？  3. 如何通过结合记忆模块与RAG来提高生成的可靠性和效率？
为了解决这些挑战，采用了几种策略。检索增强生成（RAG）[334]结合了检索和生成模型，通过利用外部知识源增强LLM的能力。与记忆检索和匹配中提到的方法不同，RAG专注于将检索到的信息整合到生成过程中。当受提示时，代理检索相关的记忆段，并将它们融入到生成模型提供的上下文中。这种上下文丰富可以引导模型产生更加真实和信息丰富的输出。例如，在回答用户查询时，代理可以首先从其知识库中检索相关条目，然后基于这些检索到的信息生成答案，从而将回应基于已建立的知识。最近，一些研究将记忆模块与RAG相结合，整合了自我反思[274]和自适应检索机制[272]，以提高生成的可靠性和效率。例如，Atlas [273]利用因果中介分析，而[284]采用基于一致性的幻觉检测来确定模型是否已具备必要知识——允许直接生成——或者是否需要检索，在这种情况下，模型首先检索相关信息然后生成响应。在一个统一的框架中，RAGLAB[271]提供了一个全面的生态系统，用于评估和分析主流的RAG算法。HippoRAG [22]采用了受人类记忆海马体索引理论启发的策略，为记忆创建了基于知识图的索引，并使用个性化PageRank进行记忆检索。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.6 Memory Utilization/section/2/text
1. 长上下文建模如何在智能代理设计中发挥关键作用，特别是在管理大规模记忆存储方面的重要性是如何体现的？  2. 采用Transformer模型变体和压缩技术扩展代理的记忆窗口，对于代理处理更广泛的记忆存储和在更广泛背景下进行推理和决策有何影响？  3. 如何利用记忆压缩技术，例如AutoCompressor和上下文自编码器(ICAE)，来实现更有效的长上下文建模，从而提高代理的性能和效率？
此外，长上下文建模在管理大规模记忆存储中发挥着至关重要的作用。这种方法增强了LLM处理长序列和大规模记忆的能力，使其能够更深入地理解和利用长距离依赖关系。通过采用Transformer模型变体，如Transformer-XL和Longformer，或通过分层和递归处理技术，如循环记忆变换器(RMT)，代理可以扩展其上下文窗口。这使它们能够处理更广泛的记忆存储，并在更广泛的背景下进行推理和决策。例如，当处理大量文档或进行长时间对话时，代理可以保持更长的记忆跨度。此外，一些研究利用记忆来压缩长上下文，实现更有效的长上下文建模。例如，AutoCompressor将摘要向量引入记忆，将信息从先前的上下文窗口传输到当前窗口，促进长上下文理解。类似地，上下文自编码器(ICAE)生成准确全面地表示原始上下文的记忆槽，而LLMLingua、Gist和CompAct进一步优化长提示压缩，以减少输入上下文长度。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.4 The Memory Lifecycle/3.4.6 Memory Utilization/section/3/text
1. 如何通过事实核查机制确保减少虚构策略生成的内容可靠性，以及这种机制如何与已建立的知识库相互作用？  2. 在减少虚构策略中，不确定性估计是如何评估生成内容的置信水平的，以及如何处理置信度较低的输出？  3. 专家记忆子网络如何帮助优化代理的记忆存储，从而减少主模型产生虚构内容的倾向？
最后，减少虚构策略对于确保生成输出的可靠性至关重要。这些策略旨在最小化LLM产生事实错误或荒谬内容的倾向。一种方法是实施事实核查机制，根据已建立的知识或记忆存储验证生成的内容。另一种方法涉及不确定性估计，模型评估生成内容的置信水平，并标记或过滤出置信度较低的输出。此外，在生成阶段可以采用基于知识的解码策略，引入约束来引导模型生成更准确的内容。这些技术共同有助于生成更值得信赖且与代理已建立的知识库保持一致的输出。最近的研究引入了专家记忆子网络，例如PEER和Lamini Memory Tuning，专门用于记忆特定类型的信息，包括世界知识和AI代理的过去经验。这些子网络将记忆工作转移到专用参数，减少主模型产生虚构的倾向。通过实施这些记忆利用策略，代理可以变得更有能力、准确和可靠。它们可以成功利用其记忆存储在复杂任务中实现卓越性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.5 Summary and Discussion/section
智能代理的发展需要综合考虑记忆系统与感知、规划、推理和行动选择等认知功能的紧密整合。记忆不仅是独立模块，还与其他认知过程相互作用，如感知、规划和行动选择。代理的核心在于建立和利用内部世界模型，这些模型对于高层认知和规划至关重要。然而，有效的世界模型和记忆系统面临挑战，包括管理复杂环境、确定适当抽象层次、整合多模态信息和有效学习更新模型等。未来研究应重点关注借鉴人类记忆的灵活性和联想能力，以增强智能体的记忆系统。有前途的研究方向包括受生物启发的机制、积极策展记忆内容和创建更健壮的情景记忆形式，以实现更智能、更有意义的互动。深度学习、强化学习和认知科学的交叉将为开发更复杂、更适应的世界模型和记忆系统提供创新解决方案。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.5 Summary and Discussion/section/0/text
1. 智能代理中的记忆系统如何与感知、规划、推理和行动选择等认知功能进行无缝整合，以实现更高层次的智能行为？    2. 在智能代理的发展中，为什么强调记忆系统不是孤立的模块，而是与感知、规划和行动选择等其他认知过程密切相关？这种相互作用如何影响代理的行为表现和决策过程？  3. 未来研究如何借鉴人类记忆的灵活性和联想能力，以增强智能体的记忆系统，进而实现更智能、更有意义的互动？
真正智能代理的发展不仅仅取决于强大的记忆系统，还取决于它们与感知、规划、推理和行动选择等其他认知功能的无缝整合。记忆不是一个孤立的模块；它与这些其他过程密切相关。例如，感官输入在存储之前被编码和过滤（如在有关记忆表示和生命周期的部分中所讨论的），突显了感知和记忆之间的相互作用。长期记忆，特别是程序性记忆，通过学习的技能和例行程序直接影响行动选择。检索机制，如上下文感知的语义相似度计算，对规划至关重要，使代理能够访问相关的过去经验。这种相互作用延伸到“世界模型”的概念中。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.5 Summary and Discussion/section/1/text
1. 世界模型在智能代理中的作用是怎样影响高层认知、规划和类人智能的发展？ 2. 在智能代理的记忆系统中，如何实现有效的新记忆编码、巩固和检索，以促进世界模型的建立和利用？ 3. 如何借鉴人类记忆的灵活性和联想能力，以增强智能体的记忆系统，并进一步提升智能代理的功能和性能？
智能代理的核心是它们建立和利用内部世界模型的能力。这些模型代表了代理对环境的理解，可以进行模拟、推理和预测。健壮的世界模型对于高层认知、规划和类人智能至关重要。世界模型本质上是一种高度结构化的、通常是预测性的长期记忆形式。记忆为构建世界模型提供了原始材料——知识和经验，而世界模型反过来作为一个组织框架，影响新记忆的编码、巩固和检索。例如，一个完善的世界模型可能会优先存储令人惊讶的事件，因为这些事件表明代理的理解存在空白。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.5 Summary and Discussion/section/2/text
1. 如何克服发展有效世界模型和记忆系统所面临的挑战，包括管理复杂环境、确定抽象层次、整合多模态信息以及高效学习和更新模型？   2. 在建立基于模型的规划时，如何有效处理模型预测中的不确定性，并采用高效的搜索算法来应对这种挑战？  3. 未来研究如何借鉴人类记忆的灵活性和联想能力，以加强智能体的记忆系统，特别是通过受生物启发的机制、积极策展记忆内容和创建更健壮的情景记忆形式等途径？
然而，发展有效的世界模型和记忆系统面临着重大挑战。这些挑战包括管理现实世界环境的复杂性，确定适当的抽象层次（平衡准确性、复杂性和计算效率），以及整合多模态信息。高效地学习和更新这些模型，避免偏见，确保泛化，并实现持续适应也至关重要。此外，基于模型的规划需要高效的搜索算法来处理模型预测中固有的不确定性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.5 Summary and Discussion/section/3/text
1. 如何借鉴人类记忆的灵活性和联想能力来增强智能体的记忆系统？这种借鉴对于解决智能体记忆系统面临的挑战有何重要意义？  2. 人类记忆与智能体记忆系统在处理信息时的差异主要体现在哪些方面？如何通过研究人类记忆的优势来弥补智能体记忆系统的不足之处？  3. 在未来研究中，如何结合深度学习、强化学习和认知科学的交叉，以创新解决方案来发展更复杂、更适应的世界模型和记忆系统？
未来的研究应重点关注通过借鉴人类记忆的优势，特别是其灵活性、适应性和效率，来增强智能体记忆系统。虽然智能体的记忆系统已经取得了相当大的进展，但在这些关键领域仍远远落后于人类记忆。人类记忆具有非凡的联想能力，可以从不完整或嘈杂的线索中检索信息，并展现出一种复杂的“遗忘”形式，包括信息的巩固和抽象化，优先考虑相关信息并从经验中概括。相反，智能体的记忆系统通常依赖于精确匹配，并且在处理模糊性时存在困难。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.5 Summary and Discussion/section/4/text
1. 如何可以借鉴人类记忆的灵活性和联想能力，来增强智能体的记忆系统，特别是在开发能够积极“策展”记忆内容并整合新知识的系统方面有哪些关键挑战？  2. 在开发更加健壮和细致的情景记忆形式方面，如何可以有效地捕捉事件的“什么”、“何时”、“为什么”以及情感背景，以实现智能体真正从经验中学习并自然与人类互动？  3. 在整合元认知能力到智能体架构中的过程中，有哪些关键技术或方法可以帮助智能体反思信息、识别不一致之处，并综合新知识，从而提升智能体的认知能力？
出现了几个有前途的研究方向。探索受生物启发的机制，比如神经记忆网络（如前所讨论的），可能会带来重大突破。另一个至关重要的领域是开发能够积极“策展”其内容的记忆系统——反思信息，识别不一致之处并综合新知识。这需要将元认知能力（监控和控制自身认知过程）整合到智能体架构中。此外，创建更加健壮和细致的情景记忆形式，捕捉事件的“什么”、“何时”以及“为什么”和情感背景，对于能够真正从经验中学习并自然与人类互动的智能体是至关重要的。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/3.5 Summary and Discussion/section/5/text
1. 如何能够有效地将深度学习、强化学习和认知科学结合，提出创新解决方案来开发更复杂、更适应的世界模型和记忆系统，以反映人类认知的优势？  2. 在开发更智能、更有意义的互动中，如何利用受生物启发的机制、积极策展记忆内容和创建更健壮的情景记忆形式来增强智能体的记忆系统？  3. 为了拥有更深入了解环境的智能体，如何解决管理复杂环境、确定适当抽象层次、整合多模态信息和有效学习更新模型等挑战？
要克服这些挑战，需要在深度学习、强化学习和认知科学交叉领域提出创新解决方案。开发更复杂、更适应的世界模型和记忆系统——这些系统应当反映人类认知的优势，将为拥有更深入了解环境的智能体铺平道路，从而实现更智能、更有意义的互动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/World Model/section
在人工智能领域，世界模型是使代理能够预测和推理未来状态的关键。本节将人类认知研究中的“心理模型”与世界模型联系起来，分类为隐式、显式、基于模拟器和其他新兴方法。我们讨论了世界模型如何与其他代理组件相互作用，并提出了统一的理论框架，探讨了未来研究的开放问题和方向。通过这种方式，我们为构建更智能、自适应的人工智能系统提供了重要的理论基础和实践指导。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/World Model/section/0/text
1. 世界模型在人工智能中的四种范式（隐式、显式、基于模拟器、其他新兴方法）各自的优缺点是什么，如何影响代理的预测和推理能力？  2. 人类认知研究中的“心理模型”如何与世界模型相关联？这种联系对于构建智能、自适应的人工智能系统有何重要意义？  3. 在统一的理论框架下，世界模型与其他代理组件如何相互作用？这种相互作用如何影响人工智能系统的发展和应用？
世界模型使代理能够在没有直接现实试错的情况下预测和推理未来状态。本节探讨了人类认知研究中关于“心理模型”的内容如何与人工智能中的世界模型相关联，将其归类为四种范式：隐式范式、显式范式、基于模拟器的范式以及一类其他新兴方法（例如，基于指导的范式）。然后，我们讨论了世界模型如何与其他代理组件固有地交汇，并最终得出了统一的理论和实践框架下将这些观点联系起来的开放问题和未来方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/World Model/section/1/figure
1. 在人工智能领域中，如何将人类认知研究中的“心理模型”与世界模型联系起来，以帮助代理预测和推理未来状态？     2. 在构建更智能、自适应的人工智能系统时，世界模型如何与其他代理组件相互作用，有哪些开放问题和研究方向？
图4.1：人类可以利用大脑对世界的模型来预测其行为的后果。例如，在打乒乓球时，球员可以想象或预测动作后球的轨迹。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Reward/section
奖励在智能代理中扮演着至关重要的角色，帮助代理区分有益和有害的行为，引导其学习和决策过程。本章首先介绍了人体中常见的奖励物质及相应的奖励途径，然后定义了代理环境下的奖励范式和相关方法。讨论中探讨了不同模块之间的相互影响，总结了现有方法，并指出了未来需要解决的问题和优化方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Reward/section/0/figure
1. 根据图5.1中的示意分类，不同类型的奖励系统在智能代理中有何作用和应用场景？ 2. 图5.1中展示了不同类型的奖励系统，这些奖励系统之间是否存在交叉影响或相互补充的关系？
图5.1：奖励系统的示意分类

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Reward/section/1/text
1. 奖励如何帮助智能代理区分有益和有害的行为，并对其学习和决策过程产生怎样的影响？ 2. 人体中常见的奖励物质以及相应的奖励途径对智能代理的奖励系统有何启示和借鉴意义？ 3. 在代理环境下，不同的奖励范式和方法是如何影响代理行为和学习过程的？未来在这方面需要解决的问题和优化方向有哪些？
奖励有助于代理区分有益和有害的行为，塑造其学习过程并影响其决策。本章首先介绍了人体中常见的奖励物质以及相应的奖励途径。然后，定义了代理下的奖励范式和涉及的不同方法。在讨论部分，描述了其他模块之间的影响关系，并总结了现有方法，然后讨论了未来需要解决的问题和优化方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Reward/section/2/table
1. 人类常见奖励路径的比较表中哪种奖励物质在代理环境下更容易实现奖励效果？ 2. 在人类常见奖励路径的比较表中，哪种奖励途径对于智能代理的学习和决策过程具有更大的指导意义？
表5.1：人类常见奖励路径的比较

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Emotion Modeling/section
情感在LLM代理中扮演着重要角色，有助于提升系统智能、适应性和对周围世界的理解。情感可被视为决策工具，帮助代理处理任务优先级、理解风险和适应新挑战。然而，将情感整合到LLM代理仍处于初级阶段，研究人员正在探索如何利用情感改善系统性能。这一领域有望通过支持情感福祉，促进人机互动的深化，并为心理健康支持和用户联系提供新途径。未来合作跨学科领域的努力将推动情感理解的LLM代理发展，重新定义人类与技术之间的互动，促进更深层次的信任和有意义的关系。接下来的讨论将深入探讨情感如何增强学习和适应能力，LLM如何理解人类情感，以及如何处理情感操纵对行为和个性的影响，同时关注伦理和安全问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Emotion Modeling/section/0/text
1. 情感如何在LLM代理中被视为决策工具，帮助代理处理任务优先级、理解风险和适应新挑战，从而提升系统性能？ 2. 在将情感整合到LLM代理的过程中，研究人员面临哪些挑战和障碍？他们如何探索情感能力如何改善系统，并支持人类的情感福祉？ 3. 未来跨学科合作如何推动情感理解的LLM代理发展，重新定义人类与技术之间的互动，促进更深层次的信任和有意义的关系？
情感是人类思考、做出决策和与他人互动的关键部分。它们指导我们理解情况、做出选择和建立关系。安东尼奥·达马西奥在他的著作《笛卡尔的错误》中解释说，情感并非与逻辑分离，而是与我们推理和行动的方式深深相连。在开发LLM代理时，增加情感能力可能使这些系统变得更智能、更适应，并更好地理解周围的世界。

对于LLM代理，情感可以作为决策工具，就像它们对人类一样。情感帮助我们优先处理任务、理解风险并适应新挑战。马文·明斯基在《情感机器》中描述情感是调整我们思维过程的一种方式，帮助我们以更灵活和创造性的方式解决问题。类似地，具有类似情感特征的LLM代理可以提高它们解决复杂问题和做出决策的能力，更贴近人类风格。

然而，将情感整合到LLM代理中仍处于早期阶段。研究人员刚刚开始探索情感能力如何改善这些系统。此外，LLM代理有巨大潜力支持人类的情感福祉，无论是通过共情对话、心理健康支持，还是简单地与用户建立更好的联系。这一充满希望但具有挑战性的领域需要心理学、认知科学和人工智能伦理等领域之间的合作。随着研究的进展，理解情感的LLM代理可能重新定义我们与技术的互动方式，为人类与机器之间建立更深层的信任和更有意义的关系。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Emotion Modeling/section/1/text
1. 情感如何被应用来增强LLM代理的学习和适应能力？这种整合情感的方法对系统性能有何影响？  2. LLM代理如何理解人类情感，并如何表达和建模自身的情感状态？这种情感理解对于提升代理与人类互动的效果有何意义？  3. 如何通过操纵情感来影响LLM代理的行为和个性？在这一过程中可能出现的伦理和安全问题有哪些，以及如何应对这些挑战？
在接下来的小节中，我们将更深入地探讨情感在塑造LLM代理中的作用。我们将探讨情感如何被用来增强学习和适应能力，LLM如何理解人类情感，以及这些系统如何表达和建模它们自己的情感状态。我们还将研究如何通过操纵情感来影响LLM代理的行为和个性，以及由此产生的伦理和安全问题。这些讨论都基于情感对于创造更智能、有同理心且符合人类价值观的LLM代理的基础重要性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Perception/section
感知是人类和智能代理获取信息、解释环境并做出决策的基础。本章探讨了人类和代理感知的差异，代理感知的分类表示，以及感知系统面临的挑战。我们深入讨论了改进代理感知系统的方向，并指出了定制感知模块以优化智能代理场景的方法。这一研究为未来关注的关键领域提供了指导，强调了感知在代理互动、学习和适应能力中的重要性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Perception/section/0/text
1. 人类感知与智能代理感知的差异在哪些方面体现？这种差异对智能代理在复杂环境中的互动、学习和适应能力有何影响？  2. 代理感知系统面临哪些挑战？如何通过改进代理感知系统来应对这些挑战，以优化智能代理在不同场景中的表现？  3. 为什么定制感知模块可以被视为优化智能代理场景的方法？定制感知模块如何帮助智能代理更好地适应和学习环境，从而提升其整体性能？
感知是人类和智能代理获取信息、解释周围环境并最终做出明智决策的基础门户。对于人类来说，感知是无缝和直观的，毫不费力地将感官输入转化为有意义的解释。然而，在人工智能领域，感知系统经过精心设计，旨在模拟并在某些方面超越人类的感知处理，深刻影响代理在复杂环境中的互动、学习和适应能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Perception/section/1/text
1. 人类和人工智能代理在感知性质和效率方面的关键差异是什么，这些差异如何影响他们的决策能力？ 2. 代理感知系统面临哪些挑战，建模和系统架构方面的改进有哪些有希望的方向可以解决这些挑战？ 3. 如何定制感知模块以优化不同智能代理场景的使用，这种定制化对智能代理的发展和应用有何意义？
在本章中，我们首先探讨人类和人工智能代理在感知性质和效率方面的关键差异。接下来，我们基于不同形式和感知输入的表示对代理感知进行分类。然后，我们讨论代理感知系统中持续存在的挑战，并突出在建模和系统架构层面改进的有希望方向。最后，我们阐明了感知模块如何有效地定制给不同智能代理场景，为优化它们的使用提供实用指导，并提出了未来研究的关键领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Action Systems/section
在人工智能领域中，行动系统是智能代理在环境中为实现特定目标而执行的关键行为。行动系统的设计决定了代理与外部世界互动的方式，使其能够执行复杂的用户意图并利用可用工具。与基础模型相比，配备行动系统的人工智能代理能够扩展任务范围并展现更广泛的能力。行动系统不仅支持代理在决策制定、执行和工具利用方面的表现，还决定了它们实现复杂目标的潜力。设计有效的行动系统对于提升代理性能至关重要，涉及重大挑战和潜在收益。本节将深入探讨人类行动系统，并审视人类行动如何转化为人工智能代理的行动。随后，系统地总结了现有行动系统的范式，包括行动空间、行动学习和工具学习。最后，分析了行动与感知之间的差异，为章节做出了全面总结。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Action Systems/section/0/text
1. 行动系统如何区分人工智能代理和基础模型，以及它们在提升代理性能和扩展任务范围方面的作用是怎样的？  2. 在人工智能代理中，基础模型和配备行动系统的代理分别扮演着怎样的角色，以及它们之间在实现复杂目标和利用外部工具方面有何不同？  3. 设计有效的行动系统对于人工智能代理的性能和潜力意味着什么，这一过程中可能面临的挑战和可能带来的收益是怎样的？
在哲学领域，行动被定义为代理人在环境中为潜在或特定目的而执行的行为。例如，操纵、移动、推理和工具利用都可以被视为智能代理在真实场景中执行以实现目标的基本行动。换句话说，行动源自代理在环境中以目标为导向的参与，反映其意图改变外部世界以追求目标。因此，行动系统在区分人工智能代理和基础模型（如LLMs）方面也起着至关重要的作用。通常，现有的基础模型在各种任务中表现出色，但它们的任务范围仍然有限，因为它们主要依赖于原始的预训练目标（例如，下一个标记的预测）。通过将基础模型作为大脑智能，配备有行动系统的人工智能代理可以直接与其环境互动，并执行复杂的用户意图。此外，行动系统可以支持代理利用外部环境中的可用工具，从而显著扩展代理的任务范围。因此，行动系统的设计也将决定人工智能代理在知觉、决策制定、执行、工具利用以及与人类大脑一致的任何其他组件方面的能力。换句话说，基础模型奠定了代理的基础，而行动系统决定了它们实现复杂目标的最终潜力。为人工智能代理设计一套有效而全面的行动系统是一项至关重要的工作，涉及重大挑战和显著收益。在图8.1中，我们展示了认知系统中行动系统的执行过程。在本节中，我们将首先讨论8.1节中的人类行动系统，然后在8.2节中审视从人类行动到人工智能代理中的行动转变。之后，我们将在8.3节系统地总结人工智能代理中现有行动系统的范式，包括行动空间、行动学习和工具学习。在8.4节中分析行动与感知之间的差异，最后在8.5节总结结论。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Action Systems/section/1/figure
1. 图8.1中展示的若干概念如何有助于理解人工智能代理中的行动系统设计？ 2. 在人工智能代理中，动作执行在整个行动系统中扮演着怎样的角色？
图8.1：涉及动作和动作执行的若干概念的示意图。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.1 The Human Action System/section
人类行为系统是一个复杂的认知过程，包括心理行动和物理行动两个方面。心理行动涉及推动人脑中意图的思考过程，如推理、决策和规划，是驱动物理行动实现最终目标的脑信号。而物理行动则是身体执行的目标导向运动，如说话、操作、奔跑，通过这些行动个体与环境互动并获取反馈。这种区分有助于理解人类如何感知、规划和执行行动，以适应动态环境并做出决策调整。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.1 The Human Action System/section/0/text
1. 人类认知中的心理行动和物理行动在实现目标导向行为过程中各自扮演着怎样的角色？这种角色分工对于个体适应动态环境并做出决策调整有何重要意义？  2. 在人类认知中的行动系统中，心理行动和物理行动之间是如何相互作用和协调的？这种相互作用如何促进个体与环境的互动并获取反馈？  3. 在人类认知中的行动系统中，心理行动和物理行动的分类有助于我们理解人类如何感知、规划和执行行动。那么，这种分类对于研究个体决策过程和行为调整有哪些启示和应用意义？
人类认知中的行动系统指的是使人类能够感知、规划和执行目标导向行动的过程。这是一个复杂的系统，使个体能够与动态环境互动，做出决策，并根据反馈调整行为。一般来说，人类认知中的行动系统可以广泛分类为心理行动和物理行动：

- 心理行动可以被视为一种独特的行动，它被构想为推动人脑中最终意图的思考过程。例如，推理、决策、想象和规划都可以被视为各种类型的心理行动。换句话说，心理行动相当于驱动人类的物理行动以实现最终目标的一种脑信号。

- 物理行动指的是人类运动系统执行的任何目标导向的身体运动。在某种程度上，物理行动通常被表达为一种连续的行动。例如，说话、操作、绘画、奔跑和抓取都可以被视为物理行动。通过一系列的物理行动，人类可以进行互动并从现实世界环境中获取反馈。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.1 The Human Action System/section/1/table
1. 不同种类基础模型之间的定义如何有助于解释人类心理行动和物理行动之间的关系？ 2. 这些基础模型的区分对于研究人类行为系统中的认知过程有何意义？
表8.1：不同种类基础模型之间的定义。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.1 The Human Action System/section/2/figure
1. 在人类行为的分类示意图中，精神和身体两个方面的具体行为有何区别和联系？ 2. 人类行为系统中的心理行动和物理行动如何相互作用，从而实现个体与环境之间的互动和反馈？
图8.2: 人类行为的分类示意图，显示了精神和身体两个方面。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.2 From Human Action to Agentic Action/section
在人类行为和主体性行为之间建立映射对于构建AI代理框架至关重要。人类认知系统通过预定义行动空间解决任务，同时不断学习并扩展技能库，利用外部工具提升问题解决能力。在AI代理中，行动系统核心是与环境互动，并通过奖励函数学习，类似人类认知。因此，重要挑战包括构建复杂任务的行动空间、模拟学习能力以适应环境变化，并利用外部状态拓展任务范围。通过此调查，我们期望为社区提供更深入的见解，凸显行动系统在AI代理框架中的关键作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.2 From Human Action to Agentic Action/section/0/text
1. 人类行动系统如何激励我们塑造计算机系统朝向自主范式的发展？这种行动机制在智能的人类大脑中是如何推动目标导向行为的？    2. 在构建AI代理的过程中，为什么需要将人类大脑中产生的意识和无意识思维信号转化为心理信号，并最终导致一系列行动操作？这种映射如何帮助我们设计AI代理的原型？  3. 为什么构建行动空间、制定用于改进决策的学习机制以及整合外部状态（例如工具）是构建AI代理框架中的关键设计原则？这些设计如何受到人类行动系统的影响和启发？
在过去很长一段时间中，人类行动系统显著地激励我们塑造计算机系统朝向自主范式的发展。行动机制在人类大脑中发挥着关键作用，推动目标导向行为。在智能的人类大脑中，产生意识和无意识思维信号，这些信号被转化为心理信号，最终导致一系列行动操作。这一过程可以被映射为一个多阶段管道，涉及构建行动空间、制定用于改进决策的学习机制，并整合外部状态（例如工具）。受这些原则启发，我们发现这些设计对于构建AI代理的原型至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.2 From Human Action to Agentic Action/section/1/text
1. 不同基础模型（LLM、LMM、RFM、LAM）在AI代理框架中如何定义和运用行动系统，以及它们之间的区别是什么？  2. AI代理框架中的行动系统如何通过与环境的交互和奖励函数学习来模拟人类认知中的行动系统？这种模拟会如何影响AI代理的学习和适应能力？  3. 在构建AI代理框架时，如何利用不同基础模型（LLM、LMM、RFM、LAM）的特性来拓展任务范围、适应环境变化，并提升问题解决能力？
许多现有框架将行动学习纳入其设计中或将其用作输出。为了澄清行动系统的定义，我们强调了各种框架之间的区别，包括大型语言模型（LLM）、大型多模态模型（LMM）、机器人基础模型（RFM）和大型行动模型（LAM），如表8.1所示。具体而言，LLM是基于提供的提示生成语言输出，而LMM是基于多模态输入生成多模态工件。现有基于语言或数字AI代理框架是通过这些基础模型（例如LLM或LMM）构建的，通过预定义行动空间的范围及其学习策略。另一方面，RFM是为了基于现实环境（例如机器人视频）优化机器人控制。现有的RFM是从网络规模的视频数据进行预训练，并使用视频预测来模拟机器人控制的行动。尽管在构建物理AI代理中涉及了一些行动设计，但RFM的核心仍然是利用生成目标从大规模数据中学习知识。此外，一些最近的工作引入了大型行动模型（LAM）的概念，进一步强调生成行动策略的阶段，与现实环境进行交互，并增强自学习范式。从这些定义中，我们注意到，无论使用哪种基础模型，行动系统的核心是建立与环境的交互，然后通过预定义的奖励函数从收集的行动轨迹中启用学习过程。具体而言，这些行为背后的机制也类似于人类认知中的行动系统，为设计AI代理框架中的行动系统提供了宝贵的见解。例如：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.2 From Human Action to Agentic Action/section/2/text
1. 在构建AI代理框架时，如何预定义行动空间以解决复杂任务，并如何模拟人类在处理不同场景时的行动操作？ 2. 人类认知系统通过现实世界互动持续获取新知识，如何在AI代理中复制这种学习能力以适应动态环境并构建新的技能库？ 3. 人类如何利用外部工具扩展问题解决能力，以及如何在AI代理框架中借鉴这种方法来拓展任务范围？
·在处理不同场景时，人类通常会预定义行动空间，执行行动轨迹以解决特定任务。例如，当玩像Minecraft这样的电脑游戏时，我们会通过键盘或鼠标设置我们的行动操作，以模拟建造房屋、挖掘黄金等行为。基于此，我们还需要为处理AI代理框架中的复杂任务构建或创建一个行动空间。
·与机器相比，人类认知系统在通过现实世界互动持续获取新知识方面表现出色，通过生成和优化行动序列来指导。因此，在AI代理中复制这种学习能力对于适应动态环境并构建新的技能库至关重要。
·此外，随着人类文明的发展，学会使用外部工具已被公认为人类智能演化中最重要的里程碑之一。通过利用这些外部工具，人类可以极大地扩展在不同场景中的问题解决能力，从石器时代到工业革命。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.2 From Human Action to Agentic Action/section/3/text
1. 如何从特定场景到通用领域构建AI代理的行动空间，以实现更广泛的任务覆盖？ 2. 在构建AI代理的行动学习过程中，如何模拟人类认知系统中的学习能力，以适应环境的动态变化？ 3. AI代理如何利用外部状态，例如工具，来扩展任务范围，提高问题解决能力？
为此，我们期望构建人类认知系统的行动系统与AI代理框架设计之间的映射，包括如何从特定场景到通用领域构建AI代理的行动空间，如何在环境中构建行动学习，以及如何利用外部状态（例如工具）来扩展AI代理的任务范围。通过开展这项系统性调查，我们致力于为社区提供更深入的见解，清晰地理解行动系统在AI代理框架中的重要性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/section
本节深入探讨了人工智能代理的主体行动系统范式，包括行动空间、行动学习和工具支持。行动系统由行动空间 $\mathcal{A}$、状态 $s$、观测 $\mathcal{O}$ 和工具空间 $\tau$ 组成，塑造了代理的行动特征和执行过程。为了探索各种行动可能性，必须形式化表示行动空间并考虑层次推理过程。决策过程被形式化为轨迹 $\left\langle o_{t},s_{t},a_{t}\right\rangle$，引导代理朝向目标。子章节进一步介绍了行动空间、行动学习和工具支持的核心内容。行动空间范式涵盖了基于语言、代码编程、多代理通信等多种环境，提高了代理在复杂任务中的决策能力。行动学习范式通过上下文学习、监督训练和强化学习，使代理不断优化行动选择，展现出显著的决策能力。工具支持的行动范式关注工具在代理与外部世界互动中的关键作用，为代理解决复杂任务提供重要支持，促进智能系统的全面发展。通过这些范式的整合，人工智能代理得以在不同领域展现出多功能、自主和多模态的行动能力，推动人工智能技术的发展与社会利益的协调。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/section/0/text
1. 人工智能代理框架中的行动系统主体包括哪三个主要组成部分？这三个组成部分分别如何影响代理的行动特征和执行过程？  2. 在人工智能代理的行动学习过程中，状态 $s$、观测 $\mathcal{O}$ 和代理的优化是如何相互作用的？这种相互作用如何帮助代理在动态环境中进行有效的行动选择？  3. 工具空间 $\tau$ 在人工智能代理框架中的作用是什么？它包括哪些内容，如何帮助代理在执行任务时获得支持？
通常，人工智能代理框架的行动系统主要由三个组成部分组成：1）行动空间 $\mathcal{A}$，其中包括代理在真实场景或下游任务中可以执行的所有类型行动，根据不同的代理设置可以有很大变化，从基于语言的代理到具身体的代理不等；2）在动态环境中进行的行动学习，确定状态 $s$，观测 $\mathcal{O}$ 和代理的优化过程；3）工具空间 $\tau$，包括代理可以利用的工具、接口或中间件，范围从物理设备如机器臂到数字接口如APIs。总体而言，这些组件共同定义了人工智能代理的行动系统的范围和特征，塑造了它们的制定和执行。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/section/1/text
1. 人工智能代理如何通过形式化表示行动空间和考虑层次推理过程来充分探索实际场景中可能的行动？    2. 在人工智能代理的决策过程中，轨迹 $\left\langle o_{t},s_{t},a_{t}\right\rangle$ 的形式化表示如何帮助代理朝向实现最终目标？    3. 为什么在某些情况下整合外部工具系统对人工智能代理的决策过程可能是必要的？
为了充分探索实际场景中可能的行动 $a_{t}$，我们必须形式化表示行动空间，并考虑个体操作和潜在的层次推理过程。这意味着在不同层次上检查行动空间，从低级操作到编排复杂工作流程的高级运算符。

因此，人工智能代理的决策过程可以形式化为一个轨迹 $\left\langle o_{t},s_{t},a_{t}\right\rangle$，其中 $a_{t}$ 从行动空间 $\mathcal{A}$ 中选择，根据观测 $o_{t}$ 将当前状态 $s_{t}$ 转化为下一个状态。在某些情况下，整合外部工具系统也可能是必要的。通过执行一系列 $\left\langle o_{t},s_{t},a_{t}\right\rangle$，代理被引导朝向实现其最终目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.1  Action Space Paradigm/section
动作空间$\mathcal{A}$作为构建人工智能代理行动系统的核心组成部分，在不同场景中解决复杂任务起着关键作用。基于语言的代理通过语言驱动的行动在交互式语言环境中运行，包括纯文本、代码编程和通信。纯文本动作空间旨在口头环境或文本游戏中进行交互式决策，如ReAct和AutoGPT。代码编程动作空间允许直接执行生成的代码，如MetaGPT和SWE-Agent。多代理通信动作空间通过聊天分析下一步行动，如Generative Agents和AutoGen。数字化环境中的代理，如MineDojo和Voyager，展示了在数字环境中运行的先进代理，提高了解决复杂任务的能力。多模态任务处理代理，如MM-ReAct和Visual-ChatGPT，通过整合多个视觉专家解决任务。AI代理框架，如WebGPT和WebShop，与搜索引擎交互以提高信息获取能力。最终，扩展动作空间至网络浏览、GUI交互、移动应用和实体系统，使代理更自主、多模态和具有上下文意识，弥合了基础模型和人类认知系统之间的差距，推动通用AI系统向真实世界互动迈进。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.1  Action Space Paradigm/section/0/text
1. 基于语言的人工智能代理如何通过不同类型的动作空间（纯文本、代码编程、通信）在交互式语言环境中解决复杂任务？ 2. 在基于语言的人工智能代理中，纯文本动作空间和代码编程动作空间各自的优势和局限性是什么，如何影响代理在解决问题时的效率和准确性？ 3. 多代理通信动作空间如何通过聊天分析下一步行动，以促进软件工程的发展和解决复杂任务？
动作空间$\mathcal{A}$是一个重要组成部分，它作为在人工智能代理框架内构建行动系统的基础。动作空间的组成决定了人工智能代理如何在不同场景中解决复杂任务。在图8.2中，我们基于其动作空间呈现了行动系统的分类法。通常，我们总结了现有研究中的动作空间为三种不同类型，如下所述。

基于语言的人工智能代理通常通过语言驱动的行动在交互式语言环境中运行，例如推理、编程、检索信息、执行API调用或与外部工具交互。在我们的研究中，我们总结了三种不同类型的基于语言的动作空间，包括纯文本、代码编程和通信。具体来说，早期基于语言的人工智能代理是基于纯文本构建的，旨在在口头环境或基于文本的游戏中进行交互式决策。在这里，ReAct[70]是一个代表性的基于语言的人工智能代理，它通过协同作用LLM的推理和行动来解决各种问题。AutoGPT[625]分析并分解用户请求为多个子任务，并使用网络搜索或其他工具来处理每个子任务。Reflexion[48]涉及自我完善和记忆机制，以增强语言任务中的行动执行。$\mathbf{LLM+P}$[163]赋予基于LLM的代理规划能力，以帮助决策制定。然而，将纯文本转换为可执行命令通常需要LLM首先解释文本，然后执行指令转换，导致额外信息的丢失。为此，一些工作探索使用代码作为动作空间，允许直接执行生成的代码并进行自我验证。MetaGPT[626]和ChatDev[627]通过编程语言建立行动空间，实现多代理协作。SWE-Agent[628]考虑软件工程的不同阶段，从而解决软件问题。OpenDevin[629]设计了一个自动软件开发平台，整合了编写代码、与命令交互、用于代码执行的沙盒和协作。此外，一些框架是基于多代理通信构建的，然后使用聊天分析下一步应采取哪些行动。在这里，Generative Agents[50]直接模拟虚拟城镇中的多个角色，探索每个代理如何进行下一步行动。MetaGPT[626]和ChatDev[627]都是多代理框架，促进软件工程的发展。AutoGen[630]也是一个代表性框架，可以实现多代理协作来解决任何复杂任务。总的来说，基于语言的人工智能代理在语言交互中效果显著。然而，受限于动作空间的范围，也面临如何在现实场景中解决更复杂任务的挑战。因此，我们还需要制定新的研究解决方案，构建更复杂的动作空间来解决具有挑战性的任务。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.1  Action Space Paradigm/section/1/figure
1. 在动作空间的不同分类中，纯文本动作空间和代码编程动作空间有何区别？它们分别适用于哪些场景和任务？     2. 多代理通信动作空间和多模态任务处理代理如何提高代理系统在复杂任务中的性能？它们之间是否存在某种联系或相互补充的关系？
图8.3：行动系统的示意分类，包括行动空间和学习范式

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.1  Action Space Paradigm/section/2/text
1. 在数字化环境中运行的先进人工智能代理相比传统代理有哪些优势和特点，以及这些特点如何提高代理的任务解决能力？  2. MineDojo、Voyager、JARVIS-1和SwarmBrain分别代表了怎样不同类型的先进人工智能代理？它们在数字环境中的具体任务和目标是如何设计和实现的？  3. 研究中提到的多模态任务处理代理和LLM的探讨，如何帮助人工智能代理更好地处理复杂任务和提高任务执行效率？
数字化为了拓展人工智能代理的能力，一些研究还开发了在数字环境中运行的先进人工智能代理，例如网络代理、在线购物平台和游戏系统。例如，MineDojo通过视频语言预训练设计了一个虚拟代理，并模拟支持Minecraft内多种任务和目标的环境。此外，Voyager是一个经过训练用于玩Minecraft的具有实体的人工智能代理。它通过与Minecraft环境互动，模拟多种可执行动作以开发技能库，从而提高虚拟代理的能力。JARVIS-1是一个处理多模态输入/输出、生成复杂计划并执行实体控制的开放世界代理。它在Minecraft中探索代理在行动时的进化行为。SwarmBrain是一个使用LLM在StarCraft II中进行战略和实时行动的实体代理。此外，一些研究探讨了LLM如何处理多模态任务。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.1  Action Space Paradigm/section/3/text
1. MM-ReAct 和 ViperGPT 如何利用语言模型执行多模态任务的思考过程，并选择视觉专家来解决任务？ 2. HuggingGPT 是如何通过四个阶段自动分析用户指令并预测最终答案，解决复杂的多模态任务？ 3. AI代理框架（如WebGPT、WebAgent）是如何通过与搜索引擎交互来增强代理从网站发现答案的能力？
MM-ReAct [497] 和 ViperGPT [498] 使用语言模型(LMs)执行多模态任务的思考过程，然后选择视觉专家来解决任务。Visual-ChatGPT [496] 整合了多个视觉专家，并使用LLMs作为控制器来解决任务。HuggingGPT [152] 直接涉及四个阶段，包括任务规划、模型选择、模型执行和响应生成，自动分析用户指令并基于复杂的多模态任务预测最终答案。对于代理来说，跟上线上最新信息至关重要。因此，一些AI代理框架（例如WebGPT [632]、WebAgent [634]）被设计为与搜索引擎进行交互，以增强代理从网站发现答案的能力。WebShop [633] 用于探索AI代理在在线购物中的潜力。Mind2Web [97] 用于构建模拟多个复杂网络任务的通用代理。随着基础代理在处理多模态任务或网络任务方面的进展，越来越多地增强它们解决复杂计算机任务的能力。Mobile-Agent [635] 利用多模态模型作为认知控制器来管理和编排移动功能。AppAgent [636] 将各种应用使用定义为动作空间，使基础模型能够与不同应用交互，作为移动智能助手。UFO [637] 和 OmniParser [520] 是两个先进的图形用户界面代理，将UI操作作为动作空间，使AI代理能够执行计算机使用任务。总的来说，在数字环境中拥有更先进的技能，AI代理可以展示更好的智能来解决复杂任务，并代表了从语言智能到数字智能的重要转变。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.1  Action Space Paradigm/section/4/text
1. AI代理如何通过扩展行动空间至网络浏览、GUI交互、移动应用和实体系统，实现更自主、多模态和具有上下文意识的系统演变，从而弥合基础模型和人类认知系统之间的差距？  2. 在整合LLM与结构化数字环境方面，Pangu、BIRD和Spider 2.0分别在哪些方面为LLM与知识图谱、企业数据库的连接奠定了基础？这些工作如何推动了LLM驱动的与关系数据库交互的可靠性？  3. 综合UnifiedSKG和Middleware框架，它们是如何扩展了LLM在数据库和知识图谱之间的行动能力？这种扩展对于提高AI代理在复杂任务中的表现有何影响？
通过扩展行动空间以包括网络浏览、GUI交互、移动应用和实体系统，AI代理正在向更自主、多模态和具有上下文意识的系统演变，弥合了基础模型和人类认知系统之间的差距。此外，其他研究探索了LLM与结构化数字环境（如关系数据库和知识图谱）的整合。Pangu [639] 开创了LLM与大规模知识图谱之间的连接，而 BIRD [640] 和 Spider 2.0 [641] 在现实环境中为LLM与企业数据库的操作奠定了基础。NL2SQL-BUGs [667] 解决了在NL2SQL流水线中识别语义错误的关键挑战，从而提高了LLM驱动的与关系数据库交互的可靠性。类似地，像UnifiedSKG [638] 和Middleware [642] 这样的框架扩展了LLM在数据库和知识图谱之间的行动能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.1  Action Space Paradigm/section/5/text
1. 如何通过预训练视觉-语言-动作模型来增强机器人在真实世界环境中的控制和动作执行能力？   2. 在处理来自物理环境的连续信号时，基础模型如何面临挑战，并且如何解决离散信号和连续信号之间的差异？  3. 通过机器人模型的预训练和微调，如何实现机器人动作预测和在物理系统中构建机器人学习的目标？
构建一个与真实物理世界互动的AI代理可以被视为模拟计算机程序以充当人类认知系统的最终目标。为了实现这一目标，我们需要使代理能够处理来自真实世界环境的信号并生成反馈以促进持续改进。因此，这将对如何处理传感器收集的连续信号并使基础模型做出决策提出新的挑战。为了实现这一目标，RT-family [522, 643, 644] 预训练视觉-语言-动作模型，将来自网络视频的知识整合到机器人学习中，增强机器人控制和动作执行能力。GR-2 [357] 是一个机器人模型，它在视频剪辑和语言数据上进行大规模预训练，然后在机器人轨迹上进行微调，用于机器人动作预测。$\pi_{0}$ [645] 基于机器人平台预训练了一个机器人模型，包括单臂机器人、双臂机器人和移动操纵器，以在物理系统中构建机器人学习。SayCan [646] 架起了机器人语义和LLM之间的联系，利用机器人模型为LLM提供感知，然后利用LLM进行高级决策制定。VoxPoser [647] 利用LLM理解和分解用于机器人操作的3D价值图。此外，EmbodiedGPT [648] 利用视觉-语言模型理解视频数据并执行决策驱动的动作。在物理环境中，值得注意的是，我们通常需要理解连续信号，然后为机器人控制生成连续动作。尽管现有的基础模型可以有效处理离散级别的动作（例如语言或计算机使用），但如何处理长时间的连续信号仍然具有挑战性。因此，在基础模型中消除连续信号与离散信号之间的差异仍然是一个主要问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.1  Action Space Paradigm/section/6/text
1. 动作空间在构建AI代理系统中的关键作用体现在哪些方面？它如何提升AI代理在处理下游任务时的能力和效率？ 2. AI代理系统中的动作空间通常包括哪些类型？它们如何涵盖从离散空间到连续空间的范围？ 3. 设计有效的动作空间对于推进能够进行真实世界互动的通用AI系统为什么至关重要？
通常，动作空间是构建有效AI代理系统中最关键的组成部分之一。有效的动作空间提升了AI代理在处理下游任务时的能力和效率。动作空间通常涵盖从离散空间（例如Atari游戏中的技能库）到连续空间（例如机器人操作）的范围。随着AI代理变得更加自主和多模态，设计有效的动作空间对于推进能够进行真实世界互动的通用AI系统将至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section
在行动学习范式中，AI代理通过与真实世界环境的互动不断完善其决策和行为。这包括构建行动空间、选择行动，并根据环境反馈优化行动选择。上下文学习利用大型语言模型的能力，通过提示技术指导代理生成行动，如链式思维和ReAct。监督训练包括预训练和微调，如RT系列和OpenVLA，以提高基础模型的行动能力。强化学习通过RL算法如DQN和PPO，以及分层强化学习方法，使代理从交互环境中学习并优化行动策略。这种整合使得AI代理在各领域展现出显著的决策能力，如自动驾驶系统和机器人操作任务。动作学习为代理赋予与外部世界互动的能力，为人工智能在实际应用中带来更多机遇。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/0/text
1. 行动学习在人类认知系统和AI代理中的共同之处在哪里？这种共同之处如何影响问题解决的过程和效果？  2. 在AI代理的行动学习中，上下文学习、监督训练和强化学习这三种学习范式各自的优势和局限性是什么？它们在提高代理行动系统效能方面有何不同的作用？  3. 行动学习如何帮助AI代理实现实时适应最新信息或不断变化条件的能力？这种实时适应对于代理在自主决策和行为优化方面的重要性体现在哪些方面？
在人类认知系统中，行动学习代表了解决问题的过程，涉及采取行动和反思反馈两个方面。类似地，对于AI代理来说，行动学习指的是一个自主AI系统通过与真实世界环境的直接互动不断完善其决策和行为的迭代过程。通常，行动学习包括多个阶段的循环，包括构建行动空间、选择行动，并根据与环境的互动（例如接收反馈或奖励并调整选择行动的策略）优化行动选择。通过迭代地应用这些策略，AI代理可以实时适应最新信息或不断变化的条件，最终实现更强大、灵活和高效的问题解决能力。因此，有效的行动学习机制对于优化代理行动系统至关重要。在这部分中，我们主要关注三种不同的代表性学习范式，包括上下文学习、监督训练和强化学习，具体讨论如下：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/1/text
1. 上下文学习中如何利用大型语言模型的能力来指导AI代理生成行动，以提高其推理和决策能力？ 2. 在行动学习中，链式思维提示和ReAct是如何帮助AI代理理解特定行动、执行行动并优化决策的？ 3. LearnAct如何通过迭代学习策略和生成代码来扩展行动空间，从而提升AI代理的行动能力？
在上下文学习中，由于大型语言模型展示了新兴能力，上下文学习被认为是利用现有LLM能力而无需任何修改的最有效方法。通过提供精心设计的提示来描述行动，AI代理可以理解特定行动，执行这些行动，反思与环境互动的结果，最终实现目标。在这些方法中，常见的方法是使用提示技术指导LLMs生成代理行动。其中，最具代表性的是链式思维（CoT）提示，应用“让我们逐步思考”技术生成一系列中间推理步骤，系统地探索潜在解决方案。ReAct使LLMs能够通过与环境内的互动生成推理路径和任务特定行动，提高AI代理的推理和决策能力。LearnAct设计了一种迭代学习策略，通过生成代码（即Python）扩展行动空间以创建和修改新行动。此外，一些研究（e.

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/2/text
1. 如何通过提示技术（如LLM）在Auto-CoT和其他框架中实现AI代理的自主思考过程和任务分解，以应对复杂任务的挑战？  2. 在机器人模型中，CoA是如何设计不同的提示设置来允许机器人在推理过程中进行操作的？这种设计如何影响机器人在处理复杂任务时的表现和效率？  3. 提示技术在HuggingGPT、Plan-and-Solve和其他框架中是如何被应用的，以将用户需求转化为可执行项和制定计划？这种方法对提高AI代理框架的模拟和生产力有何贡献？
Auto-CoT[137]探讨如何通过LLM自动生成CoT，从而实现AI代理的自主思考过程。为了处理更复杂的任务，ToT[72]将思考过程视为树结构，并通过LLM提示引入树搜索，而GoT[75]则应用图结构以及图搜索。对于机器人模型，CoA[649]设计了四种不同的提示设置（例如对象、抓取、空间和运动），以允许机器人在推理过程中进行操作。此外，为了解决需要复杂代理工作流程的更复杂任务，一些框架通过LLM提示引入任务分解阶段，以分解用户指令。Least-to-Most[138]是一种经典提示技术，将用户指令转换为多个子任务。HuggingGPT[152]是一个代表性的AI代理框架，应用任务规划将用户需求转化为可执行项。Plan-and-Solve[650]直接使用LLM根据用户指令制定计划，然后根据生成的计划给出答案。Progprompt[93]将类似的任务分解应用于机器人任务。此外，使用提示技术来制定AI代理的特征也被视为促进AI代理框架的模拟和生产力的增长趋势，例如Generative Agents [50]、MetaGPT[626]、ChatDev[627]和SWE-Agent[628]。最后，一些其他框架（例如

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/3/text
1. 如何通过Reflexion或Self-refine方法分析用户与环境的外部反馈，从而迭代地完善和优化结果？这种方法如何帮助代理更好地理解用户指令、分解任务目标，并制定计划？  2. 在上下文学习中，如何利用反思提示来避免参数优化，减少对大型语言模型进行训练的成本？这种方法如何帮助AI代理有效执行各种动作，适应不同领域？  3. 在强化学习中，代理如何能够通过Reflexion或Self-refine等方法获得更强大的行动学习能力？在实际应用中，这些方法可能面临哪些挑战？
Reflexion[48]或Self-refine[67]分析用户与环境的外部反馈，然后通过精心设计的反思提示迭代地完善和优化结果。所有这些设计都使我们能够更好地理解用户指令，分解任务目标，并为思考答案制定计划。在上下文学习中，可以帮助我们避免参数优化，并减少对LLM进行训练的巨大成本。这使得AI代理能够有效执行各种动作，并适应广泛的领域。然而，如果我们希望获得更强大的行动学习能力的代理，仍然存在挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/4/text
1. 监督训练中的自监督预训练（PT）和监督微调（SFT）在提高基础模型的行动学习能力方面有何优劣势？    2. 预训练范式在行动学习中的应用中存在的计算成本问题如何影响研究和实际应用的发展？  3. 如何评价RT系列、GR-2和LAM等作品在预训练范式下对基础模型行动学习能力的贡献？
监督训练为进一步提高基础模型的行动学习能力，增加的研究工作集中在训练方法上，包括自监督预训练（PT）和监督微调（SFT）。在预训练范式中，最具代表性的作品是RT系列[522, 643, 644]，它在大规模网络和机器人数据上对机器人Transformer进行预训练，产生了一个强大的视觉-语言-行动模型。遵循这一策略，GR-2[357]通过在大规模网络视频语料库上进行广泛的预训练，以理解世界的动态，并在机器人轨迹数据上进行后续训练，专注于视频生成和动作预测。同样，LAM[622]是一个在用户与计算机使用交互轨迹上进行预训练的大型行动模型。然而，预训练范式通常会带来巨大的计算成本。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/5/text
1. 如何利用微调范式来增强基础模型的行动能力，以及OpenVLA和CogACT是如何通过微调和整合不同模块来提高代理在真实世界任务中的表现的？  2. 在强化学习领域，RT-H和UniAct分别采用了怎样的方法来构建机器人的行动空间和学习通用动作特征？这些方法如何帮助代理从多样化数据集中学习并在不同任务中表现出良好的泛化能力？  3. 在上下文学习中，为什么即使在大规模语料库上进行了广泛训练，对AI代理进行上下文学习仍然是有益的？上下文学习如何有助于提高代理在实际应用中的最佳性能？
因此，许多工作采用微调范式来增强基础模型的行动能力。OpenVLA[670]基于Llama2[11]语言模型构建，并整合了基于DINOv2[671]和SigLIP[672]的视觉编码器。它在来自Open X-Embodiment（OXE）[673]的多样真实世界机器人演示数据上进行微调，在各种任务中表现优于RT-2-X[673]，同时参数数量仅为其$7\times$。在OpenVLA的基础上，CogACT [653]集成了额外的扩散动作模块，并引入了自适应动作集成策略进行推理。它还使用来自OXE的数据集进行微调，在SIMPLER [674]模拟环境中表现出35%的改进，在使用Franka Arm的真实机器人任务中增加了55%。此外，一些工作还探索了如何使机器人模型能够从物理世界中的普通语言中学习行动。例如，RT-H[654]引入了一种分层架构来构建行动空间，首先预测语言动作，然后生成低层次动作。而$\pi_{0}$ [645]从不同灵巧机器人平台收集了大量多样化数据集，然后微调预训练的VLMs来学习机器人动作。UniAct[56]学习捕捉不同形状机器人之间共享结构特征的通用动作。这种方法实现了跨领域数据利用，并通过消除异质性实现了跨体现泛化[132]。总的来说，使用监督训练，包括预训练和监督微调，可以有效地使基础模型在真实场景中智能执行行动。最后但并非最不重要的是，值得注意的是，即使在大规模语料库上进行了广泛训练，对AI代理进行上下文学习仍然是有益的，以追求它们的最佳性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/6/text
1. 强化学习如何通过与环境互动并优化行动策略，为代理在行动学习过程中带来哪些关键作用和优势？  2. 在强化学习范式中，如何通过经典算法如深度Q网络（DQN）和近端策略优化（PPO）来实现代理的行动优化？这些算法在行动学习中的应用有哪些特点和局限性？  3. 在将强化学习应用于基础模型的最具代表性工作InstructGPT中，如何有效地将语言模型输出与人类偏好对齐？这种方法在实践中可能面临哪些挑战和改进空间？
强化学习 为了促进行动学习过程，除了上下文学习和监督训练外，对于代理与环境进行互动并最终通过经验、反馈或奖励优化其行动策略也至关重要。考虑到这种迭代和顺序性质，强化学习（RL）为我们提供了所需的系统方法。在强化学习范式中，有几种经典代表性算法，如深度Q网络（DQN）和近端策略优化（PPO）。将强化学习应用于基础模型的最具代表性的RL工作是InstructGPT，它通过RLHF有效地将语言模型输出与人类偏好对齐。由于RLHF通常需要额外训练来构建奖励模型，一些论文（例如DPO）提出通过对比学习直接优化偏好数据。现有工作还展示了将RL算法扩展到基础模型以产生具有出色性能的长CoT思考阶段的潜力。尽管RL范式已成功用于微调LLM以进行文本生成任务，有效利用RL算法进行行动学习仍然是需要进一步尝试的许多挑战之一。最近的进展显示了在从各种角度应用RL到LLM进行行动学习方面取得的显著进展：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/7/text
1. 如何利用大型语言模型（LLM）中蕴含的丰富世界知识来引导代理进行高效探索，从而提升代理的行动学习效率？ 2. 在行动学习中，如何通过微调LLM并将其调整为状态转换模型和奖励函数，以提高离线RL推荐系统的性能？ 3. 当代理模型在代理环境中进行轨迹数据微调时，RL方法如何发挥作用，从而增强代理与外部环境的交互能力？
· 鉴于LLM中蕴含的丰富世界知识，我们可以利用LLM来模仿外部环境或生成想象的轨迹，以帮助代理进行行动学习。例如，RLFP[657]利用来自策略、价值和成功奖励基础模型的指导和反馈，使代理能够更高效地探索。类似地，ELLM[658]利用LLM中的大规模背景知识来引导代理在各种环境中进行高效探索。GenSim[659]通过利用LLM的编码能力自动生成丰富的模拟环境和专家演示，从而促进代理的自由探索能力。LEA [660]利用LLM的语言理解能力，并将LLM调整为状态转换模型和奖励函数，以提高离线RL推荐系统的性能。MLAQ [661]利用基于LLM的世界模型生成虚拟交互，并应用Q学习[684]从这种虚拟记忆中得出最优策略。KALM [662]微调LLM以在文本目标和展开之间执行双向翻译，使代理能够通过离线RL以虚拟展开的形式从LLM中提取知识。总的来说，通过RL范式的支持，我们可以显著探索LLM中的内部知识，从而增强与外部环境的交互。当前的工作，例如Search-R1[685]，R1-Searcher [686]，RAGEN[687]和OpenManus-RL[688]正在探索利用RL方法对代理模型在代理环境中的轨迹数据进行微调。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/8/text
1. 分层强化学习如何帮助AI代理在解决复杂任务时分解任务，学习最优策略，并如何通过高层指令和LLM生成奖励函数来提高效率？  2. 当代理利用LLM请求高层指令时，是如何通过分层强化学习学习低层策略的？这种方法在处理复杂任务时有哪些优势和应用前景？  3. 在分层强化学习中，代理如何利用离线RL算法学习高层值函数，进而隐式指导低层策略？这种方法如何帮助AI代理在文本任务和视觉观察中探索最优策略进行推理和规划？
此外，分层强化学习也是一个有前途的课题，它帮助基础模型分解复杂任务，然后通过强化学习范式学习解决每个任务的最优策略。例如，When2Ask[663]使代理能够从LLM请求高层指令。高层LLM规划者提供选项计划，代理基于这些选项学习低层策略。Eureka[664]利用LLM生成具有反思能力的人类级奖励函数，使代理能够高效学习复杂任务，如拟人五指操纵。ArCHer[665]采用分层强化学习方法，利用离线RL算法学习高层值函数，进而隐式指导低层策略。LLaRP[666]利用LLM理解文本任务目标和视觉观察。它采用额外的动作输出模块将LLM骨干的输出转换为动作空间上的分布。总的来说，使用分层强化学习可以指导人工智能代理在分析用户请求时探索最优策略以进行推理和规划。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/9/text
1. 在强化学习中，如何实现基础模型与在线学习的整合，以及动作策略和世界模型的结合，从而使人工智能代理中的高级动作系统成为可能？    2. 强化学习中代理如何动态地根据外部反馈调整和完善其决策过程，以促进动态学习的效率和效果？
利用强化学习，我们可以将基础模型与来自交互环境的在线学习相结合，同时整合动作策略和世界模型。这种整合使得人工智能代理中的高级动作系统成为可能。在强化学习范式中，代理动态地根据外部反馈调整和完善其决策过程，促进行动学习的效率和效果，从而实现期望的结果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/10/figure
1. 在图8.4中，不同的工具类别和学习范式之间是否存在明显的对应关系？这种对应关系是否对AI代理的决策能力产生影响？  2. 根据图8.4中工具系统的示意分类，哪种学习范式对于AI代理在实际应用中展现出更显著的决策能力？这种学习范式为何在特定领域中表现出优势？
图8.4：AI代理中工具系统的示意分类，包括工具类别和学习范式

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.2 Action Learning Paradigm/section/11/text
1. 动作学习如何使人工智能代理能够自动理解图形用户界面(GUI)并执行各种操作，从而提高人类的生产力？    2. 在机器人操作任务中，如何配备动作系统的人工智能代理取得显著的成果，例如物体拾取、衣物折叠和桌面清理？   3. 自动驾驶系统如何通过视觉语言模型的出色表现，有效理解真实世界环境并模拟人类水平的驾驶员？
总结一般来说，通过动作系统的支持，人工智能代理展示了在各个领域中显著的决策能力。例如，动作学习使得人工智能代理能够自动理解图形用户界面(GUI)并执行各种操作，从而通过自动化计算机使用提高人类的生产力。此外，一些研究表明，配备动作系统的人工智能代理在机器人操作任务中能够取得显著的成果，例如物体拾取、衣物折叠和桌面清理。工业界也有一些有前途的研究方向采用了动作模型。例如，自动驾驶(AD)因视觉语言模型在感知和决策方面的出色表现而引起了相当大的关注。通过将人类理解力整合到基础模型中，自动驾驶系统可以有效理解真实世界环境，使其能够模拟人类水平的驾驶员。总之，动作学习赋予代理与外部世界互动的能力，从而为人工智能在实际场景中的应用创造了更多机会。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.3 Tool-Based Action Paradigm/section
本节介绍了工具支持的行动范式在人工智能中的关键作用。工具学习将人类智能与其他动物的智能区分开来，通过利用各种工具使人工智能代理在数字和物理环境中运行，实现人类水平智能。工具在人工智能中被定义为允许代理与外部世界互动的接口或资源，如网络搜索、数据库和编码环境。工具系统的演变经历了不同阶段，从将工具转换为可解释格式到探索控制硬件与物理世界互动的具身代理。工具可以根据类型划分为语言、数字和物理领域，并在新兴领域（如科学发现）中展现潜力。工具学习的关键方面包括工具发现、工具创建和工具使用，为AI代理解决复杂任务提供了重要支持。通过工具学习，AI代理能够扩展任务范围、解决挑战和提高性能，从而构建更全能的智能系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.3 Tool-Based Action Paradigm/section/0/text
1. 工具学习如何帮助人工智能代理在数字和物理环境中实现人类水平智能？   2. 人工智能中的工具是如何定义的，以及它们在代理与外部世界互动中的作用是什么？   3. 工具系统在人工智能中的演变经历了哪些阶段，以及不同阶段对于AI代理解决复杂任务有何重要意义？
工具学习区分了人类智能与其他动物的智能。自石器时代以来，人类利用工具提高了效率、生产力和创新能力。类似地，通过利用各种工具使人工智能代理在数字和物理环境中运行，是实现人类水平智能的基本步骤。

在人工智能中，工具被定义为允许代理与外部世界互动的接口、工具或资源。例如，网络搜索、数据库、编码环境、数据系统和天气预报等都是工具的例子。通过将工具功能转化为纯文本或API格式，基础模型可以扩大其问题解决范围。人工智能中工具系统的演变可以总结为几个阶段。最初，随着大型语言模型的出现，重点是将工具转换为可解释格式（例如函数调用）。后来，多模式处理的进展将交互从对话式聊天转变为图形用户界面(GUI)，最近的工作探索了控制硬件（例如机器人手臂、传感器）与物理世界互动的具身代理。简而言之，基于工具的行动可以被视为一种用于辅助的外部行动形式。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.3 Tool-Based Action Paradigm/section/1/text
1. 工具在人工智能中的语言领域如何被表示为基础模型的函数调用，以促进外部工具的使用？这种表示方式如何扩展了语言模型的功能，并为人工智能代理的工具利用提供了怎样的优势？  2. 在语言领域中，ToolFormer、ToolLLM、Gorilla、ToolkenGPT、GPT4tools和AnyTool等工具是如何通过不同的方法和技术实现对工具的理解和利用的？它们各自的特点和应用领域有何异同之处？  3. 如何利用大型语言模型来优化工具嵌入，以使其能够检索工具并实现工具使用？基于语言的工具利用在人工智能代理中的应用中有哪些优势和挑战？
与动作空间类似，工具可以根据其类型被划分为多个类别。在这部分中，我们主要总结了三个关键领域，包括语言、数字和物理。此外，我们还探讨了工具学习在新兴领域（如科学发现）中的潜力：

· 语言：为了促进外部工具的使用，我们通常将工具表示为基础模型的一种函数调用，这通常包括任务描述、工具参数和相应的输出。这种表达方式使大型语言模型能够理解何时以及如何在人工智能代理中使用工具。具体而言，ToolFormer [689]通过整合计算器、问答系统、搜索引擎、翻译和日历等外部工具空间，扩展了语言模型的功能。ToolLLM [690]将RapidAPI作为行动空间，然后使用基于深度优先搜索的决策树算法确定解决任务最合适的工具。Gorilla [691]是基于工具文档进行微调的语言模型，然后可用于编写API调用。ToolkenGPT [692]旨在优化工具嵌入，从而使大型语言模型能够从经过微调的工具嵌入中检索工具。GPT4tools [693]和AnyTool [694]还构建了自我指导的数据集，然后对其进行微调，以供工具使用。总的来说，由于大型语言模型的出色能力，人工智能代理的基于语言的工具利用已经得到研究，其有效性在大量作品中得到验证，涵盖了从纯文本或函数调用到代码编程的范围。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.3 Tool-Based Action Paradigm/section/2/text
1. 工具学习如何帮助人工智能代理在数字领域中扩展任务范围和提高性能？   2. 在数字环境中，人工智能代理如何利用大型语言模型和多模态工具来解决不同任务？   3. 人工智能代理如何通过使用搜索引擎、GUI操作和应用程序等数字工具来增强解决复杂任务的能力？
· 数字：随着大型语言模型在处理语言信息方面取得成功，许多研究人员正在探索将人工智能代理的任务范围从语言领域扩展到数字领域（例如，多模态、网络搜索、图形用户界面等）。例如，MM-ReAct [497]、ViperGPT [498]和Visual ChatGPT [496]将LLMs作为控制器，然后使用LLMs选择视觉专家来解决不同的任务。HuggingGPT [152]和Chameleon [153]使用LLMs首先进行推理和规划动作，然后分析应该使用哪些多模态工具来解决用户指令。WebGPT [632]和WebAgent [634]分别为LLMs提供了搜索引擎，以增强LLMs解决更具挑战性任务的能力。Mobile-Agent [635]和AppAgent [636]分别将GUI操作和应用程序使用作为基于工具的行动，以扩展人工智能代理在解决手机任务中的任务范围。与物理世界相比，数字环境通常提供更简单的管道来收集和处理数据。通过涉及基础模型及其与数字环境的交互，我们可以在计算机、手机和其他数字设备中开发智能助手。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.3 Tool-Based Action Paradigm/section/3/text
1. 物理世界的应用在人工智能中面临哪些挑战？这些挑战如何影响工业应用的发展和实现？ 2. 工具集成在物理环境中的作用是什么？通过工具集成如何提高人工智能代理在物理世界中的性能和效率？ 3. 在自动驾驶系统等领域，如何将视觉-语言模型与工具集成，实现可解释的导航？这种集成方式对于实现自主外科手术等高级任务推理有何意义？
·物理：对于物理世界的应用，RT-2[643]展示了使用视觉-语言工具进行语言引导的机器人操作，TidyBot [695]展示了LLMs如何根据个性化家庭偏好调整清洁工具。SayCan [646]利用LLMs作为认知系统，通过机器人手臂和视觉感知指导机器人解决任务。SayPlan [292]构建了一个3D场景图作为行动空间，并为3D模拟设计了多个动作和工具，然后使用LLMs作为规划者来调用这些动作或工具进行机器人任务规划。此外，现在在不同领域中，真实场景中的专业应用也不断增加。例如，在外科机器人领域，[715]提出了一个多模态LLM框架，用于机器人辅助吸血，实现高层次任务推理，从而实现自主外科手术子任务。一些自动驾驶系统[716,717]也将视觉-语言模型与车辆控制工具集成，实现可解释的导航。总的来说，与其他任务相比，物理世界的应用是面临最大挑战的，但也提供了最大的工业价值。因此，未来仍需要我们继续探索物理环境中基于行动学习和工具集成的先进技术。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.3 Tool-Based Action Paradigm/section/4/text
1. 科学工具在推动AI代理在不同学科领域取得进步的关键作用体现在哪些方面？ 2. 如何描述HoneyComb、ChemCrow、SciToolAgent和SciAgent这些工具在材料科学和化学领域中的作用以及它们的特点？ 3. 工具驱动的多代理框架如何在加速材料科学及其他领域的发现中展现出潜力？
·科学：科学工具在推动AI代理在各个学科领域取得进步方面发挥了转变性作用，使它们能够学习、适应和执行任务，同时将基础模型与推动创新并解决复杂挑战的框架相结合。在材料科学领域，HoneyComb [696]通过其ToolHub展示了由工具驱动的进步。通用工具提供动态访问实时信息和最新出版物，有效地弥合了静态知识库中的差距。材料科学工具旨在为计算密集型任务设计，利用Python REPL环境动态生成和执行代码，用于精确数值分析。类似地，ChemCrow [697]通过将GPT-4与18个专家设计的工具集成，展示了化学领域工具的转变力量，以自动化有机合成、药物发现和材料设计等复杂任务。这些工具包括OPSIN用于IUPAC结构转换，计算器用于精确数值计算，以及其他专业化化学软件，实现准确的反应预测和分子性质评估。类似地，SciToolAgent [698]展示了多工具集成如何革新科学研究。设计用于解决现有系统的局限性，SciToolAgent集成了超过500种工具（例如Web API、ML模型、函数调用、数据库等）。最后，SciAgent [699]展示了一个集成本体知识图与专门代理用于假设生成和批判性分析的多代理框架，强调模块化、工具驱动系统在加速材料科学及其他领域的发现中的潜力。这些例子突显了将专业工具整合到AI框架中以有效解决特定领域挑战的转变潜力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.3 Tool-Based Action Paradigm/section/5/text
1. 工具发现在人工智能中的两种主流范式分别是什么？它们各自的特点和适用场景是怎样的？ 2. 如何通过基于检索和基于生成的方法来实现工具发现？这两种方法各自如何利用语料库和模型进行训练和微调？ 3. 工具发现阶段对AI代理的世界模型和多功能性有着怎样的要求？这些要求如何影响AI代理在选择和操作不同工具系统时的能力？
受人类进化启发的工具学习[718]，将工具集成到人工智能中涉及三个关键方面：工具发现（识别合适的工具）、工具创建（开发新工具）和工具使用（有效利用工具）。我们还系统地审查了现有文献，并总结如下：

1. 工具发现：在现实环境中，从数字到物理世界存在各种各样的工具。为用户指令找到最合适的工具可能具有挑战性。因此，工具发现的过程是识别和选择AI代理可以操作以实现其目标的适当工具。这一阶段还要求AI代理的世界模型对任何复杂的用户指令和不同工具的世界知识具有深刻理解。此外，AI代理的多功能性也与其操作不同工具系统的能力相关。一般来说，工具发现可以分为两种主流范式：基于检索和基于生成的方法。基于检索的方法旨在从工具库中选择最相关的工具。例如，HuggingGPT [152]引入了一个框架，其中LLMs充当控制器，编排任务规划，然后调用来自Hugging Face等平台的合适模型以实现用户意图。在基于生成的方法中，我们通常对LLMs进行微调，以学习如何根据各种用户指令使用和选择工具。例如，ToolFormer[689]收集了大量语料库，其中包括相应的API调用（例如计算器、问答系统、搜索引擎、翻译和日历）进行训练。ToolLLM[690]根据解决路径收集工具指令，然后对Llama模型进行微调，以生成更好的API调用以利用工具。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.3 Tool-Based Action Paradigm/section/6/text
1. 工具创建在人工智能中的关键作用是什么？它如何促进AI代理解决复杂任务和提高性能？ 2. 除了利用现有工具，创造新工具对于人类文明的重要性体现在哪些方面？LLMs在工具创建中扮演着怎样的角色？ 3. 如何利用LLMs生成可执行程序的函数来创造新工具？PAL、LATM、Creator和SciAgent分别是如何利用LLMs来实现工具创建的？
2. 工具创建
除了使用现有工具外，创造新工具的能力在人类文明中起着至关重要的作用。对于语言代理，一种被广泛采用的方法是利用LLMs生成作为可执行程序的函数，这些函数包括代码和文档。例如，PAL[701]生成程序作为解决问题的中间推理步骤，LATM[702]或Creator[703]使用LLMs为用户意图创建代码，并进一步设计验证器来验证所创建的工具。SciAgent[699]不仅集成了多个科学工具，还为科学发现创造新工具。关于工具创建的更多细节，可在第9.4.2节中找到从优化角度的讨论。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.3 Tool-Based Action Paradigm/section/7/text
1. 工具使用如何构成了AI代理能力的基石，以实现虚拟和物理世界之间的应用程序？ 2. 在现代AI代理中，垂直专业化、水平整合和具体化这三个关键扩展维度是如何帮助代理处理跨领域复杂任务的？ 3. 工具使用对于AI代理在机器人技术、科学和医疗保健等领域中实现专业水平性能有何重要意义？
3. 工具使用
在收集或创建工具之后，有效利用工具构成了AI代理能力的基石，使得能够构建虚拟和物理世界之间的应用程序。现代AI代理越来越多地利用工具来处理跨越各种领域的复杂任务，具有三个关键的扩展维度：1) 垂直专业化：代理利用特定领域的工具在复杂领域（如机器人技术、科学和医疗保健）中实现专业水平的性能；2) 水平整合：系统跨越多种形式（视觉、语言、控制）结合多模态工具包进行问题解决；3) 具体化：代理通过机器人工具和传感器与环境进行物理交互。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.3 Paradigms of Agentic Action System/8.3.3 Tool-Based Action Paradigm/section/8/text
1. 工具学习如何帮助AI代理拓展任务范围，并将边界推动至基础模型的范围之外？ 2. 在工具学习中，如何确定工具空间、发现和选择工具，以及创建和使用工具这些具有挑战性的阶段是如何解决的？ 3. 工具学习在构建全能的AI代理框架中的关键作用体现在哪些方面？
总结 工具学习和行动学习构成了AI代理行动系统中最重要的两个组成部分。工具学习可以被视为利用外部状态进行问题解决的一种行动方式。工具学习使得AI代理能够显著拓展他们的任务范围，将边界推动至基础模型的范围之外。例如，通过API或函数调用的支持，语言模型可以直接重复利用现有模型的能力（例如检索、编码、网络搜索）来生成答案，而不是进行下一个标记的预测。工具学习还涉及多个具有挑战性的阶段，包括如何确定工具空间、如何发现和选择工具，以及如何创建和使用工具。总体而言，工具学习在构建一个全能的AI代理框架中发挥着至关重要的作用，以解决不同领域中的复杂任务。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.4 Action and Perception: “Outside-In" or “Inside-out"/section
在智能系统中，关于行动和感知哪个在因果流中起主导作用存在认知科学和神经科学的争议。传统观点认为外部刺激引发感知，最终影响行为，而“从内到外”的框架则主张代理人的行为塑造了信号意义。这种框架下，代理人主动产生预测和运动命令，内部信号指导感知，使外部刺激成为确认或纠正。这种逆转影响了对感知目的和功能的理解，将感知视为更新代理人关于环境假设的手段。从进化角度看，行动能力在进化中早于复杂感知，即使简单生物也能从运动中获益，暗示行动能力不仅源自外部刺激，而是具有独立意义。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.4 Action and Perception: “Outside-In" or “Inside-out"/section/0/text
1. 在智能系统中，传统“从外到内”观点和Buzsaki的“从内到外”框架之间的主要区别是什么？这种区别如何影响对于感知和行动在因果流中的理解？  2. 从进化的角度出发，为什么认为行动能力在进化中早于复杂感知？这种观点对于我们理解智能系统中行动和感知的关系有何启示？  3. 在Buzsaki的框架下，代理人如何通过内部产生的信号来更新和完善关于环境的基于行动的假设？这种方式如何改变了对于感知目的和功能的理解？
认知科学和神经科学中的一个核心争论是关于行动或感知在智能系统中的因果流中起到根本作用。图8.5呈现了不同的观点。传统的“从外到内”的观点坚持认为，因果影响始于外部刺激。环境刺激外围感受器，这些信号向内传播，最终产生行为。这种观点描绘了生物体或代理人本质上是被动的：外部世界导致感觉变化，代理人的行为代表了这些变化的下游效应。相比之下，Buzsaki的“从内到外”的框架[18]提出，正是代理人自己的行为塑造了传入信号的意义和后果。这种观点意味着一个主动的代理人，不断产生预测和运动命令，同时向感觉区域发送“副产生放电”或“行动副本”。这些内部产生的信号作为参考，告知代理人哪些感觉变化是自发启动的，而不是外部世界强加的。通过这种方式，因果从外部事件转变为内部发起的倡议，使外部刺激扮演确认或纠正角色。这种逆转对我们如何解释感知的目的和功能有重要影响：感知并非自身目的，而是更新和完善代理人关于环境的基于行动的假设的手段。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.4 Action and Perception: “Outside-In" or “Inside-out"/section/1/text
1. 从进化的角度来看，为什么拥有在不依赖复杂感知分析的情况下移动的能力可以带来即时的生存益处？这种运动如何影响生物体在富含营养的水域中获取食物的能力？  2. 进化时间尺度上，为什么行动能力先于高级感知出现？这种序列的出现对我们理解生物行为和感知的关系有何启示？  3. 行动能力不仅仅是外部刺激的结果，而具有独立意义。你认为这种独立意义体现在哪些方面？行动能力对生物体的生存和繁衍有着怎样的重要性？
从进化的角度来看，拥有在不依赖复杂感知分析的情况下移动的能力可以带来即时的生存益处。即使是简单的生物体也能从定期运动中获益，这种运动搅动了富含营养的水域中的食物，早在复杂的感知能力进化之前。换句话说，在进化的时间尺度上，运动先于高级感知，这表明行动能力不仅仅是外部刺激的结果，而是可以

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Brain from Outside-ln/section
在智能代理领域，行动和感知之间的互动关系至关重要。外源性大脑概念强调了行动对感知发展的推动作用，通过额外传感器的引入，指导代理的运动，将感知基于效用，并将感官辨别与运动结果联系在一起。研究发现，中断行动和感知互动揭示了错综复杂的因果循环，如睡眠瘫痪期间的现象。神经生理数据支持内在-外在模型，表明大脑中的原因源自内部，指导外部信号的处理。当前大多数人工智能系统处于被动模式，但积极的智能代理可以通过自发行为形成假设，减少歧义，优化内部状态。这种转变可以提高数据效率和上下文感知，增强代理处理复杂任务和泛化能力，为下一代人工智能系统的发展提供新的思路。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Brain from Outside-ln/section/0/figure
1. 根据图8.5(a)的描述，“外部到内部”和“内部到外部”比较大脑的结构有何不同之处？这种不同可能对智能代理的行为产生怎样的影响？  2. 在图8.5(b)中描述了余留放电机制的示意图，这种机制是如何实现运动命令和感知系统之间的调节和协调的？余留放电如何影响感知系统对外部输入的处理？
图8.5：(a) 从“外部到内部”和“内部到外部”比较大脑。(b) 描述了余留放电机制的示意图。一个运动命令（传出信号）从运动区域传输到眼部肌肉，同时一个余留放电（虚线箭头）被路由到感觉系统中的比较器。比较器使用这个内部信号来调节或减去外部（外来）输入。此外，来自肌肉的张力反馈（再传入信号）对感知产生延迟影响。所有哺乳动物的大脑皮层中都存在从运动到感觉皮层的直接投射，这种结构是该架构的基础。部分(b)改编自参考文献[18]中的原始图。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Brain from Outside-ln/section/1/text
1. 行动如何在智能代理中起到推动感知发展的作用？这种发展顺序是如何将感知基础于效用，并联系感官辨别与运动结果的？ 2. 睡眠瘫痪期间的错综复杂因果循环如何揭示了行动和感知互动中的中断？这种中断如何导致个体经历虚幻感和混淆？ 3. 内在-外在模型如何解释了大脑中的“原因”通常源自内部，指导外部信号的处理？这种模型对于理解智能代理中的感知与行动互动有何启示？
在行动机制足够建立之时，动作本身成为随后感知发展的推动因素。正是额外传感器的加入使代理受益，这些传感器更有策略地指导这些运动。这种发展顺序将感知基础于效用，将感官辨别与运动的实际结果联系在一起。

行动和感知正常互动的中断揭示了错综复杂的因果循环。在睡眠瘫痪期间，大脑的运动命令暂时无法到达肌肉；外部刺激仍然轰击感官，但通常的行动到感知的校准丢失了。因此，个体会经历一种加剧的虚幻感，因为大脑缺乏内部产生的参考信号来解释感官输入。同样，如果在大脑没有发出运动命令的情况下外部操纵眼睛，视觉场景似乎会移动，突显了单纯感知——缺乏先前、自发行动的情况下——可能导致混淆。神经生理数据进一步支持内在-外在模型。许多曾被视为“纯粹感觉”的区域的神经元不仅追踪外部刺激的变化，还追踪自发的运动——有时甚至更强烈。这表明大脑中的“原因”经常源自内部，指导外部信号的幅度和意义。没有这些内部相关因素，原始的感官数据可能对系统而言变得模棱两可，甚至无用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Brain from Outside-ln/section/2/text
1. 智能代理如何通过自发行为形成和测试假设，从而减少歧义并优化内部状态？ 2. 被动模式与主动模式在智能代理中的角色和作用有何不同，对代理的行为和性能有何影响？ 3. 如何利用内部-外部视角的启示，改善人工智能系统的数据效率、上下文感知能力以及处理复杂任务的能力？
智能代理的启示内部-外部视角为现代智能代理研究提供了深刻的见解。大多数当代人工智能系统——以及许多LLM代理——仍然主要以一种被动模式运作，等待用户输入，并根据从大量数据集中学习到的统计相关性生成响应。这种被动性类似于一种“外部-内部”框架，代理的角色受限于响应而非主动发起。然而，如果一个代理是主动的，通过自发行为（物理或表征性）持续形成和测试假设，它可能会基于自身的“感知”输入——无论是感官流或语言提示——从而减少歧义。例如，一个基于LLM的代理，插入问题或根据知识库验证自己的陈述，可以更好地区分哪些推论是自身引起的，哪些是外部数据要求的。通过跟踪这些自发贡献（类似于余流放电），模型可以改善连贯性，减少称为“幻觉”的错误，并通过迭代的因果循环优化其内部状态。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Brain from Outside-ln/section/3/text
1. 积极的智能代理如何通过探索、引发反馈以及将自动生成的经验纳入训练中来提高数据效率和上下文感知？  2. 行动和感知之间的紧密耦合如何有助于增强代理处理复杂任务、适应意外挑战并更稳健地泛化的能力？  3. 为什么将感知重新定位为行动的因果下游可以促进智能系统从 passively 等待标记示例转变为积极创造、塑造和解释回流信号中的信息？
积极的立场还鼓励更具数据效率和上下文感知的学习。代理不再 passively 等待标记示例，而是可以探索、引发反馈，并将自动生成的经验纳入其训练中。随着时间的推移，行动和感知之间的紧密耦合可能增强代理处理复杂任务、适应意外挑战并更稳健地泛化的能力。从外部到内部模型的转变将感知重新定位为行动的因果下游。智能系统——无论是生物还是人工的——都有望从认识到有目的的运动，或者在LLM的情况下是积极的对话步骤，可以积极地创造、塑造和解释回流信号中的信号中受益。通过承认行动的因果关系能力，并努力构建积极而非仅仅是反应性代理，我们可能会更深入地理解自然认知和下一代人工智能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Brain from Outside-ln/section/4/table
1. 人类和人工智能代理在感知方面有何相似之处，有何不同之处？ 2. 行动对于人类和人工智能代理的感知发展有何影响？
表8.2：比较人类和人工智能代理的感知和行动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.5 Summary and Discussion/section
在"总结与讨论"章节中，我们系统性地审查了行为系统对AI代理的影响。行为系统的重要性体现在行为空间、行为学习和工具学习三个方面。行为空间决定了AI代理在任务执行中的上限，而行为学习使代理能够学习和优化策略，包括零样本学习。行为系统与工具系统的整合提高了代理在动态环境中的性能和鲁棒性。未来，需要解决效率、评估、多模态学习、隐私和伦理等挑战，以实现更广泛的任务处理和提高AI代理的性能。在基础模型和外部工具之间取得平衡是未来发展的关键，以确保开发多功能且高效的人工智能代理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.5 Summary and Discussion/section/0/text
1. 行为系统如何影响AI代理在任务执行中的上限，以及如何促进代理学习和优化策略？ 2. 人类认知系统中的行为系统是如何逐步发展大脑智能并创造新文明的？AI代理中的行为系统又如何类似于这一过程？ 3. 在动态环境中，为什么整合行为系统和工具系统对AI代理的性能和鲁棒性至关重要？
传统上，行为代表了基于与环境的互动反馈的人类认知系统的行为。它赋予人类思考、推理、言语、奔跑和执行任何复杂操控的能力。基于行为系统，人类可以通过增强他们对世界的感知和行动来逐步发展大脑智能，并形成一个闭环以进一步在世界中创造新的文明和创新。类似于人类认知系统，行为系统加上工具系统对AI代理也发挥着重要作用。整合行为系统使AI代理能够系统地规划、执行和调整他们的行为，促进在动态环境中更具适应性和鲁棒性的表现。在本节中，我们系统地审查和总结了行为模块对AI代理的影响，重点关注行为系统和工具系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.5 Summary and Discussion/section/1/text
1. 行为空间在AI代理中的作用如何影响代理在解决下游任务时的上限？在面对复杂任务时，如何构建稳健和通用的行为空间成为了怎样的挑战？ 2. 行为学习是如何帮助AI代理在与外部世界互动中学习和优化策略的？基于不同的基础模型，行为学习又衍生出哪些不同的范式？ 3. 未来发展中，如何在基础模型和外部工具之间取得平衡，以确保开发多功能且高效的人工智能代理？如何解决效率、评估、多模态学习、隐私和伦理等挑战？
行为系统 在我们的研究中，我们从三个角度简要描述了行为系统：行为空间、行为学习和工具学习。在行为系统中，行为空间通常作为最重要的组成部分，决定了AI代理在解决下游任务时的上限。它规定了AI代理在与真实世界环境互动时可以选择和执行哪些动作。对于行为空间，根据数据类型的不同，从离散到连续数据，也存在各种困难。随着对AI代理的需求不断增长，人们对AI代理处理更复杂任务的期望也在增加，特别是涉及真实应用的任务。因此，如何构建稳健和通用的行为空间仍然是行为系统中的一个持续挑战。在行为空间的基础上，行为学习是使代理能够有效与外部世界和人类互动的另一个关键组成部分。行为学习代表了AI代理在与真实世界环境互动过程中学习和优化其策略的过程。基于不同的基础模型，它也衍生出不同的行为学习范式，例如零样本学习。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.5 Summary and Discussion/section/2/text
1. 在行为学习中，如何解决ICL范式所需的先验知识问题，以确保适当的提示设计？ 2. 在整合预训练和微调数据集进行监督训练时，如何处理数据的高质量和多样性要求，以减少人力投入？ 3. 在大规模训练场景中应用强化学习时，如何克服其不稳定性带来的困难，以提高AI代理的性能和稳定性？
在行为学习中，深入了解任务是至关重要的，包括如何设计系统提示、如何确定预训练或微调数据集，以及在训练过程中的奖励信号或优化策略。尽管在推动AI代理框架方面在行为学习方面取得了显著进展，但仍有许多问题有待解决。具体来说，ICL范式需要特定的先验知识来进行适当的提示设计。此外，将预训练和后训练结合进行监督训练需要高质量和多样化的数据，这通常需要细致的数据处理和大量人力投入。此外，强化学习的不稳定性在大规模训练场景中应用时存在困难。此外，行为系统的设计在最大化工具集成的好处方面起着至关重要的作用。通过整合有效的行为系统，AI代理可以无缝地与各种工具互动，执行复杂的用户意图，并将外部数据转化为有意义的结果。行为系统与工具之间的协同作用不仅可以减轻记忆限制并降低幻觉风险，还可以增强系统的专业知识和稳健性。例如，配备强大行为系统的AI代理可以动态选择并使用最适合特定任务的工具，从而确保其响应的准确性和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.5 Summary and Discussion/section/3/text
1. 行为系统如何促进了层次推理过程，进而使AI代理能够组织复杂的工作流程，与用户目标紧密契合？ 2. 在人工智能代理中，为什么弥合基础模型能力与实际应用需求之间的差距至关重要？行为系统和工具执行过程如何在这一过程中发挥作用？ 3. 专业工具与强大行为系统的结合如何显著提升了AI代理在多样化和动态环境中的性能、可靠性和适用性？
此外，行为系统促进了层次推理过程，使代理能够组织复杂的工作流程，与用户目标紧密契合。这种对齐对于需要精确执行和实时决策的任务至关重要，从而弥合了基础模型能力与实际应用需求之间的差距。此外，工具执行过程提供的透明度和可解释性增强了用户信任，并促进了有效的人机协作。因此，专业工具与强大行为系统的结合显著提升了AI代理在多样化和动态环境中的性能、可靠性和适用性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.5 Summary and Discussion/section/4/text
1. 在构建有效的行为系统时，效率问题如何成为一个重要障碍？采取哪些策略可以缓解这一问题？  2. 为什么效率在实时应用中尤为重要？行为系统的复杂性如何可能导致不可接受的延迟？  3. 针对行为系统的效率挑战，提到了过滤不相关信息、利用零提示简化推理过程和利用高速存储解决方案等策略，这些方法如何有助于保持高性能并减少响应时间？
总之，行为系统可以显著建立AI代理框架的解决问题能力的基础，使它们能够处理更广泛的复杂任务，超越基础模型的范围。

未来方向然而，为代理构建有效的行为系统需要解决一系列挑战，我们在以下总结：

1.效率是一个重要障碍，特别是在需要快速和精确响应的实时应用中。行为系统涉及的复杂性可能导致不可接受的延迟，阻碍AI系统在欺诈检测或实时决策等场景中的实际部署。为了缓解这些效率问题，必须采取策略，如过滤掉不相关或冗余信息，利用零提示来简化推理过程，并利用高速存储解决方案缓存相关知识。这些方法有助于保持高性能的同时减少响应时间。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.5 Summary and Discussion/section/5/text
1. 在AI代理中，如何建立有效和稳健的评估系统来衡量行为系统的准确性和可靠性？这种评估系统如何帮助避免来自不同来源的行为或工具之间的冲突信息？  2. 在行为系统中，为什么揭示基础模型的决策过程对于理解哪种行为更好以及如何与各种行为或工具协调至关重要？这种揭示过程如何有助于提供可信赖的输出？  3. AI代理在现实世界环境中面临来自不同来源的大量行为，如何解决确定正确行为或工具的挑战？如何通过开发稳健的评估系统和验证协议来减少行为预测中的不正确性？
2. 评估在行为系统中也是一个重要因素，包括行为学习和工具学习。在现实世界的环境中，来自不同来源的大量行为存在。因此，如何确定来自不同来源的正确行为或工具，以避免冲突信息，仍然是AI代理中一个重要挑战。为了缓解这些问题，建立有效和稳健的评估系统来衡量行为系统是至关重要的，以保持响应的准确性和可靠性。开发稳健的评估系统、验证协议，并创建透明的方法对于减少行为预测中的不正确性至关重要。此外，揭示基础模型的决策过程也有助于我们理解哪种行为更好，以及如何与各种行为或工具协调，提供可信赖的输出。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.5 Summary and Discussion/section/6/text
1. 如何解决基于大型语言模型的自主代理在理解和调用超出语言指令范围的行为方面所面临的挑战，以提高AI代理在处理现实场景任务时的表现能力？  2. 在多模态行为学习中，如何实现AI代理通过各种形式的指令（如语言、图像、视频或人类引导）来学习和发展新技能，以缩小人类与AI代理在工具利用方面的差距？  3. 在提升AI代理在解决现实场景任务中的能力方面，如何探索并促进多样的模态开发或学习行为，以推动未来先进代理框架的设计？
3. 基于大型语言模型的自主代理中，多模态行为学习取得了显著进展。然而，如何理解和调用超出语言指令范围的行为（例如GUI操作或具体工具）仍然是挑战。在现实场景中，人类可以通过任何形式的指令（例如语言、图像、视频或人类引导）开发或学习新技能的使用。因此，使AI代理能够通过多样的模态开发或学习行为对于提升AI代理在解决来自现实场景的实际任务中的能力至关重要。换句话说，我们有必要探索如何减少人类和AI代理在工具利用方面的差距，促进未来先进代理框架的设计。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.5 Summary and Discussion/section/7/text
1. 在生成式人工智能领域中，如何确保模型在维护数据完整性的同时保持高性能？  2. 在人类与模型协作的伦理影响方面，如何确保人类尊严和自主权得到有效保护？  3. 在模型与物理环境交互的安全问题中，如何发展强大的安全机制以预防潜在风险？
4. 隐私在生成式人工智能领域尤为关键，特别是在使用大型语言模型时。因此，在工具利用中，维护敏感用户数据的隐私和防止用户行为的披露至关重要。为了解决这些隐私问题，可以采用一些安全技术，如联邦学习，使模型能够在分散的数据源上进行训练，而不直接暴露敏感信息。此外，通常需要进行模型蒸馏，以确保模型在维护数据完整性的同时保持高性能。这些方法能够有效地训练模型，同时保护用户数据的保密性。

5. 此外，人类与模型协作的伦理影响以及模型与物理环境交互所涉及的安全问题需要认真考虑。在将人类劳动与人工智能系统整合时，确保人类尊严和自主权得到保护至关重要。建立伦理准则，促进公平的工作条件，促进跨学科合作是解决这些问题的必要条件。此外，发展强大的安全机制，以防止人工智能系统与物理工具或行为交互时发生错误或恶意行为，对于防范潜在风险至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/8.5 Summary and Discussion/section/8/text
1. 如何确定何时在人工智能代理中使用基础模型而非外部工具，以实现最佳平衡？这种平衡对于提高代理的性能和功能至关重要吗？  2. 在人工智能代理发展中，如何应对增强基础模型内在能力的增长趋势，以确保代理的多功能性和高效性？  3. 在发展人工智能代理的过程中，如何解决基础模型与外部工具之间的平衡问题，以应对动态环境和提高代理的鲁棒性？
除了上述挑战之外，行动系统仍然存在一些未解决的问题。例如，如何在基础模型和外部工具之间实现最佳平衡，确定何时使用前者而非后者的适当时机，仍然没有答案。具体来说，尽管工具系统可以为基础模型提供灵活性和可扩展性，但越来越多地增强基础模型的内在能力是一个增长的趋势。因此，在基础模型和工具系统之间取得平衡对于开发多功能且高效的人工智能代理至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Self-Evolution in Intelligent Agents/section
在智能体中的自我进化领域，传统手动设计的人工智能系统正逐渐被自动化学习解决方案所取代。代理系统的自我进化将代替手动设计，使代理能自主完善能力、适应环境并实现持续学习。LLM代理的自我进化带来了三大优势：可扩展性、降低劳动成本和与自然智能发展一致。利用LLMs推动代理系统自我进化的方法，如AFLOW，已经取得成功，标志着代理系统设计的范式转变。研究探索了各种代理系统优化空间，传统优化算法和元优化，并分类了自我进化场景为在线和离线优化。LLM代理的自我改进技术应用于人工智能科学领域，推动知识发现。最后，讨论了代理自我进化技术相关的安全问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Self-Evolution in Intelligent Agents/section/0/figure
1. LLM代理中的自我进化结构图中展示了哪些关键组成部分？ 2. 如何利用图8.6中展示的LLM代理自我进化结构来实现代理系统的自主完善能力和持续学习？
图8.6：LLM代理中的自我进化结构。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Self-Evolution in Intelligent Agents/section/1/text
1. 代理系统中的自我进化如何取代了传统的手动设计方法，以实现更高效的学习解决方案？  2. AutoML如何在机器学习领域展示了自动化成功的先例，以及如何启发将类似原则扩展到代理人工智能系统的领域？ 3. 代理自我进化的完全自动化目前尚未实现，但为什么被认为是未来进展的必要方向？
在机器学习研究的历史中，手动设计的人工智能系统逐渐被更高效的学习解决方案取代。例如，在深度学习出现之前，特征通常是由专家手工设计的，但最终被神经网络提取的特征所取代。随着神经网络变得越来越复杂，各种自动设计技术，如神经架构搜索，已经出现，进一步取代了需要手动设计网络结构的需求。同样，代理系统最初严重依赖手动设计，行为规则和决策策略是由开发人员明确制定的。虽然代理自我进化的完全自动化尚未实现，但预计并被认为是未来进展所必需的。这种自动化的成功先例已经可以在自动化机器学习（AutoML）中看到，它自动化了传统机器学习流程的各个组件。特别是，AutoML简化了机器学习算法流水线的选择和配置，同时结合了高级的超参数优化技术。在AutoML的最显著应用中，NAS自动设计神经网络架构以增强模型性能。受传统机器学习中成功向自动化转变的启发，我们提议将类似原则扩展到代理人工智能系统的领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Self-Evolution in Intelligent Agents/section/2/text
1. 代理人工智能系统的自我进化如何可能将其开发和改进置于一个自主、自我维持的循环中？ 2. 在LLM代理中启用自我进化机制相比传统手动设计的系统，到底有哪些优势和价值？ 3. 代理研究中存在的反直觉问题是什么，为什么当前手动设计的代理人工智能系统最终可能被自动化学习解决方案所取代？
当前代理研究中一个关键的反直觉问题是，虽然开发或改进代理人工智能系统的最终目标是自动化人类工作，但创建这些系统的过程目前仍然超出了完全自动化的范围。因此，我们认为，所有手动设计的代理人工智能系统最终将被可学习和自我进化的系统所取代，这可能最终将代理人工智能的开发和改进置于一个自主、自我维持的循环中。在LLM代理中启用自我进化机制具有以下好处：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Self-Evolution in Intelligent Agents/section/3/text
1. 自我进化的代理系统相较于基于LLM的代理系统在可扩展性上有何优势？ 2. 在代理系统的自我进化中，如何实现优化代理行为而无需修改基础的LLM？ 3. 为什么升级基于LLM的代理模型昂贵且需要大量重新训练，而自我进化的代理系统提供了更高效和可扩展的解决方案？
1. 可扩展性：尽管基于LLM的代理展现出了卓越的性能，但它们的改进仍然严重依赖于基础的LLM。然而，升级这些模型是昂贵的，并且通过包含额外的现实世界数据来扩展性能需要在大型数据集上进行大量的重新训练，这带来了重大的资源限制。相比之下，自我进化的代理系统可以优化代理行为，而无需修改基础的LLM，提供了更高效和可扩展的解决方案。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Self-Evolution in Intelligent Agents/section/4/text
1. 自我进化的代理系统如何通过降低劳动成本实现对传统手动设计方法的优势转变？ 2. LLM代理系统的自我进化是如何与自然智能的发展趋势保持一致的？
2. 降低劳动成本：手动设计代理系统是一个复杂而劳动密集的过程，需要开发人员深入研究复杂的技术细节。传统方法通常涉及从头开始构建这些系统，需要相当多的专业知识和努力。相比之下，自我进化的代理系统可以自动化这个过程的大部分内容，显著减少了对手动干预的需求，降低了开发成本。

3. 与自然智能发展一致：正如人类通过学习和适应不断改进自己一样，为LLM代理配备自我改进能力是迈向真正自主代理的发展的必要步骤。这使它们能够优化性能，适应新挑战，并在没有直接人类干预的情况下进化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Self-Evolution in Intelligent Agents/section/5/figure
1. 在图8.7中，优化空间、优化器和优化目标之间的关系是如何体现的？ 2. 如何利用图8.7中描述的关键概念，实现LLM代理系统的自我改进？
图8.7: 本节讨论的关键概念示意图，包括优化空间、优化器和优化目标。优化器在优化空间内迭代地改进组件，以增强代理系统，直到达到满意的结果，从而实现LLM代理系统的自我改进。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Self-Evolution in Intelligent Agents/section/6/text
1. LLMs如何作为推动引擎实现代理系统自我进化的方法，相较于传统优化方法有哪些优势和特点？    2. AFLOW是如何利用蒙特卡洛树搜索来发挥LLMs的全面能力，实现自动化生成和优化整个代理系统工作流程的？这种方法如何代表了代理系统设计范式的转变？  3. 在代理系统自我进化领域，LLMs如何拓展了优化空间，使得自然语言成为通用桥梁，实现了对复杂、异构参数的优化？
为了实现自动化人类努力的目标，许多研究提出了利用LLMs作为推动引擎，实现代理系统自我进化的方法。特别是，LLMs为传统优化方法（如基于梯度和基于强化学习的方法）提供了一种高效的替代方案。它们将优化空间从数值值扩展到更多样化的领域，其中自然语言作为一种通用桥梁。LLM能够优化复杂、异构的参数，如指令和工具实现，并可以跨越各种LLMs，包括开源和闭源模型。这种方法的一个显著例子是AFLOW，它自动化生成和优化整个代理系统工作流程。该系统利用蒙特卡洛树搜索来发挥LLMs的全面能力。在这个框架中，传统手工制作的代理系统被算法生成的系统所取代，标志着一种范式转变。此外，越来越多的研究探索类似的方法，进一步推动了该领域的发展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Self-Evolution in Intelligent Agents/section/7/text
1. 代理系统优化空间的探索中，为什么需要包括提示、工具和工作流程？这三者如何相互促进代理系统的自我进化？  2. 传统优化范式和元优化对于代理系统的自我进化有何影响？优化过程如何影响基础优化算法本身的发展？  3. 在探讨自我进化场景时，为什么将其分类为在线优化和离线优化两种类型？这两种类型各自在代理系统的自我进化过程中扮演着怎样的角色？
本部分结构如下：首先，我们介绍了最近研究中探索的各种代理系统优化空间，包括提示、工具和工作流程。在接下来的部分中，我们回顾了优化算法，讨论了传统优化范式和元优化，其中优化过程也影响基础优化算法本身。然后，我们探讨了自我进化场景，将其分类为在线优化和离线优化两种类型。在此之后，我们讨论了大型语言模型（LLM）代理自我改进技术的应用，特别是在人工智能科学领域的知识发现中。最后，我们讨论了与代理自我进化技术相关的安全问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Optimization Spaces and Dimensions for Self-evolution/section
自主代理的优化代表着一个复杂的挑战，涵盖了多个抽象层面。在本节中，我们首先将即时优化确立为基础层，之上涌现出三个不同的优化分支：代理工作流优化、工具优化和全面自主代理优化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Optimization Spaces and Dimensions for Self-evolution/section/0/text
1. 自主代理的优化涵盖了哪些抽象层面？这些抽象层面如何相互关联和影响？  2. 如何将即时优化作为基础层，从而推导出代理工作流优化、工具优化和全面自主代理优化这三个不同的优化分支？  3. 在自主代理的优化过程中，如何解决不同分支之间的复杂挑战？这些挑战可能会对代理的性能和效果产生怎样的影响？
自主代理的优化代表着一个复杂的挑战，涵盖了多个抽象层面。在本节中，我们首先将即时优化确立为基础层，之上涌现出三个不同的优化分支：代理工作流优化、工具优化和全面自主代理优化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.1 Overview of Agent Optimization/section
在智能代理优化的两层架构中，基础层面是提示优化，强调增强语言模型节点的基本交互模式。随后出现三个并行分支：工作流水平优化关注LM节点之间的协调与交互，工具优化通过开发工具适应新任务并利用过去数据进化，全面自主代理优化通过多维度增强代理能力。智能代理优化可分为单目标或多目标，主要关注性能、推理成本和延迟。不同优化模式下的目标可能有所不同，如在提示级别优化中，提示长度可能成为额外目标。这种多方面优化目标的性质反映了代理系统的复杂性和平衡竞争需求的必要性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.1 Overview of Agent Optimization/section/0/text
1. 在基于LLM的智能代理优化中，为什么要将优化过程分为工作流水平优化、工具优化和全面自主代理优化三个并行分支？这三个分支各自的优势和作用是什么？  2. 在智能代理优化中，单目标和多目标优化有何区别？如何在不同的优化模式下权衡性能、推理成本和延迟等因素？  3. 提到在不同优化模式下可能会有不同的目标，以提示级别优化为例，为什么提示长度可能成为额外的优化目标？这种多方面优化目标对代理系统的复杂性和竞争需求有何影响？
现有基于LLM的智能代理优化可以在一个两层架构中进行概念化。在基础层面上是提示优化，专注于增强语言模型节点的基本交互模式。在此基础上，出现了三个并行分支：i) 工作流水平优化，重点关注多个LM节点之间的协调和交互模式；ii) 工具优化，代理通过开发和改进工具来适应新任务并利用过去的数据而进化；iii) 全面自主代理优化，旨在通过考虑多个维度来全面增强代理的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.1 Overview of Agent Optimization/section/1/text
1. 智能代理优化中的单目标和多目标范式各有何特点？它们如何影响代理系统的性能和效率？ 2. 性能、推理成本和延迟在智能代理优化中扮演怎样的角色？这三个度量标准如何相互影响，以及如何根据具体情况进行权衡和优化？ 3. 在智能代理优化中，如何根据具体的优化模式来调整不同的优化目标？提示级别优化中的额外约束条件对整体优化过程有何影响？
类似于AutoML中的优化范式，智能代理优化可以被归类为单目标或多目标。当代智能代理优化主要集中在三个经典的度量标准上：性能、推理成本和延迟。性能衡量了代理完成其指定任务的有效性，而推理成本则量化了代理运行所需的计算资源。延迟表示代理响应并完成任务所花费的时间。这些目标根据具体的优化模式可能会有所不同。例如，在提示级别的优化中，额外的约束条件，如提示长度，可能成为相关的目标。这种多方面的优化目标的性质反映了代理系统的复杂性以及平衡多个竞争需求的必要性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/section
在大型语言模型(LLMs)基于代理的优化中，提示优化在提升代理性能、延迟和成本方面扮演着关键角色。通过生成任务特定的提示，最大化性能表现。优化函数通过改进现有提示，执行函数调用当前提示以获取输出，评估函数评估输出生成评估信号和优化信号。评估函数在提示优化中起着关键作用，协调评估来源、方法和信号生成，包括LLM生成的输出和任务特定基准。优化函数则生成高质量输出，利用评估信号和优化信号指导迭代优化。各种评估方法提供多样化反馈形式，促进智能代理的持续学习和进化。评估指标跨维度评估优化方法的有效性，包括性能、效率和定性指标，帮助全面评估代理行为特征。提示优化框架为不同目标提供相应的评估指标，平衡性能和效率之间的权衡，推动代理系统实现更快收敛和更具见解的输出。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/section/0/text
1. 在大型语言模型(LLMs)基于代理的优化中，为什么提示优化被认为在提升代理性能、延迟和成本方面扮演着至关重要的角色？  2. 在给定一个任务$T=(Q,G_{t})$的情况下，任务特定的提示$P_{t}^{*}$是如何通过提示优化来最大化性能的？  3. 在评估函数在提示优化中的关键作用中，如何协调评估来源、方法和信号生成，以确保评估函数有效地指导优化函数生成高质量输出？
大型语言模型(LLMs)基于代理的优化中，提示优化在优化中起着至关重要的作用。在优化代理时，除了模型级别的优化之外，任务特定或模型特定的提示优化直接影响代理的性能、延迟和成本。给定一个任务$T=(Q,G_{t})$，其中$Q$表示输入查询，$G_{t}$代表可选的地面实况，提示优化的目标是生成一个任务特定的提示$P_{t}^{*}$，以最大化性能：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/section/1/formula
$$ 
P^{*}=\underset{P\in\mathcal{P}}{\arg\operatorname*{max}}\mathbb{E}_{T\sim\mathcal{D}}[\phi_{\mathrm{eval}}(\phi_{\mathrm{exe}}(Q,P),T)]
 $$
该公式的目的是在大型语言模型(LLMs)基于代理的优化过程中，通过最大化期望评估函数的输出来生成任务特定的提示，从而达到最大化性能的目标。公式中的符号和参数解释如下：$P^{*}$表示最佳提示，$\mathcal{P}$代表可能提示的空间，$T$表示任务，$\mathcal{D}$表示任务分布，$Q$表示输入查询，$P$表示提示，$\phi_{\mathrm{eval}}$表示评估函数，$\phi_{\mathrm{exe}}$表示执行函数。  设计该公式的动机在于通过优化提示来提高代理的性能，其中评估函数$\phi_{\mathrm{eval}}$和执行函数$\phi_{\mathrm{exe}}$起着关键作用。评估函数协调评估来源、方法和信号生成，帮助选择有效的提示；而执行函数则调用当前提示以获取输出，评估函数的输出会生成评估信号和优化信号，用于指导优化函数改进现有提示。  在论文中，该公式是提示优化框架中的关键部分，用于生成任务特定的提示以最大化性能。通过优化提示的方式，可以提高代理系统的性能、延迟和成本，促进智能代理的持续学习和进化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/section/2/text
1. 在大型语言模型基于代理的优化中，如何评估当前输出以生成评估信号和优化信号？这些信号如何影响优化函数的执行和提示的选择？  2. 优化函数、执行函数和评估函数在代理优化中的作用各是什么？它们是如何相互协作的，以实现更高质量的输出和更快的收敛？  3. 提示优化框架如何通过平衡性能和效率之间的权衡，推动代理系统实现更快收敛和更具见解的输出？
其中，$\mathcal{P}$代表可能提示的空间，$\phi_{\mathrm{exe}}$表示执行函数，$\phi_{\mathrm{eval}}$表示评估函数。这种优化通常通过三个基本函数实现：$\phi_{\mathrm{opt}}$、$\phi_{\mathrm{exe}}$和$\phi_{\mathrm{eval}}$。优化函数$\phi_{\mathrm{opt}}$根据优化信号改进现有提示，执行函数$\phi_{\mathrm{exe}}$调用当前提示以获取输出$O$，评估函数$\phi_{\mathrm{eval}}$评估当前输出以生成评估信号$S_{\mathrm{eval}}$和优化信号$S_{\mathrm{opt}}$。评估信号用于选择有效的提示，而优化信号则帮助优化函数执行优化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.1 Evaluation Functions/section
评估函数 $\phi_{eval}$ 在提示优化中扮演关键角色，通过协调评估来源、方法和信号生成，推动持续改进。评估来源包括LLM生成的输出$G_{llm}$和任务特定的基准$G_{t}$，评估方法分为基准评估、LLM作为评判者和人类反馈。基准评估依赖预定义规则提供数值反馈，而LLM作为评判者则根据任务描述和输出$G_{llm}$评估任务完成质量。人类反馈作为最高水平整合方式，显著提高了提示质量，但也带来显著资源开销。信号类型包括数值反馈、文本反馈和排名反馈，分别满足不同优化需求，提供量化性能、详细建议和相对质量排序。这些评估方法的应用为提示优化提供了多样化的反馈形式，促进了智能代理的持续学习和进化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.1 Evaluation Functions/section/0/text
1. 评估函数 $\phi_{eval}$ 如何在提示优化中协调评估来源、方法和信号生成，推动持续改进？   2. 人类反馈在提示优化中扮演怎样的角色？它如何显著提高了提示质量，同时又带来了怎样的资源开销？   3. 信号类型包括数值反馈、文本反馈和排名反馈，它们分别如何满足不同的优化需求，促进了智能代理的持续学习和进化？
在提示优化的核心是评估函数 $\phi_{eval}$，它作为导出优化信号和引导提示演化轨迹的基石。该函数在评估来源、方法论和信号生成之间进行复杂的协调，建立一个反馈循环，推动持续改进。评估函数 $\phi_{eval}$ 处理评估来源作为输入，并采用各种评估方法生成不同类型的信号，随后指导优化过程。在这里，我们定义了来源、方法和信号类型的维度，以建立提示优化的基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.1 Evaluation Functions/section/1/text
1. 评估函数在提示优化中的关键角色体现在哪些方面？基于不同评估来源和方法，如何推动持续改进？  2. 在提示优化中，基准评估、LLM作为评判者和人类反馈这三种评估方法各有何优缺点？如何在不同情境下选择最合适的评估方法？  3. 信号类型的多样化如何促进了智能代理的持续学习和进化？在实际应用中，如何根据具体优化需求选择合适的信号类型进行评估？
评估来源主要包括LLM生成的输出$G_{llm}$和任务特定的基准$G_{t}$。现有工作主要利用$G_{llm}$和$G_{t}$之间的比较作为评估来源。一些方法仅利用$G_{llm}$作为评估来源。例如，PROMPT通过将$G_{llm}$与人工设计的规则进行比较来评估提示的有效性；SPO则利用来自不同提示的输出的成对比较来确定相对有效性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.1 Evaluation Functions/section/2/text
1. 评估方法中的基准评估和LLM作为评判者各有哪些优缺点，以及它们在提示优化中的应用情况如何？  2. 人类反馈在评估方法中扮演着怎样的角色？它相较于基准评估和LLM作为评判者有何独特之处？  3. 在评估方法中，如何利用不同类型的信号（数值反馈、文本反馈和排名反馈）来满足不同的优化需求，并促进智能代理的持续学习和进化？
评估方法
评估方法可以大致分为三种方法：基准评估、LLM作为评判者和人类反馈。基准评估仍然是提示优化中最普遍的方法。这种方法依赖预定义的指标或规则来提供数值反馈作为评估信号。虽然它提供了自动化的评估过程，但其有效性最终取决于基准设计与人类偏好的一致性程度。

LLM作为评判者的引入代表了自动化评估和偏好对齐的重大进展。利用LLM与人类偏好的内在一致性和精心设计的评判标准，这种方法可以根据任务描述和提示输出$G_{llm}$来评估任务完成质量，提供反映性的文本梯度反馈。显著的实施包括ProteGi、TextGrad、Semantic Search和Revolve。此外，LLM作为评判者还可以通过特定评分机制在地面真相$G_{t}$和输出$G_{llm}$之间进行比较评估。这种方法的有效性取决于评判提示的设计以及基础模型与人类偏好的一致性。作为一种专门的扩展，Agent-as-a-Judge通过利用专门的代理人在复杂任务上提供过程评估，同时以显著降低的评估成本保持与人类偏好的高度一致性，进一步完善了这一范式。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.1 Evaluation Functions/section/3/text
1. 人类反馈在提示优化中扮演着重要角色，如何平衡人类反馈带来的质量提升与资源开销之间的矛盾？  2. APOHF[777]研究表明，整合人类反馈可以在最小计算资源下实现强大的提示优化，这种方法在哪些类型的任务中表现尤为突出？为什么？  3. 人类仍然是提示效果的最终裁决者，那么如何设计评估函数，以有效利用人类反馈的信息，推动智能代理的持续学习和进化？
人类反馈代表了评估过程中智能整合的最高水平。由于人类仍然是提示效果的最终裁决者，直接的人类反馈可以快速且显著地提高提示的质量。然而，这种方法引入了显著的资源开销。APOHF[777]表明，整合人类反馈可以在最小的计算资源下实现强大的提示优化，特别擅长于开放式任务，如用户指导、文本到图像生成模型的提示优化以及创意写作。然而，对人类干预的需求在一定程度上与自动演化的目标相矛盾。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.1 Evaluation Functions/section/4/text
1. 评估函数中的数值反馈方法在提示优化中的应用有哪些优势和局限性？如何平衡其广泛适用性和对特定实例细节的忽视可能性？  2. 文本反馈作为一种复杂方法，在提示设计中如何提供有针对性的改进指导？其对智能参与的依赖如何影响了可扩展性？  3. 排名反馈相较于其他反馈形式有何独特优势？在难以定义绝对度量或优化相对改进的情况下，如何有效应用排名反馈进行提示优化？
信号类型评估方法生成的反馈以三种明显形式呈现，每种形式都满足不同的优化需求。数值反馈通过标量度量指标量化性能，与规则、基准真相、人类评估和LLM判断兼容。虽然广泛适用，但这种方法需要大量样本以获得统计可靠性，可能忽视可指导优化的特定实例细节。文本反馈通过分析和具体建议提供详细的、特定实例的指导。这种复杂方法需要智能参与，可以是来自人类专家或先进语言模型，通过明确建议实现对提示设计的有针对性改进。然而，它对复杂智能来源的依赖影响了其可扩展性。排名反馈通过全面排名或成对比较建立相对质量排序。这种方法独特地避免了对绝对质量度量或预定义标准的需求，只需要偏好判断。当难以定义绝对度量或优化主要涉及相对改进时，这种方法尤为有价值。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.2 Optimization Functions/section
优化函数在每次提示优化迭代中生成高质量输出起着关键作用。评估信号$S_{eval}$和优化信号$S_{opt}$是当前优化方法的主要依赖。评估信号引导下的优化方法选择基于$\phi_{eval}$评估的最有效提示，如SPO和Evoprompt，利用语言模型的任务对齐能力进行迭代优化。优化信号引导下的方法，如OPRO和ProTegi，提取共同模式或分析失败案例以指导优化方向，而TextGrad和Revolve进一步扩展了这一思路，通过“文本梯度”和模拟二阶优化提高效率和长期任务性能改进。这些方法在提示优化中展示了不同的指导方式，推动自我演化系统实现更快收敛和更具见解的输出。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.2 Optimization Functions/section/0/text
1. 评估信号引导下的优化方法如SPO和Evoprompt是如何选择最有效提示并进行迭代优化的？ 2. 优化信号引导下的方法，如OPRO和ProTegi，是如何利用共同模式或分析失败案例指导优化方向的？ 3. TextGrad和Revolve是如何通过“文本梯度”和模拟二阶优化提高效率和长期任务性能改进的？
优化函数的设计在确定每次提示优化迭代中生成质量的关键作用。通过有效的信号引导，提示自我演化可以实现更快的收敛。当前的优化方法主要依赖于两种类型的信号：评估信号$S_{eval}$，用于识别最有效的现有提示，以及优化信号$S_{opt}$，提供改进的详细指导。

通过评估信号进行优化时，该过程从基于$\phi_{eval}$评估的最有效提示的选择开始。一些方法采用启发式探索和优化策略，而非直接从过去的错误中学习。SPO[778]根据当前表现最佳提示的输出迭代地优化提示，利用语言模型固有的与任务要求对齐的能力。类似地，Evoprompt[723]采用进化算法，LLMs作为启发式提示组合的进化操作符。PromptBreeder[732]通过比较变异提示之间的分数变化，同时通过LLM的固有能力修改元提示和提示，进一步推进了这种方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.2 Optimization Functions/section/1/text
1. 在优化信号的指导下进行优化与仅基于评估信号的优化方法相比，其优势在哪里？如何利用明确的优化信号来提高效率和指导优化方向？  2. 不同的方法（如OPRO、ProTegi、TextGrad和Revolve）是如何利用优化信号来指导优化方向的？它们在优化过程中如何提取共同模式、分析失败案例或模拟二阶优化，以实现更快收敛和更具见解的输出？  3. 通过对比评估信号引导和优化信号引导的优化方法，我们如何评价在提示优化中展现的不同指导方式对系统收敛速度和输出质量的影响？
在优化信号的指导下进行优化 虽然仅基于评估信号的优化方法需要进行广泛搜索以在庞大的搜索空间中找到最佳解决方案，但另一种方法利用明确的优化信号来引导优化方向并提高效率。现有方法展示了利用这些优化信号的各种方式。OPRO[730]从高性能提示解决方案中提取共同模式，以指导后续优化步骤。ProTegi[779]采用语言模型来分析失败案例并预测错误原因，利用这些见解作为优化指导。TextGrad[728]进一步扩展了这一方法，将提示反映转化为“文本梯度”，将这一指导应用于代理系统中的多个提示。Revolve[780]通过模拟二阶优化进一步增强了优化，将先前的一阶反馈机制扩展为建模连续提示和响应之间不断演变关系的方式。这使系统能够根据先前梯度的变化进行调整，避免停滞在次优模式中，并实现更具见解的、长期的复杂任务性能改进。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.3 Evaluation Metrics/section
评估指标对优化方法的有效性进行跨维度评估。CloseTasks的性能指标是最直接的，包括通过率@1、准确性、F1分数和ROUGE-L等指标，评估提示优化的稳定性和有效性。效率指标也是关键维度，一些方法取得出色结果但需要大量计算资源，而其他方法在资源需求较低情况下取得中等结果，凸显了性能和效率之间的权衡。定性指标关注评估代理行为特定方面，如一致性、公平性和信心，提供了评估代理行为的定性指标。提示优化框架为不同目标提供相应的评估指标，有助于全面评估代理的行为特征。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.2 Prompt Optimization/9.2.3 Evaluation Metrics/section/0/text
1. 如何利用CloseTasks的性能指标来评估提示优化方法的稳定性、有效性和收敛速度？  2. 在提示优化方法中，如何权衡性能和效率之间的关系，以及如何衡量不同方法在资源需求和结果表现之间的平衡？  3. 定性指标在评估代理行为特定方面时起到什么作用，如何利用一致性、公平性和信心等指标来全面评估代理的行为特征？
可以评估提示优化方法的有效性，跨多个维度进行评估。对于CloseTasks的性能指标[782,778,730]作为提示固有性能的最直接指标，包括通过率@1、准确性、F1分数和ROUGE-L等指标。这些指标使研究人员能够评估提示优化过程的稳定性、有效性和收敛速度。另一个关键维度是效率指标[778]。虽然一些提示优化方法取得了出色的结果，但它们通常需要大量的计算资源、更大的样本量和广泛的数据集。相反，其他方法在资源需求较低的情况下取得了中等结果，突显了代理演化中性能和效率之间的权衡。第三个维度关注评估代理行为特定方面的定性指标：一致性[776]衡量了多次运行中输出的稳定性，公平性[783]评估了减轻语言模型固有偏见的能力，信心[784,785]量化了代理对其预测的确定性。当将这些行为方面视为不同的目标时，提示优化框架提供相应的评估指标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/section
在"工作流优化"章节中，探讨了智能工作流空间的重要性，特别是在协调多个LLM组件以解决复杂任务时的作用。智能工作流通过节点的协议操作实现优化目标，与完全自主的多代理系统有所区别。通过形式化定义智能工作流和优化目标，研究了节点和边缘的核心组件，分析了它们的搜索空间和表示方法。子章节"工作流程制定"详细描述了工作流的节点和边的集合，以及优化目标的重要性，强调在任务完成质量和计算效率之间取得平衡。而"优化工作流边缘"则介绍了不同表示形式（图形、神经网络、代码）对搜索空间和优化算法的影响，为工作流的优化提供了多样化的选择。最后，"优化工作流节点"重点讨论了节点空间$N$、输出格式空间$F$、温度参数$\tau$和提示空间$P$的关键维度，强调了节点空间优化面临的可扩展性挑战，需要有效的策略来处理大规模节点的优化问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/section/0/text
1. 智能工作流空间相较于完全自主的多代理系统有何不同之处，以及这种区别对于解决复杂任务的影响是什么？  2. 在智能工作流中，节点如何根据预定的协议和优化目标操作，与展示自主决策能力的完全自主多代理系统有何区别？  3. 对于提升专门任务完成和一般代理能力，智能工作流在现代人工智能系统中扮演着怎样的关键角色？
尽管在增强单个LLM能力方面，提示级别的优化显示出了令人鼓舞的结果，但现代人工智能系统通常需要协调多个LLM组件来解决复杂任务。这需要一个更全面的优化领域——智能工作流空间。在其核心，智能工作流包括LLM调用节点，其中每个节点代表专门设计用于较大系统中特定子任务的LLM组件。

尽管这种架构与多代理系统相似，但重要的是要将智能工作流与完全自主的多代理情景区分开来。在智能工作流中，节点根据预定的协议和优化目标操作，而不是展示自主决策能力。许多著名系统，如MetaGPT[626]和AlphaCodium[786]，可以归类为这种框架。此外，智能工作流可以作为更大的自主代理系统中的可执行组件，使它们的优化对于推进专门任务完成和一般代理能力的发展至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/section/1/text
1. 智能工作流的形式化定义对于解决复杂任务有何重要意义，与完全自主的多代理系统相比有何区别？  2. 在智能工作流中，节点和边缘作为核心组件分别具有怎样的搜索空间？这种搜索空间的分析如何有助于优化目标的实现？  3. 不同的表示形式（如图形、神经网络、代码）对智能工作流的搜索空间和优化算法有何影响？这种多样化的选择如何促进工作流的优化？
在GPTSwarm[651]和AFLOW[773]提出的形式化基础上，本节首先建立了智能工作流及其优化目标的形式化定义。然后，我们将研究智能工作流的核心组件——节点和边缘——分析它们各自的搜索空间，并讨论文献中现有的表示方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.1 Workflow Formulation/section
在"工作流程制定"章节中，代理工作流被形式化表示为一个包含节点和边的集合。节点包括调用LLM节点所需的语言模型、温度参数、提示空间和输出格式空间，而边表示不同LLM调用节点之间的联系。工作流的优化目标是找到最优工作流，以最大化性能指标，如任务完成质量、计算效率和执行延迟。这种优化反映了在实际部署代理工作流时需要在效果和资源约束之间取得平衡的挑战。通过工作流的结构组件和操作参数，实现了代理工作流行为的定义和优化，以提高代理系统的整体性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.1 Workflow Formulation/section/0/text
1. 代理工作流的形式化表示中，节点和边分别代表什么内容，它们之间的联系如何体现代理工作流的执行过程？  2. 优化一个代理工作流的目标是什么？在实际部署代理工作流时，为什么需要在效果和资源约束之间取得平衡？  3. 通过对代理工作流的结构组件和操作参数进行定义和优化，如何可以提高代理系统的整体性能？
一个代理工作流 $\kappa$ 可以形式化表示为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.1 Workflow Formulation/section/1/formula
$$ 
\mathcal{K}=\{(N,E)|N\in\mathcal{N},E\in\mathcal{E}\}
 $$
这个公式表示了代理工作流 $\mathcal{K}$ 的形式化表示，其中 $\mathcal{K}$ 是由节点集合 $N$ 和边集合 $E$ 组成的。在这里，$N$ 表示节点集合，$E$ 表示边集合。  具体地，节点集合 $N$ 可以表示为 $N = \{N(M,\tau,P,F) | M \in \mathcal{M}, \tau \in [0,1], P \in \mathcal{P}, F \in \mathcal{F}\}$，其中： - $M$ 代表可用的语言模型； - $\tau$ 代表温度参数，其取值范围在 0 到 1 之间； - $P$ 代表提示空间； - $F$ 代表输出格式空间。  而 $E$ 则表示不同LLM调用节点之间的边。这种形式化表示包含了定义代理工作流行为的结构组件和操作参数，有助于理解代理工作流的组成和关系。  在论文中，这个公式的作用是描述了如何将代理工作流形式化表示为节点和边的集合，通过节点的语言模型、温度参数、提示空间和输出格式空间以及节点之间的联系来定义代理工作流的行为。这有助于优化工作流，使其达到最大化性能指标的目标，如任务完成质量、计算效率和执行延迟。通过对工作流的结构组件和操作参数进行形式化表示，可以更好地理解和优化代理系统的整体性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.1 Workflow Formulation/section/2/text
1. 代理工作流中的节点和边是如何定义的？它们分别代表了什么内容和关系？  2. 在工作流优化中，为什么需要在任务完成质量、计算效率和执行延迟之间取得平衡？这种平衡对代理系统的整体性能有何重要性？  3. 如何通过调整工作流的结构组件和操作参数来实现代理工作流行为的定义和优化？这种优化如何有助于提高代理系统的性能？
其中$\mathcal{N}=\{N(M,\tau,P,F)|M\in\mathcal{M},\tau\in[0,1],P\in\mathcal{P},F\in\mathcal{F}\}$代表了调用LLM节点的集合，其中$M$，$\tau$，$\mathcal{P}$和$\mathcal{F}$分别表示可用的语言模型、温度参数、提示空间和输出格式空间。$E$表示不同LLM调用节点之间的边。这种表述包含了定义代理工作流行为的结构组件和操作参数。

给定一个任务$T$和评估指标$L$，工作流优化的目标是发现最大化性能的最优工作流$K^{*}$：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.1 Workflow Formulation/section/3/formula
$$ 
K^{*}=\underset{K\in\mathcal{K}}{\arg\operatorname*{max}}L(K,T)
 $$
这个公式表示工作流优化的目标，即寻找最大化性能指标的最优工作流$K^{*}$。在这里，$K^{*}$是一个使性能指标$L(K,T)$取得最大值的工作流。$K$表示工作流的搜索空间，即所有可能的工作流集合。$L(K,T)$是评估指标，用于衡量工作流$K$在任务$T$上的性能。通常，这个性能指标会考虑任务完成质量、计算效率和执行延迟等方面。这个优化目标反映了在实际部署代理工作流时需要在性能和资源约束之间取得平衡的挑战。通过找到最优工作流，可以提高代理系统的整体性能，使其在效果和资源利用之间取得平衡。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.1 Workflow Formulation/section/4/text
1. 如何通过$L(K,T)$来衡量代理工作流的多个方面，包括任务完成质量、计算效率和执行延迟？这种衡量方式对于优化工作流有何意义？  2. 在实际部署代理工作流时，为什么需要在效果和资源约束之间取得平衡？这种平衡对于提高代理系统整体性能有何重要性？  3. 代理工作流的搜索空间$K$在优化工作流中扮演着怎样的角色？$L(K,T)$如何帮助反映实际部署代理工作流时所面临的挑战？
其中$K$是工作流的搜索空间，$L(K,T)$通常衡量多个方面，包括任务完成质量、计算效率和执行延迟。这种优化目标反映了在部署代理工作流时面临的实际挑战，我们必须在效果和资源约束之间取得平衡。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.2 Optimizing Workflow Edges/section
本节讨论了优化工作流边缘空间的表示形式，包括基于图形、神经网络和代码结构的三种范式。基于图形的表示适用于表达节点间的层次、顺序和并行关系，特别擅长处理复杂分支模式，如GPTSwarm展示了其在协调多个LLM组件方面的有效性。神经网络架构则能捕捉非线性关系，如Dylan表明其在需要动态调整的场景中表现出色。基于代码的表示提供了最全面的表达性，支持线性序列、条件逻辑、循环以及图形和网络结构的整合，如AFLOW和ADAS展示了其精确控制工作流执行的能力。不同表示形式的选择影响了搜索空间维度和适用的优化算法，如即时优化技术、强化学习算法以及针对特定问题的拓扑优化方法。这些方法为工作流的优化提供了多样化的选择，有助于提升智能代理系统的性能和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.2 Optimizing Workflow Edges/section/0/text
1. 不同的工作流表示形式（基于图形、神经网络、代码结构）各有何优势和适用场景？如何根据具体需求选择最合适的表示形式？  2. 如何评价基于图形的表示形式在处理复杂分支模式和协调多个组件方面的有效性？基于神经网络的工作流表示又是如何实现动态调整和自适应行为的？  3. 基于代码的工作流表示提供了最全面的表达性，能够支持哪些结构和功能？AFLOW和ADAS是如何展示这种表示形式对工作流执行的精确控制能力的？
边缘空间 $\mathcal{E}$ 定义了智能工作流的表示形式。目前的方法主要采用三种不同的表示范式：基于图形、基于神经网络和基于代码结构。每种范式都具有独特的优势，并对优化过程引入特定的约束。

基于图形的表示使得节点之间的层次、顺序和并行关系得以表达。这种方法自然地适应复杂的分支模式，并便于可视化工作流拓扑结构，特别适用于需要明确结构操作的场景。例如，GPTSwarm[651] 在通过具有拓扑感知优化的图形化工作流表示协调多个LLM组件方面展示了其有效性。神经网络架构提供了另一种强大的表示范式，擅长捕捉节点之间的非线性关系。Dylan [725] 表明，基于神经网络的工作流通过可学习参数可以表现出自适应行为，因此在需要根据输入和反馈进行动态调整的场景中特别有效。基于代码的表示在当前方法中提供了最全面的表达性。AFLOW[773] 和 ADAS[741] 显示，将工作流表示为可执行代码支持线性序列、条件逻辑、循环以及图形和网络结构的整合。这种方法可以精确控制工作流的执行，并利用LLMs固有的代码生成能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.2 Optimizing Workflow Edges/section/1/text
1. 不同边缘空间表示形式对搜索空间维度和适用的优化算法有何影响？这种影响如何体现在即时优化、强化学习算法和针对特定问题的拓扑优化方法上？  2. 在工作流优化中，如何利用基于图形、神经网络和代码结构的表示形式来提升智能代理系统的性能和效率？这三种表示形式各自的优势和局限性是什么？  3. 在文中提到的即时优化、强化学习算法和基于代码的表示形式中，哪一种方法更适合于需要动态调整的场景？它们分别如何应对固定工作流拓扑结构和特定问题的拓扑优化需求？
边缘空间表示形式的选择显著影响了搜索空间的维度和适用的优化算法。[728] 专注于即时优化，同时保持固定的工作流拓扑结构，从而可以利用基于文本反馈的优化技术。相比之下，[651] 开发了强化学习算法，用于联合优化单个节点提示和整体拓扑结构。[773] 利用基于代码的表示形式，通过语言模型直接实现工作流优化，而[787] 和 [788] 的最新进展则引入了针对特定问题的拓扑优化方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.3 Optimizing Workflow Nodes/section
在优化工作流节点中，节点空间$N$、输出格式空间$F$、温度参数$\tau$和提示空间$P$是影响节点行为和性能的关键维度。节点优化研究主要集中在特定维度上，如提示优化、提示和温度参数的组合，以及跨不同节点的模型选择。然而，输出格式空间的优化尚未得到充分探讨。与边缘空间优化相比，节点空间优化面临着可扩展性挑战，因为代理工作流程中存在大量节点，导致搜索空间的维度呈指数增长。有效的优化策略需要应对这种复杂性，确保在保持合理计算成本的同时处理大规模节点的优化问题。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.3 Optimizing Workflow Nodes/section/0/text
1. 在节点优化研究中，为什么输出格式空间的优化尚未得到充分探讨？输出格式空间对节点性能的影响体现在哪些方面？  2. 面对节点空间优化的可扩展性挑战，为什么有效的优化策略需要处理搜索空间维度的指数增长？如何确保在处理大规模节点的优化问题时保持合理的计算成本？  3. 提示空间$P$如何影响与LLMs的核心交互模式？提示空间$P$的设计如何与节点行为和性能密切相关？
节点空间$N$包含四个关键维度，影响节点行为和性能。输出格式空间$F$通过构建LLMs的输出格式，如XML和JSON，显著影响性能，使响应结构更具精确控制。温度参数$\tau$控制输出的随机性，影响节点响应中稳定性与创造性的权衡。提示空间$P$继承了来自提示级别优化的优化领域，决定了与LLMs的核心交互模式。模型空间$M$代表可用的LLMs，每个LLM都具有独特的能力和计算成本。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.3 Workflow Optimization/9.3.3 Optimizing Workflow Nodes/section/1/text
1. 在节点优化研究中，为什么输出格式空间的优化相对未被深入探讨？这种局面可能对节点性能和行为产生怎样的影响？  2. 节点空间优化与边缘空间优化相比，面临着怎样的可扩展性挑战？如何设计有效的优化策略来处理大规模节点的优化问题，同时保持合理的计算成本？  3. 在节点优化研究中，专注于特定维度如提示优化、提示与温度参数的组合以及跨不同节点的模型选择，这种局限性可能会如何影响对整个节点空间的优化效果和全局性能提升？
针对单节点优化，现有研究主要集中在该空间内的特定维度上。[773] 专注于提示优化，而[741] 将搜索空间扩展到包括提示和温度参数。采用不同方法，[789] 固定提示同时探索跨不同节点的模型选择。尽管输出格式优化至关重要，但仍相对未被深入探讨。

与边缘空间优化相比，节点空间优化由于代理工作流程中通常存在大量节点，面临独特的可扩展性挑战。随着每个额外节点的增加，搜索空间的维度呈乘法增长，需要高效的优化策略，能够有效处理这种复杂性同时保持合理的计算成本。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/section
在工具优化领域，智能代理通过先进的多轮规划和与外部世界互动的能力，实现了更高性能和适应性。优化工具使用是提升代理整体性能的关键，涉及评估和完善代理选择、调用和整合工具的方式。关键性能指标包括决策准确性、检索效率、选择精度和任务规划。工具学习和工具创建是两种重要的优化策略。学习使用工具包括基于示范和反馈学习，强化系统的泛化工具使用能力。新工具的创建则通过动态创造工具，如ToolMakers、CREATOR和CRAFT方法，增强了智能代理框架的适应性和效率。工具效果评估章节通过各种基准和框架，如Gorilla、T-Bench和ToolEyes，为量化代理工具使用能力提供了基础，强调了决策准确性、检索效率、选择精度和任务规划的重要性。综合考虑各方面因素，优化工具性能能够提高工具辅助机器学习工作流程的效果和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/section/0/text
1. 工具学习和工具创建在优化工具使用过程中的作用有何不同？它们如何相互补充，共同提高代理整体性能和适应性？ 2. 除了决策准确性、检索效率、选择精度和任务规划，还有哪些因素可能影响优化工具的性能？这些因素如何在工具优化过程中被考虑和权衡？ 3. 如何利用工具效果评估章节中提到的基准和框架，如Gorilla、T-Bench和ToolEyes，来量化代理工具使用能力？这些评估方法如何帮助提升工具辅助机器学习工作流程的效果和效率？
与通常单轮操作LLMs的传统用法不同，代理配备了先进的多轮规划能力，并具有通过各种工具与外部世界进行交互的能力。这些独特的特性使得优化工具使用成为增强代理整体性能和适应性的关键组成部分。工具优化涉及系统地评估和完善代理如何选择、调用和整合可用工具以更高效、更低延迟地解决问题。在这一背景下，关键的性能指标包括决策准确性、检索效率、选择精度、任务规划和风险管理。在这一优化过程中，两种互补策略至关重要：工具学习和工具创建。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.1 Learning to Use Tools/section
在学习使用工具方面，基于示范的学习和反馈学习为支持LLM代理的模型提供了重要方法。基于示范的学习通过模仿专家行为，利用行为克隆等技术实现监督学习策略优化。反馈学习则通过强化学习，根据环境或人类反馈的奖励调整模型。整合这两种学习方法增强了系统的泛化工具使用能力，迭代改进工具调用和执行策略。优化模型需要结合先进的检索模型、推理策略和自适应学习机制，如思维链、思维树和DFS-DT，以促进更复杂的决策过程，并通过模型输出学习实现更好的后处理和分析，提升工具利用效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.1 Learning to Use Tools/section/0/text
1. 基于示范的学习和反馈学习在支持LLM代理的模型中的应用有何优势和局限性？   2. 如何利用基于示范的学习方法训练支持LLM代理的模型，以实现通过模仿学习专家行为来优化模型？  3. 如何通过基于示范的学习方法中的行为克隆等技术，实现模型对人类示范的监督学习策略的优化？
与基于提示的方法不同，利用冻结的基础模型在上下文学习能力方面，基于训练的方法通过监督来优化支持LLM代理的模型。受发展心理学启发，基于示范的学习可以分为两个主要流派：从示范学习和从反馈学习中学习。利用基于示范的学习方法训练支持LLM代理的模型，通过模仿学习专家行为。诸如行为克隆等技术使模型能够通过复制人类注释的工具使用动作以监督方式学习策略。形式上，给定数据集 $D=\{(q_{i},a_{i}^{*})\}_{i=0}^{N-1}$，其中 $q_{i}$ 是用户查询，$a_{i}^{*}$ 是相应的人类示范，控制器的参数 $\theta_{C}$ 被优化为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.1 Learning to Use Tools/section/1/formula
$$ 
\theta_{C}^{*}=\arg\operatorname*{max}_{\theta_{C}}\mathbb{E}_{(q_{i},a_{i}^{*})\in D}\prod_{t=0}^{T_{i}}p_{\theta_{C}}(a_{i,t}^{*}\mid x_{i,t},H_{i,t},q_{i})
 $$
这个公式的设计旨在优化控制器参数 $\theta_{C}$，以支持LLM代理的模型通过基于示范的学习方法进行训练。在给定数据集 $D=\{(q_{i},a_{i}^{*})\}_{i=0}^{N-1}$ 中，其中 $q_{i}$ 是用户查询，$a_{i}^{*}$ 是相应的人类示范，公式的目标是最大化期望值 $\mathbb{E}_{(q_{i},a_{i}^{*})\in D}$，即在数据集 $D$ 中对每个查询 $q_{i}$ 和相应的人类示范 $a_{i}^{*}$ 的期望。在给定的时间步 $t$ 中，公式中的 $a_{i,t}^{*}$ 表示查询 $q_{i}$ 在时间步 $t$ 的人类标注，$T_{i}$ 是总时间步数。公式中的 $p_{\theta_{C}}(a_{i,t}^{*}\mid x_{i,t},H_{i,t},q_{i})$ 则表示在给定输入特征 $x_{i,t}$、历史信息 $H_{i,t}$ 和查询 $q_{i}$ 的情况下，控制器生成人类示范 $a_{i,t}^{*}$ 的概率。因此，通过最大化这个概率的乘积，控制器参数 $\theta_{C}$ 可以被优化，以使模型更好地学习并适应人类示范的策略。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.1 Learning to Use Tools/section/2/text
1. 控制器参数 $\theta_{C}$ 的优化目标是什么？   2. 如何通过反馈学习中的强化学习来实现模型根据奖励进行调整？  3. 如何整合先进的检索模型、推理策略和自适应学习机制来促进更复杂的决策过程？
其中 $a_{i,t}^{*}$ 是查询 $q_{i}$ 在时间步 $t$ 的人类标注，$T_{i}$ 是时间步的总数。

从反馈学习中学习利用强化学习，使模型能够根据来自环境或人类反馈的奖励进行调整。控制器参数 $\theta_{C}$ 的优化目标是：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.1 Learning to Use Tools/section/3/formula
$$ 
\theta_{C}^{*}=\arg\operatorname*{max}_{\theta_{C}}\mathbb{E}_{q_{i}\in Q}\mathbb{E}_{\{a_{i,t}\}_{t=0}^{T_{i}}}\left[R\left(\{a_{i,t}\}_{t=0}^{T_{i}}\right)\right]
 $$
这个公式的目标是优化控制器参数 $\theta_{C}$，使得在给定查询 $q_{i}$ 的情况下，通过最大化期望奖励 $\mathbb{E}_{\{a_{i,t}\}_{t=0}^{T_{i}}}\left[R\left(\{a_{i,t}\}_{t=0}^{T_{i}}\right)\right]$ 来调整控制器参数。在这里，$\{a_{i,t}\}_{t=0}^{T_{i}}$ 表示时间步 $t$ 的动作序列，$R$ 代表基于动作序列的奖励函数。公式中的 $\mathbb{E}_{q_{i}\in Q}$ 表示对所有可能的查询 $q_{i}$ 进行期望，$\mathbb{E}_{\{a_{i,t}\}_{t=0}^{T_{i}}}$ 表示对所有可能的动作序列进行期望。  这个公式的作用是通过最大化期望奖励来调整控制器参数，以使LLM代理在给定查询情况下能够获得最大的奖励，从而提高其能力和性能。在论文中，这个公式是用来优化控制器参数，以增强系统在不同任务和环境中的泛化工具使用能力，进一步改进工具调用策略、选择策略和执行准确性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.1 Learning to Use Tools/section/4/text
1. 如何通过结合基于演示和基于反馈的学习来迭代改进工具调用策略、选择策略和执行准确性，从而增强系统在不同任务和环境中的泛化工具使用能力？  2. 在优化LLM代理的能力时，为什么需要结合先进的检索模型、精细调节的推理策略和自适应学习机制？这些因素如何促进更复杂的决策过程和更精确有效的工具交互？  3. 如何通过从模型的输出中学习实现更好的后处理和分析，以提升工具利用效率？
其中 $R$ 代表基于动作序列 $\{a_{i,t}\}$ 的奖励函数。

将工具学习整合到优化框架中增强了系统在不同任务和环境中泛化工具使用能力。通过结合基于演示和基于反馈的学习，模型可以迭代改进其工具调用策略、选择策略和执行准确性。

为了优化上述指标以提高LLM代理的能力，需要结合先进的检索模型、精细调节的推理策略和自适应学习机制。推理策略，如思维链 (CoT) [46]、思维树 [72] 和深度优先搜索决策树 (DFS-DT) [690]，促进了关于工具使用的更复杂的决策过程。通过优化模型对工具的理解，包括参数解释和动作执行，可以实现更精确和有效的工具交互。此外，从模型的输出中学习可以实现更好的后处理和分析，进一步提升工具利用效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.2 Creation of New Tools/section
在新工具的创建方面，除了优化现有工具外，动态创造新工具可以显著增强LLM智能代理框架的适应性和效率。近期工作提出了几种互补方法：ToolMakers采用闭环框架，通过三个阶段制造工具；CREATOR采用四阶段生命周期，强调工具多样性和错误恢复机制；CRAFT采用离线范式，将领域特定数据提炼为可重复使用的原子工具。这些方法的整合为混合系统提供了研究机会，可能实现多层工具层次结构，自监督工具评估指标和跨领域泛化的进展可能进一步自动化工具生命周期。未来的研究可关注工具粒度和可重复使用模式的相互作用，以实现灵活的组合和自我改进的人工智能系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.2 Creation of New Tools/section/0/text
1. 如何通过ToolMakers的闭环框架中的三个阶段制造工具，实现可靠性和全自动化，并如何确保工具的有效性和适应性？    2. 在CREATOR的四阶段生命周期中，如何通过抽象推理创建特定任务的工具、决策规划工具调用以及执行生成的程序，实现工具多样性、抽象/具体推理的分离和错误恢复机制的纠正？  3. CRAFT采用的离线范式如何通过GPT-4提示、验证和去重将领域特定数据提炼为可重复使用的原子工具，并如何实现可解释的工具链，避免模型微调，特别适用于将复杂任务分解为模块化步骤？
除了优化现有工具之外，基于对任务和当前工具使用的深刻理解，动态地创造新工具可以显著增强LLM智能代理框架的适应性和效率。在最近的工作中，提出了几种互补的方法。ToolMakers建立了一个闭环框架，其中一个制造工具的代理通过三个演示迭代地执行三个阶段：（1）通过示范进行编程示范提出Python函数，（2）通过自动化单元测试验证功能（3个验证样本）并进行自我调试测试用例，（3）为下游任务包装经验证的工具并提供使用演示。这一严格的过程确保了可靠性同时保持了全自动化。CREATOR采用了四阶段生命周期：通过抽象推理创建特定任务的工具，决策规划工具调用，执行生成的程序，通过迭代工具细化强调工具多样性、抽象/具体推理的分离和错误恢复机制的纠正。相比之下，CRAFT采用了离线范式，通过GPT-4提示、验证和去重将领域特定数据提炼为可重复使用的原子工具（例如对象颜色检测）。其无需训练的方法将人可检查的代码片段与组合问题解决相结合，实现可解释的工具链，同时避免模型微调，特别适用于将复杂任务分解为模块化步骤时。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.2 Creation of New Tools/section/1/text
1. 如何将CRAFT的预制工具库与ToolMakers的按需生成相结合，利用功能缓存来平衡效率和适应性，从而实现多层工具层次结构和自监督工具评估指标的进展？  2. 工具粒度（原子 vs. 复合）和可重复使用模式之间的相互作用对于实现灵活的组合和自我改进的人工智能系统有何重要性，如何进行系统研究以解决细粒度工具可能增加的编排复杂性问题？  3. 未来人工智能系统中可能出现的双向工具-任务相互适应机制如何促进工具创新和任务表示的重塑，从而最终实现自我改进的人工智能系统？
这些互补方法的整合为丰富的研究机会提供了可能。混合系统可以将CRAFT的预制工具库与ToolMakers的按需生成相结合，利用功能缓存来平衡效率和适应性。未来的框架可能实现多层工具层次结构，其中来自CRAFT的基本操作输入到ToolMakers的复合工具中，而CREATOR风格的纠正处理边缘情况。自监督工具评估指标和跨领域泛化的进展可能进一步自动化工具生命周期。值得注意的是，工具粒度（原子 vs. 复合）和可重复使用模式之间的相互作用需要进行系统研究，细粒度工具可以实现灵活的组合，但会增加编排复杂性。随着代理的发展，双向工具-任务相互适应机制可能会出现，其中工具重塑任务表示，而新任务推动工具创新，最终实现自我改进的人工智能系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section
在"工具效果评估"章节中，通过评估工具调用、选择准确性、检索效率和复杂任务规划等方面的基准和指标，为量化代理工具使用能力提供了全面的基础。各种基准和框架如Gorilla、T-Bench和ToolEyes等不断推动工具增强LLM研究的发展，从孤立推理任务向全面的代理评估转变。工具调用的度量标准和决策规则，以及工具选择准确率的评估，帮助系统确定是否需要调用外部工具以及选择最合适的工具。此外，工具检索效率和层次准确性的评估通过层次框架区分检索准确性和选择准确性，强调了系统精确检索正确工具和选择最佳工具的能力。复杂任务的工具规划方面，通过平衡任务效果和计划复杂性来评估规划质量，强调了行为规划的重要性，提供了对模型规划能力的整体度量。综合而言，优化工具性能需要综合考虑决策准确性、检索效率、层次选择精度、战略规划和强大的工具学习机制，以提高工具辅助机器学习工作流程的效果和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/0/text
1. 评估指标和基准如何为量化代理工具使用能力提供全面基础？这些基准如何在优化工具使用过程中发挥作用？ 2. 代理工具使用基准的演变如何影响工具的即时性能提升和长期战略改进？这些基准如何帮助确定进一步工具优化的关键评估指标？ 3. 在工具调用、选择准确性、检索效率和复杂任务规划等方面的评估中，哪些指标对于提高工具辅助机器学习工作流程的效果和效率至关重要？
下面讨论的评估指标和基准为量化代理工具使用能力提供了全面的基础。通过评估工具调用、选择准确性、检索效率和复杂任务规划等方面，这些基准不仅衡量当前性能，而且为优化工具使用提供了明确的具体目标。这些指标在引导代理系统的即时性能提升和长期战略改进方面起着重要作用。在接下来的几节中，我们首先回顾了代理工具使用基准的演变，然后整合了作为进一步工具优化目标的关键评估指标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/1/text
1. 不同工具评估基准和框架在评估工具使用能力方面的优势和特点是什么，它们如何推动了工具增强LLM研究的发展？  2. 在工具评估基准中，如何通过MetaTool的方法来评估LLM代理是否具有正确的工具选择能力，以及这种方法对于提高工具辅助机器学习工作流程的效果和效率有何重要意义？  3. $\tau$ -bench基准如何强调了人机协作的视角，并通过动态用户交互和政策遵从来推动工具增强LLM研究的发展？
工具评估基准
最近LLM作为代理研究的努力产生了多样化的基准和框架，用于评估工具使用能力。早期研究，如Gorilla和API-Bank，开创了大规模数据集和测试LLM与外部API交互的方法，揭示了诸如参数准确性和幻觉等问题。随后的作品，如T-Bench和ToolBench，引入了更广泛的任务套件，并强调了系统性数据生成对工具操作的重要性。StableToolBench通过强调现实世界API的不稳定性，提出了虚拟API服务器，以实现更一致的评估。同时，ToolAlpaca调查了在相对较小的语言模型中通过最少领域内训练实现通用工具使用的可行性。ToolEmu评估了通过模拟沙盒环境对工具增强的LLM代理的安全性和风险方面。MetaTool引入了一个新的基准，重点关注LLM是否知道何时使用工具，并能正确选择要使用的工具。它提供了一个名为ToolE的数据集，涵盖了单工具和多工具使用情景，鼓励研究工具使用意识和细致的工具选择。ToolEyes通过检查真实场景和跨大型工具库的多步推理进一步推动了评估。最后，$\tau$ -bench引入了人机协作的视角，强调了基于代理对话中的动态用户交互和政策遵从。总的来说，这些基准和框架突显了工具增强LLM研究不断发展的格局，标志着从孤立推理任务转向全面的、真实世界代理评估。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/2/text
1. 工具调用的度量标准如何帮助系统确定是否需要调用外部工具以提高效率和有效性？   2. 为什么在许多场景中，模型必须确定自身推理是否足以回答查询，或者是否需要外部工具提供额外知识？   3. 引入带标签的数据集如何有助于形式化工具调用过程，从而提升系统的性能？
工具调用的度量标准决定是否调用外部工具是一个至关重要的步骤，它可以显著影响系统的效率和有效性。在许多场景中，模型必须确定自身推理是否足以回答查询，或者是否需要工具提供的额外外部知识（或功能）。为了形式化这一过程，我们引入了一个带标签的数据集。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/3/formula
$$ 
D_{\mathrm{inv}}=\{(q_{i},y_{i})\}_{i=0}^{N-1},
 $$
这个公式的作用是定义了一个带标签的数据集$D_{\mathrm{inv}}$，用于模型学习工具调用的决策函数。在这个数据集中，每个样本由一个用户查询$q_{i}$和一个二进制标签$y_{i}\in\{0,1\}$组成，表示是否需要调用工具。其中，$q_{i}$代表第$i$个用户查询，$y_{i}$的取值为0或1，分别表示不需要调用工具和需要调用工具。基于这个数据集，模型将学习一个决策函数$d(q_{i})$，用于根据用户查询$q_{i}$预测是否需要调用工具。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/4/text
1. 决策函数$d(q_{i})$在何种情况下能够准确地判断用户查询$q_{i}$是否需要调用工具，以及其在提高工具辅助机器学习工作流程效率方面的作用是怎样的？  2. 在评估工具选择准确率时，如何利用模型学习的决策函数$d(q_{i})$来确定最合适的工具，并说明这对系统提高工具使用能力的重要性？  3. 在综合考虑决策准确性、检索效率和层次选择精度的基础上，如何利用模型学习的决策函数$d(q_{i})$来优化工具性能，提高工具辅助机器学习工作流程的效果和效率？
其中，$q_{i}$表示第$i$个用户查询，$y_{i}\in\{0,1\}$是一个二进制标签，指示是否需要调用工具（$\langle y_{i}=1\rangle$）或不需要（$(y_{i}=0)$）。基于这个数据集，模型学习一个决策函数$d(q_{i})$，定义如下：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/5/formula
$$ 
d(q_{i})={\left\{\begin{array}{l l}{1,}&{{\mathrm{if~}}P_{\theta}(y=1\mid q_{i})\geq\tau,}\\ {0,}&{{\mathrm{otherwise}},}\end{array}\right.}
 $$
这个公式用于定义一个决策函数$d(q_{i})$，用于确定在给定用户查询$q_{i}$时是否需要调用工具。其中，$P_{\theta}(y=1\mid q_{i})$表示模型（由参数$\theta$参数化）预测在查询$q_{i}$中调用工具的概率，$\tau$是预先确定的阈值。决策函数$d(q_{i})$根据预测概率$P_{\theta}(y=1\mid q_{i})$是否大于等于阈值$\tau$来输出相应的决策：如果$P_{\theta}(y=1\mid q_{i})\geq\tau$，则输出$1$表示需要调用工具；否则输出$0$表示不需要调用工具。这个决策规则可以帮助系统在处理用户查询时做出是否调用工具的决策，从而提高工具辅助机器学习工作流程的效果和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/6/text
1. 如何通过整体调用准确率$A_{\mathrm{inv}}$来评估模型在决定是否调用工具方面的能力？这种评估方法有哪些优点和局限性？  2. 在评估模型决定是否调用工具的能力时，为什么除了决策规则外还需要考虑其他指标？这些指标是如何帮助提高对模型性能的全面评估的？  3. 在机器学习中，如何利用$P_{\theta}(y=1\mid q_{i})$和预先确定的阈值$\tau$来进行工具调用的决策？这种决策方法是否存在潜在的局限性？
其中，$P_{\theta}(y=1\mid q_{i})$表示模型（由参数$\theta$参数化）预测在查询$q_{i}$中调用工具的概率，$\tau$是预先确定的阈值。

除了这个决策规则，还可以使用几种指标来评估模型正确决定是否调用工具的能力。例如，可以计算整体调用准确率$A_{\mathrm{inv}}$如下：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/7/formula
$$ 
A_{\mathrm{inv}}=\frac{1}{N}\sum_{i=0}^{N-1}\mathbf{1}\{d(q_{i})=y_{i}\},
 $$
这个公式用于计算整体调用准确率$A_{\mathrm{inv}}$，表示模型在决定是否在查询$q_{i}$中调用工具时的准确率。其中，$N$表示总的查询数，$d(q_{i})$表示模型对查询$q_{i}$的决策，$y_{i}$表示查询$q_{i}$的真实标签。公式中的指示函数$\mathbf{1}\{\cdot\}$的作用是当括号内的条件成立时取值为1，否则为0。通过计算所有查询的决策准确率的平均值，可以评估模型在调用工具决策上的整体表现。在论文中，这个公式的作用是衡量模型在调用工具时的准确性，为评估模型决策能力提供了重要的指标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/8/text
1. 如何定义净收益分数，以评估工具调用的成本和正确使用工具带来的收益之间的平衡？  2. 在评估工具性能时，为什么需要综合考虑精确率、召回率、F1分数等指标，以及决策准确性、检索效率、层次选择精度等方面的因素？  3. 如何通过工具性能评估中的度量标准和决策规则，提高工具辅助机器学习工作流程的效果和效率？
其中，$\mathbf{1}\{\cdot\}$是指示函数。还可以使用其他指标，如精确率、召回率和F1分数。此外，如果$C_{\mathrm{inv}}$表示调用工具产生的成本，$R(q_{i})$表示正确使用工具时获得的收益或奖励，则可以定义净收益分数：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/9/formula
$$ 
{\cal B}_{\mathrm{inv}}=\sum_{i=0}^{N-1}\left({\bf1}\{d(q_{i})=1\}\cdot R(q_{i})-C_{\mathrm{inv}}\right).
 $$
这个公式的目的是计算净收益分数${\cal B}_{\mathrm{inv}}$，用于评估在使用工具时的成本效益。公式中的符号含义如下：$N$表示候选工具的数量；$q_{i}$表示第$i$个候选工具；$d(q_{i})$是一个指示函数，当使用工具$q_{i}$时产生期望收益时为1，否则为0；$R(q_{i})$表示正确使用工具$q_{i}$时获得的收益或奖励；$C_{\mathrm{inv}}$表示调用工具$q_{i}$产生的成本。公式通过对所有候选工具的期望收益减去调用工具的成本，来计算总体净收益分数。  在论文中，这个公式的作用是帮助系统评估是否需要调用外部工具以及选择最合适的工具。它不仅强调了准确性，还考虑了调用外部工具的成本效益，从而在工具选择过程中综合考虑了收益和成本，以提高工具辅助机器学习工作流程的效果和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/10/text
1. 如何平衡工具选择准确性与调用外部工具的成本效益，以确保系统选择最合适的工具？ 2. 在评估工具选择准确率时，系统如何确定最佳的工具以提高工具辅助机器学习工作流程的效果和效率？ 3. 在考虑工具选择时，系统如何综合考虑工具性能、任务效果和计划复杂性，以实现更好的工具学习机制？
这种表述不仅强调准确性，还考虑了调用外部工具的成本效益。

在决定调用工具之后，下一个挑战是从候选工具池中选择最合适的工具。假设候选工具集表示为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/11/formula
$$ 
\mathcal{T}=\{t_{1},t_{2},\dots,t_{M}\}.
 $$
这个公式表示了一个候选工具集合$\mathcal{T}$，其中包含了$M$个候选工具，分别记为$t_{1}, t_{2}, \dots, t_{M}$。在给定查询$q_{i}$的情况下，假设最佳的工具（根据实际情况）是$t_{i}^{*}$，而模型选择的工具是$\hat{t}_{i}$。工具选择准确率$A_{S}$是衡量模型选择的工具与最佳工具之间匹配程度的性能度量。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/12/text
1. 工具选择准确率$A_{S}$在评估工具选择性能时的优势和局限性是什么？  2. 如何通过工具选择准确率$A_{S}$评估系统是否需要调用外部工具以及选择最合适的工具？  3. 在工具选择准确率$A_{S}$的基础上，如何量化代理工具使用能力并提高工具辅助机器学习工作流程的效果和效率？
对于给定查询$q_{i}$，假设最佳工具（根据地面实况）为$t_{i}^{*}$，模型选择了$\hat{t}_{i}$。最简单的选择性能度量是工具选择准确率$A_{S}$。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/13/formula
$$ 
A_{S}=\frac{1}{|Q|}\sum_{q_{i}\in Q}\mathbf{1}\{\hat{t}_{i}=t_{i}^{*}\}.
 $$
这个公式用于计算工具选择准确率$A_{S}$，即系统从一组候选工具中选择最佳工具的能力。在给定查询$q_{i}$的情况下，假设根据地面实况最佳工具为$t_{i}^{*}$，而模型选择了$\hat{t}_{i}$。公式中的符号解释如下：$|Q|$表示查询集合$Q$的大小；$\mathbf{1}\{\}$是指示函数，当括号内的条件成立时取值为1，否则为0。因此，公式的计算方法是对于查询集合$Q$中的每个查询$q_{i}$，判断模型选择的工具$\hat{t}_{i}$是否等于最佳工具$t_{i}^{*}$，然后将判断结果求和并除以查询集合的大小$|Q|$，从而得到工具选择准确率$A_{S}$的数值。  在论文中，工具选择准确率$A_{S}$是评估系统从候选工具中选择最佳工具的能力的一个重要指标。通过这个公式，可以量化系统在工具选择方面的表现，为评估工具使用能力提供了基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/14/text
1. 在评估工具检索系统时，如何通过基于排名的指标如MRR和nDCG提供更为细致的评估？这些指标如何帮助识别最相关的工具？  2. 层次框架如何区分工具检索的检索准确性和选择准确性？检索准确性和选择准确性分别如何衡量，以评估系统的工具使用能力？  3. 总体工具使用意识是如何通过准确度、召回率、精确度和F1分数进行评估的？这些指标如何帮助评估系统从一组候选工具中选择最佳工具的能力？
然而，许多场景涉及通过相关性对多个候选工具进行排名。在这种情况下，诸如平均倒数排名（MRR）和归一化折现累积增益（nDCG）之类的基于排名的指标提供了更为细致的评估。[690]在评估工具检索系统时使用了这两种指标。

工具检索效率和层次准确性 工具检索涉及识别合适工具的速度以及选择的准确性。高效的检索方法可以减少延迟和计算开销，而高检索准确性则确保为任务识别出最相关的工具。为了全面评估工具使用，我们采用了一个层次框架，区分了检索准确性和选择准确性。检索准确性（$A_{R}$）反映了系统从存储库中精确检索正确工具的能力，通常通过诸如精确匹配（EM）和F1分数之类的指标来衡量，这些指标捕捉了完全匹配和部分匹配。相反，选择准确性（$A_{S}$）评估了系统从一组候选工具中选择最佳工具的能力，同样使用类似的指标。总体工具使用意识进一步通过准确度、召回率、精确度和F1分数进行评估。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/15/text
1. 总体检索效率$E_{Ret}$如何能够综合评估系统的检索准确性和选择准确性，从而提升工具辅助机器学习工作流程的效果和效率？  2. 在评估工具的检索效率时，为什么需要区分层次框架来强调系统精确检索正确工具和选择最佳工具的能力？  3. 总体检索效率$E_{Ret}$的定义如何有助于衡量系统在调用外部工具、选择合适工具以及执行复杂任务规划时的综合表现？
因此，总体检索效率$E_{Ret}$可以表示为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/16/formula
$$ 
E_{R e t}=\frac{A_{R}\times A_{S}\times A_{P}\times A_{U}}{C_{R}}
 $$
该公式用于计算总体检索效率$E_{Ret}$，其中$A_{R}$代表代理在检索时的准确性，$A_{S}$代表选择准确性，$A_{P}$代表工具检索效率，$A_{U}$代表复杂任务规划的准确性，$C_{R}$代表与检索相关的成本。通过将这些因素相乘并除以检索相关的成本，可以得到总体检索效率。在论文中，这个公式的作用是帮助评估工具选择的效率和准确性，为优化工具性能提供量化指标。同时，公式体现了综合考虑决策准确性、检索效率、层次选择精度和规划质量的重要性，以提高工具辅助机器学习工作流程的效果和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/17/text
1. Metatool引入的正确选择率（CSR）如何帮助评估工具选择的效率和精度，以及它是如何量化模型选择预期工具的查询百分比的？  2. 在工具选择评估框架中，如何通过避免选择不正确或不存在的工具来确保可靠性，以及处理多工具查询是如何提高工具检索和选择的效率和精度的？  3. 优化策略可能涉及使用反馈机制训练嵌入模型，以增强效率和每个层次组件的准确性。在这种情况下，如何可以利用反馈机制来提高工具选择的效率和每个层次组件的准确性？
其中$C_{R}$是与检索相关的成本。优化策略可能涉及使用反馈机制训练嵌入模型，以增强效率和每个层次组件的准确性。

为了更细致地评估工具选择，Metatool [796]引入了正确选择率（CSR），用于量化模型选择预期工具的查询百分比。这种评估框架涵盖了四个方面：在类似候选工具中选择正确的工具，在特定上下文场景中选择适当的工具，通过避免选择不正确或不存在的工具来确保可靠性，并处理多工具查询。这些指标和子任务共同提供了工具检索和选择中效率和精度的稳健度量。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/18/text
1. 复杂任务中的工具规划如何帮助系统平衡任务效果和计划复杂性，从而提高规划质量？ 2. 在代理工具使用能力评估中，为什么强调了复杂任务的工具规划对于整体度量模型规划能力的重要性？ 3. 如何通过对复杂任务的工具规划进行评估，提升工具辅助机器学习工作流程的效果和效率？
复杂任务的工具规划
复杂任务通常需要依次应用多个工具才能达到最佳解决方案。工具规划可以表示为一个有序序列。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/19/formula
$$ 
\Pi=[t_{1},t_{2},\dots,t_{K}],
 $$
这个公式表示了一个工具规划$\Pi$，其中包含了按顺序应用的$K$个工具$t_{1}$到$t_{K}$。在论文中，复杂任务通常需要按照特定顺序使用多个工具才能得到最佳解决方案，而工具规划则可以将这些工具的使用顺序表示为一个有序序列。$K$代表了规划中包含的步骤数量，即需要按顺序使用的工具数量。评估这样的规划质量通常涉及到平衡任务效果和规划复杂性的考量。其中，任务效果可以通过度量$R_{\mathrm{task}}(\Pi)$来评估，而规划的复杂性或长度则是另一个重要考量因素。通过综合考虑任务效果和规划复杂性，可以得到一个综合规划得分，用以评估工具规划的质量。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/20/text
1. 如何通过平衡任务效果和计划复杂性来评估计划质量？   2. 为什么在评估计划质量时需要考虑任务效果和计划的复杂性？   3. 什么是综合规划得分，以及它如何捕捉任务效果和计划复杂性之间的平衡？
其中$K$是步骤的数量。这样的计划质量通常通过平衡任务效果（例如，通过度量$R_{\mathrm{task}}(\Pi)$）与计划的复杂性（或长度）来评估。这种平衡可以通过形式为的综合规划得分来捕捉。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/21/formula
$$ 
S_{\mathrm{plan}}=\alpha\cdot R_{\mathrm{task}}(\Pi)-\beta\cdot K,
 $$
这个公式用于计算规划质量得分$S_{\mathrm{plan}}$，其中$S_{\mathrm{plan}}$由任务效果$R_{\mathrm{task}}(\Pi)$乘以系数$\alpha$减去计划步骤数量$K$乘以系数$\beta$得到。系数$\alpha$和$\beta$用于调整任务性能收益和计划复杂性成本之间的权衡。在论文中，$S_{\mathrm{plan}}$用于评估规划质量，通过平衡任务效果和计划复杂性来确定最终得分。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/22/text
1. 如何通过调整系数$\alpha$和$\beta$来平衡高任务性能收益和计划复杂性成本？这种权衡对于优化规划效率有何重要性？  2. 工具评估中的整体规划效率指标是如何利用相似度指标（如BLEU或ROUGE）来比较预测计划$\Pi$与地面真值计划$\Pi^{*}$的？这种方法如何有助于评估工具的性能和有效性？  3. 在工具使用中，为什么行为规划被认为至关重要？行为规划的评估是如何沿着合理性、时效性、多样性、语法正确性、逻辑一致性和纠正思维能力等维度进行的？
其中$\alpha$和$\beta$是调整高任务性能收益和计划复杂性成本之间权衡的系数。当存在地面真值计划$\Pi^{*}$时，可以使用BLEU或ROUGE等相似度指标将预测计划$\Pi$与$\Pi^{*}$进行比较，然后相应地定义整体规划效率指标。

此外，最近的工作（如ToolEyes[797]）强调了将行为规划引入工具使用的重要性。除了选择工具和参数外，LLMs还需要简洁总结获取的信息并策略性地规划后续步骤。在这种情况下，行为规划能力沿两个维度进行评估。首先，通过评估当前状态总结的合理性、为下一个动作序列规划的及时性以及规划的多样性来计算得分$S_{b}$，其有效性$\in[0,1]$。其次，通过评估语法正确性、逻辑一致性和纠正思维能力来计算得分$S_{b\mathrm{-integrity}}\in[0,1]$。然后，将综合行为规划得分确定为

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/23/formula
$$ 
S_{B P}=S_{b\mathrm{-validity}}\cdot S_{b\mathrm{-integrity}},
 $$
这个公式用于计算整体行为规划得分$S_{BP}$，其目的是综合评估模型规划能力。在公式中，$S_{b\text{-validity}}$代表行为规划的有效性得分，$S_{b\text{-integrity}}$代表行为规划的完整性得分。这两个得分相乘得到整体行为规划得分$S_{BP}$，用于衡量模型在行为规划方面的综合表现。  在论文中，这个公式的作用是强调对复杂任务的工具规划需要综合考虑有效性和完整性两个方面，不仅关注工具的选择和排序，还注重维持连贯、高效和具有战略性的规划过程。通过综合评估行为规划的有效性和完整性，可以全面评价模型在规划方面的能力，从而提高工具辅助机器学习工作流程的效果和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.4 Tool Optimization/9.4.3 Evaluation of Tool Effectiveness/section/24/text
1. 如何通过综合框架对模型规划能力进行整体度量，以确保工具规划在复杂任务中不仅侧重于工具的选择和排序，还注重维持连贯、高效和具有战略性的规划过程？  2. 在Agent系统中，如何平衡决策准确性、检索效率、层次选择精度、战略规划、严密风险管理和强大的工具学习机制，以优化工具性能并提高工具辅助机器学习工作流程的效果和效率？  3. 在工具效果评估中，为什么强调了对模型规划能力的整体度量，以确保工具规划在复杂任务中维持连贯、高效和具有战略性的过程？
提供了对模型规划能力的整体度量。这一综合框架确保了针对复杂任务的工具规划不仅侧重于工具的选择和排序，还注重维持连贯、高效和具有战略性的规划过程。

总之，在Agent系统中优化工具性能需要一个综合方法，平衡决策准确性、检索效率、层次选择精度、战略规划、严密风险管理和强大的工具学习机制。通过实施有针对性的优化和学习策略，可以提高工具辅助机器学习工作流程的效果和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.5 Towards Autonomous Agent Optimization/section
在迈向自主代理优化的过程中，除了优化智能代理的个体模块外，研究也集中于整个智能系统的优化。这种整体方法使得大型语言模型（LLM）代理能够更全面地演化，然而，这也提出了更高的要求。ADAS引入了一个元代理，能够在整体优化过程中设计智能系统的工作流程、提示和工具，实验表明自动设计的智能系统胜过手工设计。另一项工作提出了代理符号学习框架，通过引入基于语言的反向传播和权重更新方法，实现了代理工作流的结构化优化。此外，一些研究专注于优化代理系统内的工作流程和提示，如训练额外的LLMs生成提示和工作流程，实现代理系统架构的自动化设计。优化整个代理系统的工作流程需要精心设计算法，考虑到组件之间复杂的相互依赖关系，这是一项具有挑战性的任务，需要先进的技术支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.5 Towards Autonomous Agent Optimization/section/0/text
1. 如何在优化整个智能系统的过程中解决个体组件之间复杂的相互作用，以提高大型语言模型代理的整体性能？ 2. 为什么优化整个代理系统的工作流程需要精心设计算法？这些算法如何考虑到组件之间的复杂相互依赖关系？ 3. 在自主代理优化中，如何利用元代理设计智能系统的工作流程、提示和工具，以实现自动化设计的优势？
除了优化智能代理演化中的个体模块，如提示、工具和工作流程——这些容易受到局部优化的影响，可能损害智能系统整体性能外，大量研究致力于优化整个智能系统内的多个组件。这种整体方法使大型语言模型（LLM）代理能够更全面地演化。然而，优化整个系统提出了更高的要求。算法不仅必须考虑个体组件对智能系统的影响，还必须考虑不同组件之间的复杂相互作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.5 Towards Autonomous Agent Optimization/section/1/text
1. ADAS如何通过引入元代理来实现智能系统的自动设计，以及自动设计相较于手工设计的优势体现在哪些方面？  2. 在优化整个代理系统的工作流程中，为什么需要考虑组件之间复杂的相互依赖关系？这种挑战性任务如何能够借助先进技术得到支持？  3. 代理符号学习框架如何通过引入基于语言的反向传播和权重更新方法，实现了代理工作流的结构化优化？
ADAS[741]是最具代表性的工作之一，首次正式定义了智能系统中自动设计问题。它将多个智能系统组件整合到进化管道中。具体来说，ADAS引入了一个元代理，能够在整体优化过程中迭代地设计智能系统的工作流程、提示和潜在工具。正如实验所证明的那样，自动设计的智能系统胜过了最先进的手工设计基准。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.5 Towards Autonomous Agent Optimization/section/2/text
1. 代理符号学习框架如何将连接主义学习原理与代理管道相结合，实现了代理工作流的结构化优化？ 2. 在训练语言代理时，代理符号学习框架是如何定义基于提示的损失函数，并如何通过代理轨迹传播语言损失来更新符号组件的？ 3. 代理符号学习框架中将节点视为独立代理或允许多个代理在单个节点中执行，这种设计如何有助于自然地扩展到多代理系统，提高整个代理系统的工作效率？
此外，[726]提出了一种代理符号学习框架，用于训练语言代理，灵感来自神经网络中使用的连接主义学习原理。通过将代理管道与计算图进行类比，该框架引入了一种基于语言的反向传播和权重更新方法。它定义了基于提示的损失函数，通过代理轨迹传播语言损失，并相应地更新符号组件。该方法实现了代理工作流的结构化优化，并通过将节点视为独立代理或允许多个代理在单个节点中执行而自然地扩展到多代理系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/9.5 Towards Autonomous Agent Optimization/section/3/text
1. 如何利用自指的概念来优化代理系统内部的工作流程和提示？这种方法如何实现自我改进，以增强系统性能？  2. 在优化代理系统的工作流程中，为什么需要考虑到组件之间复杂的相互依赖关系？这种复杂性如何影响算法的设计和实现？  3. 为什么优化整个代理系统的工作流程不仅仅是简单地对各个组件进行优化的聚合？相比于优化个体组件，系统范围的优化具有哪些更具挑战性的特点？
[799]提出了一种优化提示和代理自身代码的方法，实现自我改进。这符合自指的概念，即系统可以分析和修改自身结构以增强性能。

类似地，[773]、[787]、[800]和[788]专注于优化代理系统内的工作流程和提示。特别是，[285]提出了一种方法，训练额外的大型语言模型（LLMs）生成提示和工作流程，实现代理系统架构的自动化设计。

总之，优化整个代理系统的工作流程并不仅仅是对各个组件优化的简单聚合。相反，它需要考虑到组件之间复杂的相互依赖关系的精心设计算法。这使得系统范围的优化成为一项更具挑战性的任务，需要先进的技术来实现有效和全面的改进。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Large Language Models as Optimizers/section
本章讨论了将大型语言模型（LLMs）作为优化器的相关研究。现有研究主要关注解决Equation(9.1)中定义的提示优化问题，而其他优化代理工作流组件仍处于新兴研究阶段。本章通过类比经典迭代算法，探讨它们如何整合到现代优化工作流中。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Large Language Models as Optimizers/section/0/text
1. 如何将大型语言模型（LLMs）概念化为优化器，并与现代优化工作流整合，相较于传统的迭代算法，其优势在哪里？  2. 为什么现有研究主要集中于解决Equation(9.1)中定义的提示优化问题，而对于优化代理工作流的其他组件的研究仍处于新兴阶段？  3. 在将LLMs作为优化器的研究中，如何通过类比经典的迭代算法来探讨其在现代优化工作流中的整合方式？
在本章中，我们介绍并讨论将LLMs概念化为优化器的现有研究。首先，我们注意到大多数现有研究集中于Equation(9.1)中定义的提示优化问题，因为优化代理工作流的其他组件仍然是一个新兴的研究领域。为了继续，我们将类比于经典的迭代算法，并研究它们如何融入现代优化工作流中。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Online and Offline Agent Self-Improvement/section
智能代理通过优化机制实现自我完善，调节个体组件并确保性能增强一致性。优化涵盖提示设计、工作流编排、奖励函数调整等方面，以战略框架指导整体改进。在线和离线自我改进是主要范式，通过协调两者实现效率和适应性的最大化。混合优化策略整合了这两种方法，以保持一致性、最大化整体有效性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Online and Offline Agent Self-Improvement/section/0/text
1. 智能代理如何利用优化机制来实现自我完善，包括哪些方面可以进行精细调节？ 2. 在自我完善过程中，为什么在孤立情况下优化奖励函数和提示设计可能会产生冲突的结果？如何通过战略方法协调这些优化以保持一致性并最大化整体有效性？ 3. 在智能代理的自我进化中，为什么需要将自我改进分为在线和离线两个主要范式？混合优化策略是如何整合这两种方法以最大化效率和适应性的？
在自我完善的追求中，智能代理利用优化作为一种机制，用于精细调节个体组件，如提示设计、工作流编排、工具利用、奖励函数调整，甚至优化算法本身，并作为一个战略框架，确保这些个体改进朝向一致的性能增强。例如，在孤立情况下优化奖励函数和提示设计可能会产生冲突的结果，但战略方法协调这些优化以保持一致性并最大化整体有效性。我们将自我进化分为两个主要范式：在线和离线自我改进。此外，我们探讨了集成这两种方法以最大化效率和适应性的混合优化策略。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.1 Online Agent Self-Improvement/section
在线自我改进是智能代理根据即时反馈实时调整行为的优化策略。这种范式通过连续优化关键性能指标，如任务成功率和稳定性，确保代理对不断变化的环境做出响应。关键优化策略包括迭代反馈与自我反思、多代理系统中的主动探索、实时奖励塑造和动态参数调整。迭代反馈方法使代理能够批判和优化自身输出，例如自我反思和ReAct框架。多智能体系统中的主动探索策略积极搜索新模式和工作流改进，如MetaGPT和CAMEL。实时奖励塑造整合即时反馈信号用于纠正错误和调整内部奖励函数。动态参数调整通过自主更新内部参数实现无缝适应环境，如自我优化（SSO）。这些策略促进了智能代理框架的不断演化，实现了实时适应性、用户中心优化和强大问题解决能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.1 Online Agent Self-Improvement/section/0/text
1. 在线自我改进如何通过迭代反馈与自我反思实现代理的批判性优化和输出优化？ 2. 多代理系统中的主动探索策略如何促进新模式和工作流改进，例如MetaGPT和CAMEL的应用？ 3. 实时奖励塑造是如何利用即时反馈信号来纠正错误和调整内部奖励函数的？
在线自我改进是指代理根据即时反馈动态调整其行为的实时优化。这一范式确保代理通过连续优化关键性能指标（如任务成功率、延迟、成本和稳定性）在迭代反馈循环中保持对不断变化的环境的响应能力。在线自我改进在需要动态适应性的应用中特别有效，如实时决策制定、个性化用户交互和自动推理系统。在线自我改进中的关键优化策略可分为以下四类：迭代反馈与自我反思、多代理系统中的主动探索、实时奖励塑造和动态参数调整。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.1 Online Agent Self-Improvement/section/1/text
1. 迭代反馈与自我反思如何帮助智能代理在不断变化的环境中实现自我优化和修正错误？ 2. ReAct框架是如何将推理和行动相结合，使得智能代理可以根据外部反馈进行迭代修订？ 3. 在智能代理的自我批判循环中，如何确保选择最连贯的解决方案或者从候选方案中选择最佳解决方案？
迭代反馈与自我反思 这些方法学旨在使代理能够迭代地批判和优化其自身输出。自我反思和自我完善以及思维树引入了自我批判循环，模型在实时中识别错误并提出修订。ReAct将“推理”的思路与“行动”相结合，允许模型在观察外部反馈后迭代修订步骤。此外，其他方法要么依赖于自洽性来选择最连贯的解决方案，要么利用过程奖励模型（PRM）（Lightman等，2019）从候选方案中选择最佳解决方案。总的来说，这些框架减少了错误传播，并支持在不需要单独的离线微调周期的情况下进行快速适应。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.1 Online Agent Self-Improvement/section/2/text
1. 多智能体系统中的主动探索策略如何帮助实现新模式和工作流改进？MetaGPT、CAMEL和ChatDev是如何在多角色生态系统中展示这种探索方法的？  2. 在智能代理系统中，HuggingGPT是如何通过中央的LLM控制器协调不同模型、动态路由任务并收集反馈的？这种协作策略如何影响集体结果的完善？  3. 多智能体系统中的在线更新是如何逐步提高整体性能的？MetaGPT、CAMEL和ChatDev如何利用持续反馈来优化彼此的贡献？
多智能体系统中的主动探索 这些方法[626,848,627,152]积极探索并动态搜索多智能体系统中的新模式和工作流改进。MetaGPT[626]、CAMEL[848]和ChatDev[627]展示了多角色或多智能体生态系统，在实时互动中交换持续反馈以完善彼此的贡献。类似地，HuggingGPT[152]通过中央的LLM控制器协调托管在Hugging Face上的专门模型，动态路由任务并收集反馈。这些协作策略进一步凸显了智能体之间的在线更新如何逐步完善集体结果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.1 Online Agent Self-Improvement/section/3/text
1. 实时奖励塑造如何整合即时反馈信号来实现自适应奖励校准，以平衡性能、计算成本和延迟之间的权衡？ 2. 在智能代理系统中，为什么整合即时反馈信号用于纠正错误和调整内部奖励函数被认为是一种有效的优化策略？ 3. 如何利用实时奖励塑造框架使智能代理能够根据用户交互动态优化奖励机制，从而实现更好的问题解决能力？
实时奖励塑造 一些框架[731,91,05,849]不仅依赖于固定或纯离线奖励规范，还整合了即时反馈信号，用于纠正错误，同时也用于调整内部奖励函数和策略。这使得自适应奖励校准成为可能，平衡了性能、计算成本和延迟之间的权衡，使智能体能够根据用户交互动态优化奖励机制。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.1 Online Agent Self-Improvement/section/4/figure
1. 在图1.1中，不同利用场景下的自我改进示意图中是否呈现出明显的区别？这些区别可能对智能代理的性能有何影响？  2. 在线、离线和混合自我改进三种利用场景中，哪种场景更适合于提高智能代理的实时适应性和问题解决能力？
图1.1：展示了在三种不同利用场景下的自我改进示意图，包括在线、离线和混合自我改进。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.1 Online Agent Self-Improvement/section/5/text
1. 动态参数调整中的无梯度或近似梯度方法如何帮助智能代理在实时环境中自主更新内部参数，从而提高计算效率和决策准确性？  2. 自我优化（SSO）是如何消除手动标注的需求，并通过自动生成偏好信号在迭代训练过程中维持信号准确性的？  3. 如何利用自我优化（SSO）实现智能代理在保持训练在线策略的同时，实现对环境变化的无缝适应？
动态参数调整：在这一类别中，智能体通过使用无梯度或近似梯度方法，在实时环境中自主更新其内部参数（包括提示模板、工具调用阈值、搜索启发式等）。这些更新优化了计算效率和决策准确性，使其能够无缝适应不断变化的环境。自我优化（SSO）[850]消除了手动标注的需求，通过在迭代训练过程中自动生成偏好信号，在保持训练在线策略的同时保持信号准确性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.1 Online Agent Self-Improvement/section/6/text
1. 在线自我优化如何促进智能代理框架的不断演化？   2. 学习如何嵌入在任务执行中，对智能代理的实时适应性有何影响？   3. 如何实现以用户为中心的优化和强大的问题解决能力在智能代理系统中的应用？
在线自我优化促进了一个不断演化的智能体框架，其中学习嵌入在任务执行中，促进了增强的实时适应性、以用户为中心的优化和强大的问题解决能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.2 Offline Agent Self-Improvement/section
离线Agent自我提升利用结构化的基于批处理的优化，通过批处理参数更新和微调、代理组件的元优化以及系统性奖励模型校准来提升代理的泛化能力。这种方法适用于计算密集型任务，包括广泛微调和元学习策略。通过离线训练，代理能够优化检索策略，提高对知识库的推理能力，并确保奖励模型与长期目标一致。结构化的离线优化使代理性能稳定高效，适用于真实世界部署，尤其适用于需要可预测性能的关键任务应用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.2 Offline Agent Self-Improvement/section/0/text
1. 离线自我提升方法如何利用批处理参数更新和微调来优化代理的性能，特别是在广泛知识语料库上的推理能力方面有何作用？  2. 代理组件的元优化是如何帮助代理发现最有效的学习参数，从而提高泛化能力和适用于新问题领域的？  3. 离线设置如何通过系统性奖励模型校准来确保代理行为与长期目标一致，以应对真实世界任务的复杂性和增强泛化能力？
离线自我改进相反，利用结构化的基于批处理的优化。这种范式利用预定的训练会话和高质量策划数据集，系统地提升代理的泛化能力。与在线方法不同，离线方法适用于更加计算密集的方法，包括批处理参数更新和微调、元优化以及系统性奖励模型校准。

批处理参数更新和微调：在这个类别中，代理通过使用监督学习或强化学习（RL）技术进行广泛微调，优化在大规模数据集上跨多个训练周期的性能。检索增强生成（RAG）通常被整合以增强上下文理解和长期记忆检索。这些方法允许代理优化检索策略，从而改善对广泛知识语料库的推理能力。

代理组件的元优化：这里的离线训练不仅限于提升任务性能，还延伸到优化算法本身。优化超参数或甚至动态重构优化过程的元学习策略已经展现出有前途的成果。这些元优化方法使代理能够为新问题领域发现最有效的学习参数。

系统性奖励模型校准：离线设置有助于精确校准奖励模型，整合了分层或列表式奖励集成框架（例如，LIRE），通过基于梯度的奖励优化来使代理行为与长期目标保持一致。这种校准确保奖励函数反映真实世界任务的复杂性，从而减轻偏见并增强泛化能力。

离线优化的结构化特性导致了一个强大的代理基线，其性能经过微调以优化稳定性、效率和计算成本，然后再进行真实世界部署。离线训练允许进行高保真度的模型细化，对于需要可预测性能保证的关键任务应用至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.3 Comparison of Online and Offline Improvement/section
在线和离线优化提供了互补的好处，各自在自我提升的不同方面表现出色。在线优化在动态环境中蓬勃发展，在这种环境中，实时反馈使得持续适应成为可能。它非常适用于需要即时响应的应用，如交互式代理、实时决策和强化学习系统。然而，频繁的更新可能会引入不稳定性或漂移，需要机制来减轻随时间推移而带来的性能下降。相比之下，离线优化强调使用预先收集的数据集进行结构化、高保真度的训练，在部署之前确保强大且稳定的性能。通过利用计算密集型的学习方法，如批量训练、微调和元优化，离线方法提供了强大的泛化能力和长期一致性。然而，它们缺乏在线学习的灵活性，并且可能在没有额外重新训练的情况下难以有效地适应新领域。现代智能系统通过混合优化策略将这两种方法整合起来，利用离线训练的稳定性，同时融合了实时适应性，使代理能够在动态环境中保持长期稳健性，同时不断完善其性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.3 Comparison of Online and Offline Improvement/section/0/text
1. 在线优化和离线优化各有哪些优势和劣势？如何利用它们的优势互补，以提高智能系统在动态环境中的性能表现？ 2. 离线优化强调的预先收集数据集和计算密集型学习方法如何确保性能的稳定性和泛化能力？在线学习的灵活性与离线学习的长期一致性之间如何取得平衡？ 3. 在现代智能系统中，如何通过混合优化策略整合在线和离线优化，以实现代理在动态环境中的长期稳健性和性能持续提升？
在线和离线优化提供了互补的好处，各自在自我提升的不同方面表现出色。在线优化在动态环境中蓬勃发展，在这种环境中，实时反馈使得持续适应成为可能。它非常适用于需要即时响应的应用，如交互式代理、实时决策和强化学习系统。然而，频繁的更新可能会引入不稳定性或漂移，需要机制来减轻随时间推移而带来的性能下降。

相比之下，离线优化强调使用预先收集的数据集进行结构化、高保真度的训练，在部署之前确保强大且稳定的性能。通过利用计算密集型的学习方法，如批量训练、微调和元优化，离线方法提供了强大的泛化能力和长期一致性。然而，它们缺乏在线学习的灵活性，并且可能在没有额外重新训练的情况下难以有效地适应新领域。表11.1总结了这两种范式之间的关键区别。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.3 Comparison of Online and Offline Improvement/section/1/table
1. 在表1.1中，哪些方面展示了在线优化策略在动态环境中的优势？  2. 现代智能系统如何通过混合优化策略整合在线和离线方法的优势？
表1.1：自我增强代理中在线与离线优化策略的比较。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.3 Comparison of Online and Offline Improvement/section/2/text
1. 如何利用混合优化策略整合在线和离线优化方法，使得智能系统在动态环境中既能保持稳健性又能不断提升性能？ 2. 离线训练和在线优化各自的优势和劣势是什么，如何在混合框架中克服它们的局限性？ 3. 在现代智能系统中，为什么需要同时考虑离线训练的稳定性和在线适应性？这种整合对系统性能有哪些影响？
尽管这两种方法都具有固有的优势和权衡，但现代智能系统越来越多地通过混合优化策略将它们整合起来。这些混合框架利用了离线训练的稳定性，同时融合了实时适应性，使代理能够在动态环境中保持长期稳健性，同时不断完善其性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.4 Hybrid Approaches/section
混合方法在智能代理系统中发挥关键作用，通过结合离线预训练、在线微调和定期离线巩固三个阶段，实现对代理的持续增强。首先，在离线预训练阶段，代理通过广泛的离线训练获取基准能力，如推理和决策能力，为后续改进奠定稳定基础。其次，通过在线微调，代理能够根据实时反馈动态调整策略，不断完善自身能力，适应复杂场景。最后，定期的离线巩固阶段将在线改进整合到代理的核心模型中，确保长期稳定性和有效性。混合优化方法的循环特性使代理系统能够即时响应和持续改进，特别适用于实际应用领域，如自主机器人和个性化智能助手。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.4 Hybrid Approaches/section/0/text
1. 混合优化方法如何通过离线预训练阶段确保代理系统具备稳定的基础能力，为后续在线改进提供支持？    2. 在线微调阶段如何帮助代理系统根据实时反馈动态调整策略，以适应复杂场景并不断完善自身能力？    3. 混合优化方法中的定期离线巩固阶段如何确保在线改进能够整合到代理的核心模型中，以保证代理系统的长期稳定性和有效性？
认识到在线和离线方法都具有固有的局限性，许多当代系统采用混合优化策略。这些混合方法将结构化的离线优化与响应式的在线更新相结合，以实现对代理的持续增量增强。

混合优化明确支持自我改进，通过使代理能够自主评估、调整和增强其行为，通过独特而相互关联的阶段实现：

·离线预训练：在这个基础阶段，代理通过对策划数据集的广泛离线训练获得强大的基准能力。这个阶段建立了初步自主表现所需的基本技能，如推理和决策能力。例如，Schrittwieser等人介绍的框架系统显示了离线预训练如何系统地增强初始代理能力，确保随后的在线改进建立在稳定的基础之上。 ·在线微调以实现动态调整：代理通过自主评估其表现、识别不足之处，并根据实时反馈动态调整策略，积极完善其能力。这种自适应微调阶段与代理自我改进范式直接契合，允许实时优化代理特定的工作流程和行为，Decision Mamba-Hybrid (DM-H)等实例展示了代理如何有效适应复杂、不断变化的场景。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.4 Hybrid Approaches/section/1/text
1. Uni-O4框架如何实现离线知识巩固和在线自适应改进之间的无缝过渡？ 2. 在代理系统中，为什么定期的离线巩固阶段对于长期改进至关重要？ 3. 混合优化方法中的循环特性如何帮助代理系统在实际应用领域中实现即时响应和持续改进？
·定期离线巩固以实现长期改进：定期的离线巩固阶段，代理系统地整合和巩固在线交互中识别出的改进。这确保了增量式、在线获得的技能和改进被系统地整合到代理的核心模型中，保持长期稳定性和有效性。Uni-O4框架展示了这一过程如何实现离线知识巩固和在线自适应改进之间的无缝过渡。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/11.4 Hybrid Approaches/section/2/text
1. 混合优化方法中的离线学习和在线适应如何相互作用，从而支持代理系统的自主、持续演化？ 2. 混合优化方法如何确保代理系统具有即时的响应能力和稳定的长期改进，使其适用于复杂的现实场景？ 3. 在实际应用领域中，混合优化方法如何应用于自主机器人、个性化智能助手和交互系统，以提升其性能和适应性？
混合优化因此通过将结构化的离线学习与主动的实时在线适应相无缝地交织在一起，明确支持自主、持续的演化。这种循环方法为代理系统提供了即时的响应能力和稳定的长期改进，使其非常适用于复杂的现实场景，如自主机器人、个性化智能助手和交互系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Scientific Discovery and Intelligent Evolution/section
本章讨论了智能代理系统如何推动自我持续创新循环，探讨了科学知识发现对智能生物自我演化的重要性。代理工作流的自主发现进展被视为实现完全自主、自我演化代理的关键。这些代理旨在揭示、验证和整合数据，推动客观科学理解的进展。通过作为“科学家AI”，代理助力人类拓展知识边界。章节首先定义了知识和智能，介绍了代理与科学知识互动的典型场景，并强调了自我增强代理在科学研究中的成功案例。最后，总结了未来挑战和发展前景。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Scientific Discovery and Intelligent Evolution/section/0/text
1. 智能代理系统如何推动自我持续创新循环，以及它们如何促进代理演化和人类进步的关键机制是什么？  2. 代理工作流在科学知识的自主发现中的进展如何影响了代理系统朝向完全自主、自我演化的发展方向，以及这种发展对人类技术创新的潜在影响是什么？  3. 代理作为“科学家AI”如何在揭示、验证和整合数据、见解和原则方面推动客观科学理解的进展，以及它们如何助力人类拓展知识的边界？
在前几章中，我们主要从技术角度讨论了智能代理系统的演变，重点关注如何开发能够有效执行传统由人类执行的明确定义任务的系统。然而，一个根本而重要的问题仍然存在：这些代理能否推动自我持续创新循环，推动代理演化和人类进步？

科学知识的发现是智能生物自我演化的一个引人注目的例子，因为它帮助它们以可持续的方式适应世界。能够以不同程度的自主性和安全方式发现科学知识的代理也将在人类技术创新中扮演重要角色。在这一部分中，我们调查了使用代理工作流进行自主发现的进展，并讨论了朝着完全自主、自我演化代理的技术准备情况。在这个范围内，代理的目标是揭示、验证和整合数据、见解和原则，以推进对自然现象客观科学理解的进展。代理不是试图改变世界，而是试图作为一种“科学家AI”更好地理解自然，并协助人类拓展知识的边界。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Scientific Discovery and Intelligent Evolution/section/1/text
1. 如何定义知识和智能的概念，以及这两者在智能代理系统中的作用和关系是怎样的？ 2. 在智能代理系统中，代理和科学知识是如何相互作用的？这种相互作用对推动客观科学理解有何重要意义？ 3. 自我增强代理在理论、计算和实验科学研究中的成功案例是如何体现的？未来展望中的当前挑战主要集中在哪些方面？
我们首先定义知识和智能的概念，以澄清我们的讨论，然后介绍了代理和科学知识相互作用的三种典型场景。我们还强调了已有成功案例，以及应用于理论、计算和实验科学研究的自我增强代理。最后，我们总结了未来展望中的当前挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collaborative and Evolutionary Intelligent Systems/section
合作与进化是智能多代理系统的核心。受生物生态系统和人类社会的启发，这些系统利用集体智慧解决复杂挑战。MAS借鉴人类社会策略，整合专门代理协作解决任务。集体智慧原则支持MAS设计，认为多样化代理通常比孤立专家产生更优决策。最近，LLMs的发展为LLM-MAS带来新可能性，利用强大推理能力创建复杂架构，反映人类社会合作特征。LLM-MAS中代理扮演不同角色，采用结构化通信和协调决策实现共同目标。系统不断进化，通过互动、反馈和学习提高性能。本章系统调查基于LLM的多代理系统，关注协作机制和进化能力。研究系统目标塑造代理角色、通信结构、协作决策方法、集体智慧和进化机制。讨论适应性学习、知识共享和改进机制，指出研究方向和挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collaborative and Evolutionary Intelligent Systems/section/0/text
1. 多代理系统中的集体智慧原则如何影响代理之间的协作和决策过程？ 2. LLM-MAS相较于传统MAS系统，如何利用强大的推理能力和人类社会合作特征来提升性能和解决复杂挑战？ 3. 在基于LLM的多代理系统中，系统如何通过适应性学习、知识共享和改进机制实现持续的进化和性能提升？
合作与进化的概念是智能多代理系统（MAS）的核心。受生物生态系统和人类社会动态的启发，这些系统利用集体智慧来解决超出个体代理能力范围的复杂挑战。人类社会展示了合作、专业化和分布式决策如何显著增强集体问题解决效率的例子。同样，MAS采用这些策略，整合专门代理以协作解决复杂任务。集体智慧的基本原则——“众人的智慧”——表明，多样化、独立的代理通常比孤立的专家产生更优越的决策，直接支持MAS的设计理念。认知理论，例如明斯基的“心智社会”和心灵理论，进一步强调了这一范式，提出智能是从专门单位之间的结构化互动中产生的。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collaborative and Evolutionary Intelligent Systems/section/1/text
1. LLM-MAS中的代理如何通过结构化通信、动态知识共享和协调决策来模拟人类社会动态，从而实现共同目标？    2. 代理在LLM-MAS中如何通过互动、反馈和迭代学习不断适应和改进，从而提高系统性能？   3. 在基于LLM的多代理系统中，如何通过研究系统目标来塑造代理的角色、行为模式和协作策略？
最近，大型语言模型（LLMs）的进步为协作和进化的多代理系统（LLM-MAS）引入了新的可能性。借助强大的推理、规划和决策能力，这些模型使得能够创建复杂的MAS架构，反映了人类社会中发现的合作和适应性特征。LLM-MAS中的代理通常扮演不同的身份和角色，反映了类似人类的分工和专业化合作。通过采用结构化通信、动态知识共享和协调决策，这些系统模拟人类社会动态以实现共同目标。此外，LLM-MAS在本质上是进化的；代理通过互动、反馈和迭代学习不断适应和改进，从而随着时间的推移提高系统性能。在本章中，我们系统地调查了基于LLM的多代理系统这一新兴领域，重点关注它们的协作机制和进化能力。首先，我们在第13章中研究了不同的系统目标如何塑造代理的角色、行为模式和协作策略。接下来，在第14章中，我们分析了各种通信结构，包括促进有效代理-代理和人-代理通信的交互协议。此外，我们探讨了协作决策方法以及代理如何利用其独特的专业知识和观点，在第15章中，并在第16章讨论了集体智慧和进化机制。最后，在第17章中，我们讨论了进化过程，重点介绍了适应性学习方法、持续知识共享以及促进迭代改进的机制，共同提升MAS性能。通过这一全面调查，我们确定了当前的成就，讨论了现有的挑战，并强调了协作和进化智能系统的有前途的研究方向。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collaborative and Evolutionary Intelligent Systems/section/2/figure
1. 根据图12.3中基于LLM的多智能体系统分类，不同类别的智能体在协作机制和进化能力方面有何显著差异？     2. 在研究系统目标塑造代理角色、通信结构、协作决策方法、集体智慧和进化机制的过程中，如何利用图12.3中的分类结果指导系统的进化和性能提升？
图12.3：基于LLM的多智能体系统分类。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Design of Multi-Agent Systems/section
在基于LLM的多智能体系统（LLM-MAS）中，协作目标和协作规范是塑造系统行为和整体有效性的核心要素。协作目标指明智能体的明确目标，而协作规范则定义了智能体之间的规则和约束。本节将LLM-MAS分为战略学习、建模与仿真以及协作任务解决三类，分别涵盖了智能体在博弈论、独立行动和系统合作背景下的相互作用。战略学习系统涉及智能体在博弈环境中的合作或竞争，建模与仿真侧重于环境驱动的独立行动，而协作任务解决强调智能体之间的系统合作以实现共享目标。这些类别清晰地展示了系统目标如何引导智能体的互动和结果，为探究LLMs如何影响智能体行为和集体智能提供了框架。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Design of Multi-Agent Systems/section/0/text
1. 在LLM-MAS中，协作目标和协作规范如何共同塑造系统行为和整体有效性？  2. 在战略学习、建模与仿真以及协作任务解决这三类中，LLM-MAS是如何引导智能体的互动和结果的？ 3. 在基于LLM的多智能体系统中，协作目标和协作规范对智能体行为和集体智能有何影响？
在基于LLM的多智能体系统（LLM-MAS）的背景下，协作目标和协作规范作为塑造系统行为、交互模式和整体有效性的基础要素。协作目标指明智能体旨在实现的明确目标 - 无论是个体的、集体的还是竞争性的，而协作规范则定义了规则、约束和惯例，指导系统内智能体之间的互动。这些组成部分共同确立了一个健壮的框架，引导智能体之间有效的沟通、协调和合作。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Design of Multi-Agent Systems/section/1/text
1. 战略学习系统中的智能体在博弈论背景下追求个体或部分冲突的目标时，预定义的博弈规则和互动规范如何指导他们的交互行为？    2. 在建模与仿真背景下，智能体的独立行动是如何受到各种环境或社会因素的驱动？这种自然产生的交互如何反映了大规模社会或经济仿真中的复杂动态？  3. 在协作任务解决中，智能体之间通过结构化工作流程、角色定义和协作规范实现共享目标时，他们如何同步行动以朝向集体目标？
本节将LLM-MAS分为三类，基于不同的协作目标和规范组合：战略学习、建模与仿真以及协作任务解决。虽然不是穷尽的，这些类别涵盖了LLM-MAS设计的广泛领域，清晰地反映了系统目标如何塑造智能体的相互作用和结果。

- 战略学习系统将智能体嵌入到博弈论背景中，智能体追求个体或部分冲突的目标。交互可以是合作的、竞争的或混合的，明确受预定义的博弈规则和互动规范指导。这种设置通常与传统博弈论中的非合作（战略）和合作概念相一致。详情请参见第13.1节。
- 建模与仿真背景侧重于智能体独立行动，受到各种环境或社会因素驱动。在这里，交互会自然产生，不一定会收敛于共同目标，反映了大规模社会或经济仿真中看到的复杂动态。详情请参见第13.2节。
- 协作任务解决强调智能体之间的系统合作，以实现明确定义的共享目标。智能体通常采用结构化工作流程、清晰的角色定义和高度预定义的协作规范，以同步他们的行动朝向集体目标。详情请参见第13.3节。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Design of Multi-Agent Systems/section/2/text
1. 大型语言模型在LLM-MAS中如何被应用来塑造智能体的行为和相互作用？ 2. 在LLM-MAS中，协作目标和协作规范如何共同影响智能体的行为和集体智能？ 3. 三类LLM-MAS中的战略学习、建模与仿真以及协作任务解决如何分别影响智能体的行为和相互作用？
在本章的其余部分，我们将详细阐述每一类别，探讨LLMs如何在我们的范围内实现、影响和增强智能体的行为、相互作用和集体智能。

接下来，我们将详细研究这些类别，重点介绍每一类别如何利用大型语言模型的能力来塑造智能体的行为和相互作用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.1 Strategic Learning: Cooperation vs. Competition/section
战略学习是智能代理在博弈理论环境中预测、解释和影响其他代理行动的能力，涵盖竞争性、合作性和混合性情境。LLMs的发展使战略学习整合了对话、说服和隐含协商等“软”信号，丰富了传统博弈论框架。在经济领域，LLMs模拟市场行为和谈判策略，展示代理在招聘、股票预测和定价等方面的决策能力。此外，战略学习在资源分配、联盟合作和社交推理游戏等领域也得到广泛应用。基于LLMs的代理能够有效结合博弈论逻辑和自然语言推理，提升了对复杂现实世界互动的建模能力，为经济竞争、社会谈判和地缘政治战略领域带来重要潜力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.1 Strategic Learning: Cooperation vs. Competition/section/0/text
1. 战略学习中的LLMs如何丰富了传统博弈论框架，提供了怎样的优势和机遇？ 2. 在经济领域中，LLMs如何模拟市场行为和谈判策略，以及展示代理在决策能力方面的表现？ 3. 如何基于LLMs的代理有效结合博弈论逻辑和自然语言推理，提升了对复杂现实世界互动的建模能力？
战略学习指的是智能代理在博弈理论环境中动态地预测、解释和影响其他代理的行动能力——无论是竞争性的、合作性的还是混合性的[949]。代理根据新信息迭代调整他们的策略，通常使用基本概念，如纳什均衡[950]、贝叶斯博弈[951, 914, 952]或重复互动[953, 954]进行建模。随着LLMs实现了细致的语言推理，战略学习越来越多地整合了“软”信号，包括对话、说服和隐含协商，从而丰富传统的博弈论推理框架[952, 955, 956, 957]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.1 Strategic Learning: Cooperation vs. Competition/section/1/text
1. 多智能体战略模拟如何为市场行为和谈判策略提供宝贵见解，以及在经济领域中的应用有哪些特点和优势？  2. 在研究LLM增强的代理模拟招聘流程和预测股票走势时，如何展现了代理的理性决策能力，并且这种决策能力如何与传统经济模型相比有所不同？  3. 基于GPT-4的竞争环境如何促进了餐厅代理和顾客代理之间的竞争优化，以及这种竞争策略如何反映了现实生活中的竞标和定价策略的特点？
在经济应用中，多智能体战略模拟为市场行为和谈判策略提供了宝贵的见解，突出了竞争性和合作性动态。例如，[958]和[951]展示了LLM增强的代理如何模拟招聘流程，在受控经济实验中展现理性决策，甚至预测股票走势。[959]引入基于GPT-4的竞争环境，展示餐厅代理和顾客代理如何竞争以优化利润和满意度，展示了现实的竞标和定价策略。与此同时，[960]研究了LLM基础谈判中的买方-卖方讨价还价，而[961]利用最后通牒博弈模拟揭示了以类人战略行为为基础的政策制定决策。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.1 Strategic Learning: Cooperation vs. Competition/section/2/figure
1. 在基于LLM的多代理系统中，建模与仿真、战略学习和协作任务解决这三种主要协作类型各自的特点是什么，它们在代理的目标和规范设定方式上有何异同？     2. 基于LLM的多代理系统中，代理如何协调实现独立、分歧和共享的目标，以达到建模与仿真、战略学习和协作任务解决的效果？
图13.1：基于LLM的多代理系统中三种主要协作类型的概述：建模与仿真、战略学习和协作任务解决。每个类别的区别在于代理的目标和规范的设定方式（独立 vs. 分歧 vs. 共享）以及它们如何协调。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.1 Strategic Learning: Cooperation vs. Competition/section/3/text
1. 在资源分配和联盟合作中，基于LLMs的代理如何应对多商品竞争中的策略协商，以及在可持续发展情境下如何协调资源消耗？  2. 在社交推理游戏中，基于LLMs的代理是如何处理欺骗和合作之间复杂相互作用的？以《狼人杀》、《变色龙》等游戏为例，LLMs如何帮助代理制定微妙的欺骗和合作策略？  3. 外交模拟中基于LLMs的代理如何模拟全球范围内的地缘政治谈判和联盟形成动态？LLMs如何在复杂的外交情境中帮助代理进行自主多代理互动，重新创造复杂叙事？
在传统市场之外，战略学习广泛适用于资源分配、联盟或竞争合作权衡存在的各个领域。例如，多商品竞争[962,959]中，代理商战略性地协商条款以最大化个人利益，或者在以可持续发展为重点的情境中，代理商协调资源消耗[963]。在游戏中，社交推理游戏如《狼人杀》、《变色龙》、《阿瓦隆》和《局本射》需要代理商管理欺骗和合作之间复杂的相互作用[964,965,966,153,919,967,968,969,970]。[97,965]的研究强调了基于LLM的代理商在精心策划微妙欺骗和合作方面的出色表现，而[967,972,968,969]强调了《阿瓦隆》中自适应的、多轮策略。[970]进一步推动了这一边界，展示了在《局本射》谋杀悬疑类型中的自主多代理互动，重新创造了复杂的叙事。类似地，外交模拟([973]和[974])利用基于LLM的代理模拟全球范围内复杂的地缘政治谈判和联盟形成动态。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.1 Strategic Learning: Cooperation vs. Competition/section/4/text
1. LLM驱动的战略学习如何有效结合博弈论逻辑与自然语言推理？这种结合对代理商在解释指令、进行对话和适应环境方面有何重要意义？ 2. 在复杂的现实世界互动中，基于LLM的战略代理商相较于传统方法有哪些优势？如何体现其在经济竞争、社会谈判和地缘政治战略领域的重要潜力？ 3. 基于LLM的战略学习如何提升了对复杂现实世界互动的建模能力？其在资源分配、联盟合作和社交推理游戏等领域的应用有何特点？
总结LLM驱动的战略学习的一个关键优势在于有效地将严谨的博弈论逻辑与自然语言推理相结合。这种融合使代理商能够解释复杂的指令，进行有说服力的对话，并更灵活地适应新颖或非结构化的环境。因此，基于LLM的战略代理商在准确建模复杂的现实世界互动方面具有重要潜力，远比传统基于规则或仅数字化的方法更有效地跨越经济竞争、社会谈判和地缘政治战略领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.2 Modeling Real-World Dynamics/section
基于LLM的多智能体系统（LLMMAS）的建模和仿真是一个关键的应用领域，旨在复制复杂的社会、经济和政治现象。这种方法利用LLMs的语言理解和情境推理能力，使仿真智能体能够独立运作，反映现实世界的动态性。在医疗保健、经济和政治领域，LLM驱动的智能体如Agent Hospital和EconAgents被成功应用，为研究人员提供了测试治疗策略、经济行为和政治决策的虚拟环境。此外，社会和文化现象的模拟也得到拓展，如社交网络中情绪传播、假新闻传播和群体行为研究。LLM模拟的优势在于捕捉结构动态和推动现实行为的认知差异，为研究复杂社会过程提供了新的视角。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.2 Modeling Real-World Dynamics/section/0/text
1. 在基于LLM的多智能体系统中，如何利用复杂的语言理解和情境推理能力来实现智能体的高度异质性，以反映现实世界的动态性？  2. 相较于强调明确竞争或合作目标的战略学习环境，基于LLM的多智能体系统中，智能体独立运作的优势体现在哪些方面？如何通过领域特定角色、偏好和与模拟环境的交互来指导智能体的行为演化？  3. 在建模和仿真场景中，基于LLM的多智能体系统如何能够为研究人员提供新的视角，捕捉结构动态和推动现实行为的认知差异，以探索和理解复杂社会过程？
基于LLM的多智能体系统（LLMMAS）的建模和仿真代表另一个关键的应用领域，旨在在规模上复制复杂的社会、经济和政治现象。通过利用LLMs的复杂语言理解和情境推理，这些仿真可以呈现高度异质的智能体，其不断演化的行为反映了现实世界的动态性。与强调明确竞争或合作目标的战略学习环境不同，在建模和仿真场景中，智能体独立运作，受其领域特定角色、偏好和与模拟环境的交互指导。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.2 Modeling Real-World Dynamics/section/1/text
1. 在LLM驱动的智能体模拟中，如何利用Agent Hospital和EconAgents在医疗保健和经济领域中测试治疗策略、管理协议以及经济行为，从而提供更具逼真性和可控性的研究环境？  2. 在LLMMAS建模和仿真中，LLM的语言理解和情境推理能力如何帮助模拟医疗保健、经济和政治领域的复杂社会过程，以及如何捕捉结构动态和推动现实行为的认知差异？  3. 在LLM驱动的智能体应用中，如何通过模拟选举过程和政策制定动态揭示公共话语、候选人策略和选民互动对塑造政治结果的影响，进而为政治科学研究提供新的视角和理论价值？
在医疗保健领域，例如，引入了Agent Hospital，其中由LLM驱动的医生智能体通过与虚拟患者的真实互动反复完善治疗策略。这使研究人员能够在受控而又逼真的环境中测试管理协议、培训范式和“假设”场景。类似地，在经济背景下，提出了EconAgents，利用LLM驱动的智能体逼真地模拟个体层面的行为，如就业决策、消费模式和储蓄策略。这些智能体促进了富有表现力的宏观经济模拟，超越了传统的数值或严格基于规则的方法在适应性和逼真性方面的表现。此外，政治科学应用也受益于这种方法。例如，成功地模拟了选举过程和政策制定动态，揭示了公共话语、候选人策略和选民互动如何塑造现实世界的政治结果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.2 Modeling Real-World Dynamics/section/2/text
1. 基于LLM的模拟在研究社交网络中语言和情绪传播时，如何帮助理解在线观点、信念或情绪集群的形成机制？    2. 在模拟中，研究假新闻在异质智能体群体中传播或停滞的条件时，哪些因素对信息传播的影响最为关键？    3. 大规模模拟平台如GenSim和OASIS如何帮助研究者深入探讨群体行为和系统效应，例如病毒式信息传播、同质化信息茧房形成或群体极化？
除了经济学和政治学，基于LLM的模拟还涵盖了各种社会和文化现象。例如，[979]和[255]使用社交网络中语言和情绪传播的模拟来研究在线观点、信念或情绪集群是如何形成的。[980]的研究探讨了在不同拓扑结构和交互模式下观点动态是如何演变的，而[981]则研究了假新闻在异质智能体群体中传播或停滞的条件。诸如GenSim[982]和OASIS [936]等大规模模拟平台进一步拓展了边界，将规模扩展到数万甚至数百万用户智能体，从而使得能够研究新兴群体行为和系统效应，如病毒式信息传播、同质化信息茧房形成或群体极化等，都在现实约束条件下得以实现。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.2 Modeling Real-World Dynamics/section/3/text
1. LLM模拟如何利用语言理解和情境推理能力来捕捉社会过程中的结构动态和推动现实行为的认知差异？ 2. 在基于LLM的多智能体系统中，如何将基于语言的推理嵌入代理模型，以便研究复杂的社会过程，如说服、框架构建或文化传播？ 3. 为什么传统的数字或基于规则的方法很难捕捉复杂社会过程中的细微差别，而LLM模拟能够提供新的视角？
总结：LLM模拟的优势在于捕捉结构动态（例如，网络拓扑或制度规则）和推动现实行为的认知或语言细微差别。通过将基于语言的推理嵌入到代理模型中，研究人员可以研究复杂的社会过程，如说服、框架构建或文化传播，这些过程通过纯粹的数字或基于规则的方法很难捕捉。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.3 Collaborative Task Solving with Workflow Generation/section
协作任务解决是通过结构化工作流程协调多个代理朝着明确定义的目标前进。这种方法与竞争利益的战略学习或独立行动的开放建模相比，更注重代理作为问题解决流程的一部分。代理遵循明确定义的角色和阶段性流程，确保任务高效完成。系统如MetaGPT、CAMEL和交际代理展示了明确定义的角色和决策流程如何有效协调基于LLM的代理。代理间通过自然语言“对话”沟通，利用LLM的语言生成能力。这种结构化方法在扩展到更大项目时尤为有益，因为子任务可以委托给专门代理。协作任务解决在软件开发和科学研究中有广泛应用，如Agent Laboratory利用代理进行结构化科学工作流程。相较于其他多代理范式，协作任务解决更注重清晰性和可预测性，限制了新兴行为，同时研究致力于平衡结构和灵活性，确保任务可靠完成。这一维度展示了基于LLM的多代理系统的广度，利用基于语言的推理解决各种挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.3 Collaborative Task Solving with Workflow Generation/section/0/text
1. 协作任务解决中的结构化工作流程如何有助于多个代理朝着明确定义的目标高效前进，相较于竞争利益的战略学习或独立行动的开放建模有何优势？  2. 基于LLM的代理如何通过明确定义的角色和决策流程实现有效协调，以解决协作任务解决中的挑战，例如如何分配不同角色和阶段性流程来确保任务的准确完成？  3. 在多代理系统中，如何平衡协作任务解决中的结构性和灵活性，以确保任务可靠完成，同时又不限制新兴行为的发展？
协作任务解决通过结构化工作流程协调多个代理朝着明确定义的目标前进。与涉及竞争利益的战略学习（可能涉及）或独立行动的开放建模和仿真相比，协作代理作为统一的问题解决流程的一部分。代理通常遵循明确定义的角色（如“规划者”、“执行者”或“评估者”）和阶段性流程，以确保任务的高效和准确完成。

MetaGPT[626]、CAMEL[848]、交际代理[983]以及[924]中描述的框架等系统展示了明确定义的角色、责任和决策流程如何使基于LLM的代理能够有效协调。典型的工作流可能涉及一个代理分析问题陈述，另一个提出解决方案概要，第三个实施部分解决方案，第四个验证正确性。这些代理之间的沟通通常通过自然语言“对话”的迭代轮次进行，利用LLM固有的语言生成能力。这种结构化方法对于扩展到更雄心勃勃的项目也是有益的，因为子任务可以委托给具有特定领域提示或训练的专门代理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.3 Collaborative Task Solving with Workflow Generation/section/1/text
1. 在科学研究领域中，协作任务解决系统如何利用多代理设计来有效反映科学探究的迭代性质？ 2. 在软件开发和科学研究中，明确定义的协议如何帮助多代理系统保持连贯性并避免工作重复？ 3. 在Agent Laboratory等系统中，多代理设计在结构化科学工作流程中的应用如何提高科学发现的效率和质量？
最近，在软件开发场景中广泛探讨了协作任务解决系统（例如，多代理编码、调试和测试）。然而，科学发现代表了一个特别突出和引人注目的应用。例如，Agent Laboratory利用代理在结构化科学工作流程中：提出假设、设计实验、分析结果和完善后续探究，有效地反映了科学探究的迭代性质。类似的多代理设计可以应用于文献综述、政策起草或大规模数据分析等任务，利用明确定义的协议来保持连贯性，避免工作重复。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.3 Collaborative Task Solving with Workflow Generation/section/2/text
1. 协作任务解决相对于其他基于LLM的多代理范式，为什么更注重清晰性和可预测性？这种结构化方法如何确保任务高效完成？ 2. 在需要精确性、责任制或顺序决策的领域，为什么协作任务解决的结构特别有优势？研究如何在结构和灵活性之间取得平衡？ 3. 如何利用基于LLM的语言生成能力实现代理间的沟通，以确保协作任务解决的可靠、高质量的任务完成？
相较于其他基于LLM的多代理范式，协作任务解决固有地优先考虑清晰性和可预测性：每个代理的角色和目标都是预先定义的，限制了新兴或混乱行为。这种结构在需要精确性、责任制或顺序决策的领域特别有优势。同时，正在进行研究以在结构和灵活性之间取得平衡，确保代理有足够的自主权创造性地提供解决方案，同时遵循共享工作流程，最终确保可靠、高质量的任务完成。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.3 Collaborative Task Solving with Workflow Generation/section/3/text
1. 基于LLM的多代理系统如何利用语言生成能力来解决超越传统代理设计的挑战？ 2. 在战略学习、建模与仿真以及协作任务解决这三个维度中，基于LLM的多代理系统是如何展示广度的？ 3. 为什么在多代理系统中，协作任务解决更注重清晰性和可预测性，而研究又致力于平衡结构和灵活性？
讨论：前述三个维度——战略学习、建模与仿真以及协作任务解决——展示了基于LLM的多代理系统的广度。每个类别都涉及不同的研究问题和现实应用，利用基于语言的推理来解决超越传统、纯数值或规则驱动代理设计能力范围之外的挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.4 Composing AI Agent Teams/section
在多智能体系统中，智能体的分类为同质或异质，对系统功能至关重要。同质智能体共享能力和行动空间，适用于任务并行化，提高整体效率。研究表明，同质智能体可用于团队合作任务，如家庭劳动分工和流行游戏。相反，异质智能体的多样性提高了协作结果，因为不同观点和技能丰富了问题解决策略。异质性可体现在个性、观测和行动空间上，影响智能体的决策和协调。在基于LLM的系统中，智能体可通过与环境互动自主演化，从同质到异质的转变展示了系统的动态性和灵活性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.4 Composing AI Agent Teams/section/0/text
1. 在多智能体系统中，同质智能体的主要优势是什么，如何帮助提高整体效率？   2. 异质智能体相较于同质智能体在协作结果上有何不同，其多样性如何影响问题解决策略的丰富性？   3. 在基于LLM的系统中，智能体如何通过与环境互动实现从同质到异质的转变，这种转变展示了系统的哪些动态性和灵活性？
在多智能体系统中，智能体是系统内相互交互的核心单元，对系统的功能至关重要。这些智能体可以根据它们是否共享相同的个性、能力和行动空间而被分类为同质或异质。

同质智能体共享相同的能力、行动空间和观测空间。与单一智能体系统相比，其主要优势在于任务并行化，允许多个智能体同时处理任务的不同部分，提高整体效率。它们通常用于较为简单、协调的任务，智能体之间的统一性可以推动性能的提升。

一些研究已经将同质智能体应用于模拟游戏中的团队合作，如《Overcooked》和《Minecraft》，以及现实世界任务，比如家庭劳动分工。[924]提出了一个受认知启发的模块化框架，使基于LLM的智能体能够通过自然语言进行通信，执行劳动分工，相互请求帮助，并协作完成物体运输任务。[984]将基于提示的组织结构引入框架中，减少了智能体之间的沟通成本，在家庭任务（如准备下午茶、洗碗和准备餐点）中提高了团队效率。此外，一些研究[926,925]在流行游戏中（如《Overcooked》和《Minecraft》）使用多个基于LLM的智能体，探索它们合作完成任务的能力。根据游戏设置，这些智能体也是同质的。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.4 Composing AI Agent Teams/section/1/text
1. 异质智能体如何通过提供不同观点和技能来丰富多智能体系统中的问题解决策略？ 2. 在多智能体系统中，异质性在何种程度上影响智能体之间的协作结果？如何利用异质性来提高整体协作效率？ 3. 在基于LLM的系统中，智能体如何通过与环境互动实现从同质到异质的转变？这种转变如何展示系统的动态性和灵活性？
异质智能体的多样性在改善协作结果中起着至关重要的作用。研究表明，智能体之间的异质性可以增强问题解决能力，因为不同的智能体为手头的任务带来了不同的观点和技能。异质性有助于丰富问题解决策略，提高多智能体系统中的整体协作。智能体的异质特征可以在以下维度中体现：个性层面的异质性、观测空间的异质性和行动空间的异质性。需要注意的是，这些异质性并不是相互排斥的——一个异质智能体可能表现出其中一个或多个特征。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.4 Composing AI Agent Teams/section/2/text
1. 在基于LLM的异质多智能体系统中，个性层面的异质性如何影响智能体的问题解决能力和相互交互方式？    2. 异质智能体在软件开发和医学诊断等领域中扮演不同角色，如何利用其独特观点和专业知识来增强决策制定的健壮性？    3. 异质多智能体架构中的角色特定增强如何可以简化和优化任务执行，促进更好的决策制定和创新，尤其在复杂的跨学科任务中？
·个性层面的异质性。指代智能体配置文件的多样性，影响智能体如何解决问题并相互交互。目前大多数基于LLM的异质多智能体系统属于这一类别[987, 627, 50, 970]。例如，在软件开发中，智能体可能扮演程序员、产品经理或测试人员等角色。在医学诊断中，智能体可能代表心脏病专家、肿瘤学家或儿科医生，每个人都有不同的专业领域。每个角色的独特观点和专业知识有助于更加健壮的决策制定。尽管这些异质智能体可能共享相同的行动空间——比如撰写文件[626]（例如代码、需求报告或测试报告）或提供诊断建议[922]——但他们的人设影响了这些行动的结果，多智能体架构中的角色特定增强已被证明可以显著简化和优化任务执行。例如，执行撰写文档动作的产品经理会生成需求报告，而执行相同动作的程序员会生成软件实现代码[626]。这种多样性有助于更好的决策制定和创新，特别是在复杂的跨学科任务中。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.4 Composing AI Agent Teams/section/3/text
1. 观测空间的异质性如何在多智能体系统中影响智能体的决策过程和与其他智能体的协调？ 2. 在多智能体系统中，观测空间的异质性如何促进智能体之间的信息交换和沟通，从而影响系统整体的效率和表现？ 3. 在智能体的观测空间异质性中，不同智能体角色的差异如何影响他们在协作任务中的策略选择和团队合作模式？
·观测空间的异质性。在多智能体系统中，智能体感知和解释环境的能力可能存在差异。观测空间的异质性指的是智能体在其环境中能够观察或感知的差异。例如，在狼人游戏中，一些智能体（如狼人）可以看到队友的身份，而预言家可以获取指定玩家的身份，而其他一些智能体（如村民）则无法看到任何玩家的真实身份。类似地，在阿瓦隆游戏中，不同的角色具有不同的观测空间，从而影响玩家的策略和沟通。在这些情境中，每个智能体的感知能力或观测空间与其在系统中的角色直接相关。在多智能体系统中，智能体能够观察到的差异通常会影响它们的决策、沟通和与其他智能体的协调。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.4 Composing AI Agent Teams/section/4/text
1. 行动空间的异质性如何在虚拟环境和实际环境中影响智能体的合作策略和学习过程？ 2. 在多智能体系统中，智能体如何根据其具有的独特能力有效地分配任务，实现整体任务的协作完成？ 3. 异质性智能体之间如何根据各自的优势有效地协作和协调行动，以实现系统整体的灵活性和动态性？
·行动空间的异质性。另一方面，这指的是由于物理或功能约束而导致的智能体可以执行的行动的根本差异。这在虚拟环境和实际环境中尤为重要，因为智能体可能根据其设计或目的而具有不同的能力。在类似《狼人》和《阿瓦隆》等游戏的虚拟环境中，不同的角色具有独特的能力或技能。例如，在《狼人》中，狼人可能有秘密交流的能力，而村民可能仅限于投票或观察。这种动态要求智能体根据其独特的能力进行合作，并促进学习策略，如团队合作、信任和欺骗。同时，在机器人领域，智能体可能表现出多样化的物理能力。例如，正如[988]中所描述的，一些机器人缺乏机动性，只能操纵物体，而另一些专门用于移动，但无法操纵物体。在这种情况下，具有不同行动空间的智能体必须有效地分配任务，利用其特定能力来承担适合自己的任务部分，最终合作完成整体任务。这种异质性要求智能体有效地协作和协调它们的行动，通常根据它们各自的优势来分配任务。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.4 Composing AI Agent Teams/section/5/text
1. 基于LLM的多智能体系统中，智能体从同质到异质的演变过程中，不同轨迹的形成主要受到哪些因素的影响？ 2. 在多次模拟中，智能体如何通过与环境和其他智能体的互动逐渐展现出异质行为？这种行为转变是如何影响系统整体的动态性和灵活性的？ 3. 在智能体发展出不同角色、语言使用模式和个性后，系统中的协作和决策过程可能会受到怎样的影响？
从同质到异质的演变在一些基于LLM的多智能体系统中，智能体具有通过与环境互动自主演化和持续适应的能力。由于LLM模型和环境中固有的随机性，这些智能体的演化通常会遵循不同的轨迹。即使智能体最初具有同质的人设和行动空间，也可能在多次模拟中出现异质行为。例如，正如[989]所示，起初具有相同行动空间和人设的智能体在与环境和其他智能体多轮互动后发展出不同的角色。一些智能体专注于食物采集，而其他人则专注于制造武器。类似地，[990]观察到最初同质的智能体在群体互动后发展出不同的语言使用模式、情感表达和个性。这些新兴行为展示了从同质到异质系统的转变的可能性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/section
在"代理交互协议"章节中，首先对消息类型进行分类，强调结构化消息和非结构化消息在多代理通信中的互补作用。结构化消息如JSON、XML适用于高效、确定性任务，而非结构化消息如自然文本、图像传达更丰富信息，适用于模糊任务。接着讨论了通信接口设计，强调智能代理通信接口对代理在特定环境中执行有效动作的关键性。不同环境需要不同动作，因此各种框架确保代理适应各环境。最后，探讨了下一代通信协议的发展，如智能体互联网（IoA）、模型上下文协议（MCP）、Agent Network Protocol（ANP）和Agora，为实现大规模、互操作的代理生态系统奠定了基础。尽管目前仍处于早期阶段，但协议设计是智能代理系统快速发展的前沿领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/section/0/text
1. 在智能代理系统中，结构化消息和非结构化消息各自的优势和应用场景是什么，它们如何相互补充并促进多代理通信的效率和效果？  2. 在讨论智能代理与环境、其他智能体以及人类之间的通信界面设计时，为实现透明信息交换和提高系统互操作性，接口标准化的具体作用是什么？如何确保接口标准化能够为多智能体系统的发展带来哪些优势？  3. 统一通信协议在智能代理系统中的重要性体现在哪些方面？它是如何促进智能体与环境、智能体用户之间交互设计的原则和要求的实现的？统一通信协议如何为基于LLM系统的各种应用提供一致性和功能上的连贯性？
在本节中，首先将对典型消息类型进行分类，提供有关智能体相互作用的内容和交换模式的清晰视图。接下来，将讨论智能体与环境、智能体与智能体以及智能体与人类之间的通信界面设计。将讨论透明信息交换的架构问题和协议规范。接口标准化将受到特别关注，这对于为多智能体系统提供互操作性、可扩展性和效率至关重要。该部分将以统一通信协议讨论结束，其中将讨论智能体与环境或智能体用户交互设计原则和要求，同时为基于LLM系统的各种应用提供清晰、一致和功能上的连贯性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.1 Message Types/section
在基于LLM的多代理通信中，结构化消息和非结构化消息发挥着互补的作用。结构化消息如JSON、XML和代码，具有明确的语法和语义结构，促进了信息准确性和系统可靠性，适用于高效、确定性的任务。相比之下，非结构化消息如自然文本、图像和音频信号，传达更丰富的、上下文相关的信息，适用于模糊、创造性的任务。结构化消息适合操作性和确定性操作，而非结构化消息适合处理复杂、动态情境。这两种消息模式共同为多代理系统的自适应、有效合作奠定了基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.1 Message Types/section/0/text
1. 结构化消息在多代理系统通信中的关键作用是什么？它们相对于非结构化消息的主要优势是什么？ 2. 结构化消息如JSON、XML和代码如何促进信息准确性和系统可靠性？它们在多代理系统中的具体运用有哪些优势？ 3. 结构化消息与非结构化消息在多代理系统中的角色分工如何？它们如何共同为系统的自适应、有效合作奠定基础？
结构化消息，无论是JSON（[991, 992]），XML（[993, 636]），还是作为代码（[626, 627, 994]），是与LLM进行多代理系统通信的关键方面。结构化消息的主要优势在于它们具有语法和语义上定义的结构，使得理解明确且解析直观。由于它们缺乏歧义，它们促进了信息提取和处理的准确性，计算开销更小，系统可靠性更高。例如，JSON和XML可以表示特定任务的配置参数或以机器可读模式促进数据交换，而作为代码编写的消息甚至可以直接多次执行，使工作流程和自动化更简单。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.1 Message Types/section/1/text
1. 结构化消息在多代理系统中的作用主要体现在哪些方面？它们如何促进代理之间的协作和协调？ 2. 非结构化消息相较于结构化消息在多代理通信中的优势体现在哪些方面？它们如何帮助代理系统更好地理解复杂、动态情境？ 3. 在多代理系统中，如何根据任务的性质和要求来选择结构化消息或非结构化消息，以实现系统的自适应和有效合作？
结构化消息特别适用于高效、确定性的应用程序。它们对于子任务分解、子任务分配以及协作多代理架构中的代理之间协调非常有用，因为它们明确陈述操作命令。此外，由于结构化消息具有规定的形式，检索数据以及存储数据变得更加便利，系统优化和纵向分析也变得可行。

与之相反，非结构化消息，例如自然文本、视觉数据（如图像、视频）和音频信号（如语音、环境声音），具有更高的信息密度和表现能力。这些模态最适合传达细微且与上下文相关的信息。例如，图像可以传达空间关系、光照和面部表情，而视频可以传达动态的时间组织序列，例如随时间变化的状态或行为。同样，音频信号不仅传达语言信息，还传达语言外信息，例如语调、情感和语调，这对于自然且上下文感知的互动至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.1 Message Types/section/2/text
1. 非结构化消息在多代理系统中的应用中，为什么特别适合处理模糊任务和复杂真实世界环境？ 2. 如何利用基于深度学习的特征提取技术来应对非结构化数据的复杂性，以充分发挥其潜力？ 3. 预训练的LLM和多模态大型语言模型如何在多代理系统中的非结构化通信中发挥作用，以实现新的应用？
非结构化消息非常适用于模糊任务，以及复杂的真实世界环境。它们能够表达抽象思想，以及情感微妙或隐含的上下文建议，使非结构化消息非常适合创造性和以发现为导向的问题空间。然而，非结构化数据的复杂性需要高级处理技术，例如基于深度学习的特征提取，才能充分发挥其潜力。预训练的LLM（大型语言模型）以及多模态大型语言模型的进展在很大程度上减轻了这些复杂性，使得在多代理系统中实现非结构化通信的新应用成为可能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.1 Message Types/section/3/text
1. 结构化消息和非结构化消息在基于LLM的多代理通信中是如何相互补充作用的？ 2. 结构化消息和非结构化消息分别在何种情境下更适用于多代理系统的合作？ 3. 如何利用结构化消息和非结构化消息共同为多代理系统的自适应性和有效合作奠定基础？
摘要：基于LLM的多代理通信中，非结构化消息和结构化消息具有互补的作用。结构化消息提供准确性、一致性和计算效率，适用于操作性和确定性操作；而非结构化消息提供丰富的、具有上下文的表示，使代理能够处理模糊、创造性和高度动态的情境。这两种模式共同为自适应、有效的多代理合作奠定了基础。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.2 Communication Interface/section
智能代理通信接口是保证代理在特定环境中执行有效动作的关键。代理输出偏好动作后，从环境中获取反馈，成功则观察结果，失败则得到错误反馈。不同环境需不同动作，因此提出了各种框架以确保代理在各环境中适应。在多Agent系统中，自然语言通信是主要方式，基于文本或语音。结构化信息通信更高效，减少歧义性。人-代理通信旨在拓展人类认知，可采用自然语言或结构化信息形式。中心LM可解析自然语言为结构化信息，提高代理操作效率。人类也可通过结构化信息或编程方式与多代理系统交流，提高通信效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.2 Communication Interface/section/0/text
1. 如何通过结构化信息通信提高智能代理在不同环境中的适应性和操作效率？   2. 在多Agent系统中，为什么自然语言通信是主要方式？结构化信息通信相比之下有何优势？   3. 中心LM如何通过解析自然语言为结构化信息，提高代理的操作效率和人类与多代理系统的交流效率？
基于LLM的智能代理通常需要在环境中执行一次或多次动作，以执行一系列操作。从代理的角度来看，其输出到环境中的是它所偏好的内容，例如UI点击、Web请求或计算机图形角色的移动。不同环境会因其接受的动作而异，因此为了确保其动作能够执行，代理必须了解在其所处的特定环境中哪些动作是有效的，并执行适用于特定任务和特定环境的动作。代理输出其选择的动作后，将从环境中获得反馈。如果成功，将包括观察结果；如果出现错误，则会得到错误反馈。代理需要根据这些反馈采取行动。如今有各种类型的环境，代理可以在其中执行动作，例如操作系统、电脑游戏、数据库和电子商务网站。为了使代理-环境接口具有共同的接口，并使经过各种LLM训练的代理能够在各种环境中进行最小程度的进一步适应，提出了各种框架。这些框架使得更容易测试代理在各种可执行环境中的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.2 Communication Interface/section/1/text
1. 自然语言通信在多Agent系统中为何是主导方式？这与大型语言模型的语言能力和任务需求有何关系？ 2. 在多Agent系统中，基于结构化信息与基于自然语言的通信方式相比具有哪些优势？这些优势如何影响代理之间的通信效率和成本？ 3. 为什么在多Agent系统中，将信息结构化为不同组件有助于提高代理之间的通信效率？这种结构化信息交换方式相比于其他方式有何独特优势？
在多Agent系统中，通过自然语言进行通信是主导方式。这可能是因为大型语言模型具有强大的语言能力，这是由于在大规模自然语言语料库上进行预训练。另一个可能的原因是，对于许多任务来说，自然语言通信已经足以满足需求。根据交换的信息类型，多Agent系统可以被分类如下：基于自然语言的系统在利用自然语言的LLM多Agent系统中，基于文本的通信是最常见的。还有一些系统使用语音作为通信媒介。在这些系统中，代理通过自然语言进行行为，如讨论、谈判、说服或批评，以实现它们的目标。基于结构化信息的系统与自然语言相比，结构化信息具有更高的一致性、更低的解析复杂度和减少的歧义性，使其更适合于代理之间的高效、低成本通信。在一些实现中，代理之间交换的信息被结构化为不同的组件，以便接收代理更容易解析和利用。例如，交换的信息可能包括指定发送者、接收者、消息类型以及接收方应如何解析或使用内容的字段。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.2 Communication Interface/section/2/text
1. 多代理系统中人-代理通信的结构化信息形式相比于自然语言形式的优势在哪里？如何提高了代理的操作效率？    2. 在人类与代理之间的交流过程中，中心LM的作用是什么？它如何帮助代理更有效地进行操作？  3. 人类如何通过结构化信息或编程方式与多代理系统进行交流，从而提高通信效率？这种方式相比于自然语言交流有哪些优势？
人-代理通信
开发多代理系统的目的是拓展人类能力和认知的边界，最终为人类福祉提供服务。在一些社会仿真多代理系统中，人类主要作为观察者存在，但大多数多代理系统允许人类以各种形式参与。在这种参与过程中，人类需要与代理进行交流，这种交流可以采用自然语言或结构化信息的形式。当人类与代理之间的交流主要依赖自然语言时，一个单一的LLM通常充当中心枢纽，将人类的自然语言解析为结构化信息，以便代理可以更有效地进行后续操作。这个中心LM可以存在于多代理系统内部，也可以独立于系统运作。为了节省时间并提高通信效率，人类还可以使用结构化信息通过编程或类似方法与多代理系统进行通信。通过遵循预定义的通信协议，人类可以向多代理系统发送包含所需数据的消息。系统将根据内部逻辑处理消息和数据，并返回结果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.3 Next-Generation Communication Protocols/section
新一代智能代理通信协议的发展旨在解决当前碎片化、孤立的智能体系统通信挑战。智能体互联网（IoA）支持动态团队形成，而模型上下文协议（MCP）专注于结构化工具和数据访问。Agent Network Protocol（ANP）实现去中心化通信，而Agora提供灵活的语言驱动协议机制。这些协议在身份安全、协商能力、灵活性和中心化程度上存在差异，为实现大规模、互操作的代理生态系统奠定基础。尽管当前框架是早期步骤，但协议设计仍是智能代理系统快速发展的前沿领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.3 Next-Generation Communication Protocols/section/0/text
1. 当前智能代理系统中缺乏统一的通信框架导致了哪些具体问题，以及这些问题对代理生态系统的发展和应用有何影响？  2. 在智能代理通信协议设计中，人类学习和实施定制协议的负担如何影响代理系统的发展和效率？是否存在替代手工设计协议的方法？  3. 在智能代理领域中，如何解决多智能体系统、工具、环境和数据源独立运作所带来的互操作性和共享能力挑战？
基于LLM的智能代理领域仍处于起步阶段。开发者通常设计针对特定领域或任务的代理架构和通信机制，包括代理与环境、代理与人类以及代理之间的交互。然而，大多数现有系统缺乏统一的通信框架，导致碎片化、孤立的生态系统。多智能体系统、工具、环境和数据源通常独立运作，使得代理难以互操作或共享能力。此外，学习和实施定制协议的负担落在人类身上，几乎所有当前的协议都是手工设计的——这是一个劳动密集型过程，通常缺乏语义灵活性或可扩展性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.3 Next-Generation Communication Protocols/section/1/text
1. IoA的基于FSM的对话模板如何促进了智能体之间的动态团队形成和任务驱动的协作？   2. 在智能体通信协议中，IoA采用的灵活消息格式如何帮助代理适应不同的协调阶段？   3. 智能体互联网（IoA）与传统即时通讯架构在支持动态团队形成和任务驱动协作方面有何不同之处？
为了解决这些问题，已经提出了几种新的智能体通信协议，每种协议针对协议设计堆栈的不同方面。

智能体互联网（IoA）引入了一种受互联网启发的即时通讯架构，支持动态团队形成和任务驱动的协作。代理注册到一个负责身份管理和发现的中央协调服务器。通信流程使用基于FSM（有限状态机）的对话模板进行编排。IoA支持多种消息类型，包括讨论、任务分配和触发机制，并为控制发言者轮次、嵌套组形成和最大对话长度提供了结构化字段。这使代理能够选择和调整消息格式以匹配特定的协调阶段，在固定模式内提供灵活性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.3 Next-Generation Communication Protocols/section/2/text
1. MCP采用完全集中化方法和JSON-RPC 2.0消息进行交互，这种设计有哪些优点和局限性？如何影响了智能代理系统的发展和应用？ 2. 在MCP的设计中，缺乏元协议层和语义协商能力对其功能和性能有何影响？如何影响了智能体系统在动态团队形成和数据访问方面的表现？ 3. MCP在灵活性和可扩展性上存在局限性，需要手动注册支持的函数。这种设计如何影响了智能代理系统的部署和维护成本？如何影响了智能代理系统在大规模和互操作性方面的应用？
由Anthropic开发的模型上下文协议（Model Context Protocol，MCP）[931]专注于使LLM代理能够访问结构化工具和数据。它采用基于OAuth身份验证的完全集中化方法，交互受限于JSON-RPC 2.0消息。虽然它缺乏元协议层或语义协商能力，但其简单而严格的架构使其成为具有明确定义API的工具用例的实际选择。然而，MCP牺牲了灵活性和可扩展性，需要手动注册支持的函数。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.3 Next-Generation Communication Protocols/section/3/text
1. ANP如何通过DIDs实现代理的身份识别和通过加密的点对点通道进行通信？这种身份识别方式相较于传统方式有何优势和劣势？ 2. ANP的元协议层如何帮助代理进行协议协商和选择应用级协议？这种灵活性对于智能代理系统的发展有何意义？ 3. ANP支持多种应用层协议，如HTTP、JSON-RPC和自然语言，这如何提高协议的可扩展性和去中心化特性？在支持多种协议的同时，ANP未明确支持公共协议重用可能对智能代理系统的发展产生哪些影响？
Agent Network Protocol（ANP）[1002]旨在实现完全去中心化。代理通过符合W3C标准的去中心化标识（DIDs）进行身份识别，并通过加密的点对点通道进行通信。该协议包括一个元协议层，使代理能够协商采用哪种应用级协议，支持基于代理能力的语义协议选择。ANP还允许在应用层支持多种协议（例如HTTP、JSON-RPC、自然语言），提供了强大的可扩展性和去中心化，但并未明确支持公共协议重用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.3 Next-Generation Communication Protocols/section/4/text
1. Agora的语言驱动协议机制相较于传统预定义API的优势在于哪些方面？其采用的动态解释和执行PD的方法如何影响协议的创建和使用？    2. Agora提供的去中心化协议共享方式如何促进了智能代理系统之间的互操作性和学习？相比于集中式注册表，这种方式可能存在哪些挑战或局限性？  3. 在智能代理系统的发展过程中，Agora所提供的高度灵活的协议机制如何为实现大规模、互操作的代理生态系统奠定基础？
Agora提供了一种高度灵活且以语言驱动的协议机制。代替注册预定义的API，代理可以生成并共享协议描述（PDs），这些描述是通信语义的自由文本描述。利用大型语言模型，代理可以在运行时动态解释和执行任何PD。这使得协议可以完全通过语言创建、部署和使用，无需任何手动注册或配置。Agora避免了集中式注册表，并支持去中心化的协议共享：代理可以从对等分布式存储库发布或检索PD，以实现系统间的累积学习和互操作性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.3 Next-Generation Communication Protocols/section/5/text
1. 下一代代理通信协议在身份和安全机制、元协议协商能力、应用层灵活性以及中心化程度等关键维度上的差异如何影响代理生态系统的发展和互操作性？ 2. 为什么一个统一的、安全的、可扩展的和动态的协议基础设施对于实现大规模、互操作的代理生态系统至关重要？ 3. 在智能代理系统的快速发展中，协议设计如何扮演着关键的前沿领域角色？
总结：如表13.1所示，下一代代理通信协议在身份和安全机制、元协议协商能力、应用层灵活性以及中心化程度等关键维度上存在差异。一个统一的、安全的、可扩展的和动态的协议基础设施，代理可以在其中协商和共同创建协议，对于实现大规模、互操作的代理生态系统至关重要。尽管当前的框架如MCP、ANP、Agora和IoA代表了早期但有前景的步骤，但协议设计仍然是智能代理系统发展中快速发展的前沿领域。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.3 Next-Generation Communication Protocols/section/6/table
1. 在四种代理通信协议中，哪种协议在身份安全方面表现最出色？这种协议采用了什么样的身份验证机制来确保通信的安全性？  2. 在谈判和执行层方面，ANP和Agora这两种协议有何不同之处？它们分别如何支持代理之间的协商能力和灵活性？
表13.1：跨身份、谈判和执行层比较四种代理通信协议（MCP、ANP、Agora、IoA）。 $\mathbf{PD}=$ 协议描述；DID：去中心化标识符；LLM：大型语言模型；FSM：有限状态机

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/13.5 Agent Interaction Protocols/13.5.3 Next-Generation Communication Protocols/section/7/table
1. 在基于LLM的多智能体系统分类框架中，不同通信协议如ANP和Agora如何影响系统设计和协作任务解决的方式？  2. 在智能代理系统中，采用不同的协议设计对于实现大规模、互操作的代理生态系统有何意义？
表13.2：基于LLM的多智能体系统的分类框架，突出系统设计、通信、协作和演化的不同方面。以下是为方便参考而使用的缩写：$\mathbf{M}\&\mathbf{S}=$ 建模与模拟，$\mathbf{CTS}=$ 协作任务解决，$\mathrm{SL}=$ 战略学习，$\mathbf{S-D}=$ 静态分散式，$\mathbf{S-L}=\mathbf{S}$ 静态分层，${\mathrm{Hom}}=$ 同质的，Het $\mathbf{\tau}=\mathbf{\tau}$ 异质的，$\mathbf{T}/\mathbf{M}=$ 教学/指导，$C{\mathrm{-}}0=\left.\left\langle\right.$ 以共识为导向，$\mathbf{\partial}_{\mathbf{T}-\mathbf{O}}=$ 任务导向，${\mathrm{CL}}=$ 协作学习，Dict $\mathbf{\tau}=\mathbf{\tau}$ 独裁的，$\mathbf{D-B}=$ 辩论型，$\mathrm{CI}=$ 集体智能，Ind $\c=$ 个体。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/section
本节探讨了基于LLM的多智能体系统中的系统拓扑结构。首先介绍了静态拓扑结构，通过固定连接模式确保代理之间稳定连接，但存在灵活性不足的缺点。随后讨论了动态拓扑结构，能根据性能指标和环境变化灵活调整代理之间的连接，平衡一致性和响应性。最后探讨了可伸缩性挑战和权衡，借鉴了分布式处理和自组织研究成果，强调了在平衡系统成本、性能和鲁棒性方面的重要性。子章节中详细介绍了静态拓扑结构中的分层、分散式和集中式结构，以及动态和自适应拓扑结构的优势和挑战，强调了动态结构在应对开放式环境和任务需求变化方面的重要性，但仍需解决泛化能力和资源效率等挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/section/0/figure
1. 针对静态拓扑结构和动态拓扑结构，哪种在多智能体系统中更适合应对环境变化和任务需求的挑战？     2. 在探讨多智能体系统中的系统拓扑结构时，如何平衡系统成本、性能和鲁棒性这三个方面的重要性？
图14.1：多智能体协作的不同拓扑结构类型。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/section/1/figure
1. 在图14.2中，协作和竞争代理之间的连接模式有何不同？这种不同连接模式对系统整体性能有何影响？  2. 在多智能体系统中，如何设计动态拓扑结构以实现代理之间的协作和竞争，并同时保持系统的稳定性和灵活性？
图14.2：协作和竞争代理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/section/2/text
1. 静态拓扑结构和动态拓扑结构在多智能体系统中的优缺点分别是什么，如何影响系统的稳定性和灵活性？ 2. 在多智能体系统中，如何平衡系统成本、性能和鲁棒性这三个方面的挑战？动态拓扑结构如何应对这些挑战？ 3. 多智能体系统中的动态拓扑结构如何应对开放式环境和任务需求变化这两方面的挑战？在解决泛化能力和资源效率方面存在哪些挑战？
本节探讨了基于LLM的多智能体系统（MAS）中的交互类型学及其对通信、协作和任务执行的影响。我们首先分析了静态拓扑结构，其中连接模式由领域知识固定——然后探讨了根据性能指标、工作量变化或战略约束调整智能体间连接的动态（自适应）拓扑结构。最后，我们讨论了在平衡系统成本、性能和鲁棒性方面的可伸缩性挑战和权衡，借鉴了分布式处理、自组织和新兴协作行为的最新研究成果。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.1 Static Topologies/section
静态拓扑结构在智能代理系统中扮演着重要角色，通过预定义的结构模式确保代理之间的连接稳定且可预测。分层结构将代理按层次排列，类似于传统管理框架，有助于模块化和性能监控，但可能导致上层代理负荷过大。分散式结构中，代理相互作用形成网络，增强容错性和可伸缩性，但需要复杂的共识协议。集中式结构依赖主协调器，提供更好的控制和全局视图共享，但可能出现瓶颈和通信开销增加。静态拓扑的优势在于确定性和简便性，然而缺乏灵活性，无法实时响应变化，可能导致系统性能低下，特别在动态环境下。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.1 Static Topologies/section/0/text
1. 分层结构在智能代理系统中的应用有哪些优势和局限性？如何权衡其对性能监控和模块化的贡献与可能产生的瓶颈问题？    2. 在动态环境下，静态拓扑结构的缺乏灵活性可能导致系统性能低下。针对这一挑战，如何设计一种灵活性更强的拓扑结构以实现实时响应变化的需求？  3. 静态拓扑结构中的分散式和集中式架构分别具有哪些特点和应用场景？它们在容错性、可扩展性和通信开销方面有何区别？
静态拓扑结构由预先确定的结构模式定义，在系统执行过程中基本保持不变。在这些配置中，代理之间的连接，或者代理与中央协调器之间的连接，是通过固定规则和启发式方法建立的，确保可预测的通信流和简化的协调。通常考虑三种经典形式：分层（层次化）、分散式和集中式架构。

分层（层次化）结构
分层拓扑将代理按层次排列，高层代理协调或监督低层代理。这种方法类似于传统的管理框架，例如标准操作规程（SOP）或瀑布模型，其中任务被分解为顺序、明确定义的阶段。例如，AutoAgents框架分配角色（例如，规划者、代理观察者和计划观察者）以综合执行计划，而ChatDev利用分层任务分解来简化软件开发。尽管分层结构有助于调试、性能监控和模块化，但当上层代理超负荷时可能会产生瓶颈。最近在叙事和数据科学应用领域，包括数据清洗、可视化和自动机器学习等方面的研究，突显了一致性与自适应实时行为之间的权衡。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.1 Static Topologies/section/1/text
1. 在分散式结构中，代理之间如何相互作用，以增强系统的容错性和可伸缩性？ 2. 为了在分散式系统中实现全局状态的一致性，为什么需要复杂的共识和同步协议？ 3. 如何通过分解策略有效地委派子任务，以提高分散式系统的性能和效率？
分散式结构
在分散式拓扑中，代理在对等基础上相互作用，没有中央协调器，形成的网络通常被建模为链、环、小世界或随机图[121,971]。这种结构增强了容错性，因为单个代理的故障不会危及网络。例如，[1022]表明，将图推理任务分布在多个代理之间可以实现超出单个LLM上下文长度限制的可伸缩性。此外，[1023]提出了分解策略，允许编排LLM有效地委派子任务。然而，在分散式系统中保持一致的全局状态需要复杂的共识和同步协议。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.1 Static Topologies/section/2/text
1. 集中式结构中的主协调器在智能代理系统中的作用是什么，以及它如何影响资源处理和全局视图共享？ 2. 集中式拓扑结构可能出现的问题包括哪些，例如瓶颈、通信开销和对故障的敏感性，这些问题如何影响系统的性能和可靠性？ 3. 集中式架构在保证一致性的同时，可能面临的挑战是什么，特别是在动态环境中缺乏灵活性的情况下，如何解决这些挑战？
集中式结构

集中式拓扑依赖于一个主协调器，该协调器收集信息并按层次指导外围代理。这种设置允许更好地控制资源处理和共享全局视图，例如文化公园和Lyfe代理。然而，随着额外代理的增加，中心节点可能出现瓶颈，通信开销增加，对故障的敏感性也增加。当前关于协调器-代理配置的研究以及确保集中式配置的自治性的研究指出了与一致性和可伸缩性相关的问题。虽然集中式架构可以保证一致性，但不一定具备动态适应性的灵活性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.1 Static Topologies/section/3/text
1. 静态拓扑结构在智能代理系统中如何确保通信模式的可预测性和有效的代理间协调？这种预定义结构模式如何影响系统的灵活性和实时响应能力？  2. 静态拓扑结构相对于其他结构的优势在于简便性和维护的简单性，这种简便性是如何体现在设计、执行和维护过程中的？静态结构的明确定义如何有助于资源处理和模块化？  3. 静态拓扑结构适用于哪些特定领域和场景？它如何在任务工作流程静态、有预定义角色以及系统需求明确定义的情况下发挥作用？
简而言之，静态拓扑具有确定性和预定义的优势。通过预定义的结构模式，这些系统具有可预测的通信模式和有效的代理间协调。这些结构的拓扑通常基于结构知识或静态规则定义，因此适用于任务工作流程静态、有预定义角色以及系统需求明确定义的领域。第二个主要优势是设计、实施和维护的简便性。由于结构预定义，设计和执行程序变得更简单，因此维护过程更简单。由于静态结构明确定义，资源处理和模块化变得更简单。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.1 Static Topologies/section/4/text
1. 静态拓扑结构在智能代理系统中缺乏灵活性的根本原因是什么？如何影响系统在动态环境下的有效性？ 2. 静态拓扑结构无法实时响应变化可能导致哪些具体问题，特别是在面对突发代理故障或系统目标修改时会出现怎样的挑战？ 3. 如何解决静态拓扑结构缺乏灵活性所带来的问题，以提高智能代理系统在动态环境中的性能和有效性？
然而，静态拓扑本身缺乏灵活性，基于预先指定的连接模式，无法响应实时变化。虽然在设计时适用于特定目的，但完全缺乏对未预见挑战的灵活性，包括突发代理故障、任务复杂度不同以及系统目标修改。静态拓扑缺乏实时响应灵活性潜力，这种实时响应的不灵活性抑制了运行时系统重配置，并降低了在动态环境中系统的有效性。未能根据新出现的情况进行自组织和变形可能导致低效以及系统性能低下，特别是在动态或新兴环境下。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.2 Dynamic and Adaptive Topologies/section
动态和自适应拓扑结构在代理系统中的重要性日益凸显。相较于静态拓扑结构，动态结构更适用于开放式或新领域，因为它能够根据任务需求、资源变化和环境反馈实时调整代理之间的关系，平衡一致性和响应性。各种框架如DyLAN、OPTIMA和MAD展示了动态拓扑结构的实现方式，通过优化代理之间的连接、动态团队重组和角色分配，实现了灵活性和性能的平衡。随着技术进步，拓扑控制变得更加可行，如GPTSwarm和MACNET采用不同的图结构和优化策略。然而，动态拓扑结构仍面临泛化能力、资源效率和推理效率等挑战，未来研究应关注多任务领域泛化、成本降低和推理资源动态分配等方面的改进。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.2 Dynamic and Adaptive Topologies/section/0/text
1. 静态拓扑结构和动态拓扑结构在代理系统中的应用场景有何不同，以及它们分别体现了哪些特点和优劣势？  2. 在动态拓扑结构中，代理之间如何根据任务需求、资源变化和环境反馈实时调整其关系？这种实时调整如何平衡了一致性和响应性？  3. 未来研究如何应对动态拓扑结构面临的挑战，特别是在多任务领域泛化、成本降低和推理资源动态分配等方面的改进方向？
尽管静态拓扑结构提供了确定性和可预测性，例如在稳定任务领域和定义明确角色中表现良好的分层或中心化的静态拓扑结构所展示的，但静态拓扑结构并不适用于开放式或新领域。真实领域，从实时协作计划到动态社会模拟，通常要求代理根据工作进行更改其互动模式，可用资源变化，或接收到来自环境的反馈。这种与适应性可塑性的结构张力产生了动态拓扑结构，这些结构在运行时根据对性能、工作负载或战略约束的反馈，重新构建代理之间的关系，以在一致性和响应性之间取得平衡。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.2 Dynamic and Adaptive Topologies/section/1/text
1. 动态拓扑结构在代理系统中的重要性体现在哪些方面？它相较于静态拓扑结构的优势是什么？  2. DyLAN、OPTIMA和MAD等框架如何实现动态拓扑结构？它们的优化策略和方法有何异同之处？  3. 在面临泛化能力、资源效率和推理效率等挑战时，未来研究如何改进动态拓扑结构在多任务领域泛化、成本降低和推理资源动态分配方面的应用？
例如，DyLAN框架通过两步流程支持推理时代理选择，即通过无监督代理重要性评分进行前向后向团队优化步骤，随后在运行时进行动态团队重组。类似地，OPTIMA通过生成-排名-选择-训练框架迭代地优化代理之间的连接，利用奖励函数作为确定任务质量、代币效率和可读性之间平衡的手段，通过诸如直接偏好优化等策略进一步优化通信行为。MAD框架通过三个提示阶段和结构的联合优化展示了灵活性，通过动态角色分配（例如验证者和辩论参与者）在结构的修剪空间内进行。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.2 Dynamic and Adaptive Topologies/section/2/text
1. 动态拓扑结构在代理系统中的应用中，GPTSwarm和MACNET采用了不同的图结构和优化策略。这些不同的结构和策略如何影响代理之间的协作和性能表现？  2. 在大规模系统中，如何解决动态拓扑结构所面临的挑战，例如泛化能力、资源效率和推理效率？MACNET系统中的小世界发展如何与图推理思想相符，以实现更好的协作和规避局部限制？  3. 在动态拓扑结构中，如何有效利用外部参数配置以优化代理之间的连接、团队重组和角色分配？AutoAgents中提到的动态起草-执行流水线是如何帮助代理共同勾画专家团队，并在创意应用中实现高效的新颖生成？
随着技术的进步，拓扑控制也变得可行。GPTSwarm[651]将代理构想为计算图，并利用进化策略和强化学习来根据任务反馈调整邻接矩阵以优化节点。MACNET[1028]采用有向无环图架构，监督教练管理边缘，执行助手管理节点，用于更复杂的协调领域，通过拓扑排序和输出的敏感传播促进自适应通信。特定应用版本也强调架构多样性。开放世界环境中有DAMCS[1029]，它将分层知识图（A-KGMS）与结构化通信方案（S-CS）相结合，基于上下文传递的消息进行协作规划。AutoAgents[1030]利用动态起草-执行流水线，预定义代理共同勾画专家团队，这种设计对于创意应用（如通过并行处理和内部监督进行新颖生成）非常有效。值得注意的是，在大规模MACNET[1028]系统中的小世界发展与[1022]中展示的图推理思想相符，分布式架构通过结构化协作规避了LLM的局部限制。在协作任务解决方面，出现了几种强调动态拓扑作用的范式。这些范式包括基于搜索的方法、基于LLM的生成，以及利用外部参数的配置。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.2 Dynamic and Adaptive Topologies/section/3/text
1. 如何基于搜索的方法在代理系统中实现通信结构的优化？这种方法如何利用元代理搜索算法和蒙特卡洛树搜索（MCTS）来实现动态扩展和优化工作流程？  2. 在基于搜索的方法中，MAD和OPTIMA框架是如何整合迭代生成-排名-选择-训练范式的？这种整合如何与MCTS原则相呼应，以实现任务性能和效率的平衡？  3. 基于搜索的方法在代理系统中的优化中，如何通过存档优越配置来更新后续的生成策略？这种策略如何帮助实现通信结构的迭代优化？
基于搜索的方法
一些作品采用基于搜索的方法来迭代优化通信结构。例如，ADAS[741]采用元代理搜索算法，该算法在代码空间内迭代生成和测试新的代理设计，存档优越配置，从而更新后续的生成策略。类似地，Afow[773]将每个LM调用建模为图中的一个节点，并利用蒙特卡洛树搜索（MCTS）动态扩展和优化工作流程。其他框架，如MAD[1031]和OPTIMA[1027]，整合了迭代生成-排名-选择-训练范式，这些范式与MCTS原则相呼应，以平衡任务性能和效率。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.2 Dynamic and Adaptive Topologies/section/4/text
1. 如何利用LLM的生成能力构建和调整动态拓扑结构，以实现代理系统中的动态团队选择和协作规划？  2. 在基于LLM的方法中，Dylan的时间前馈网络（T-FFN）模型是如何计算代理重要性分数，并如何用于动态团队选择的？  3. AutoFlow和Flow等框架如何将任务工作流表示为自然语言程序或活动顶点图（AOV），并通过强化学习信号进行持续的细化？
基于LLM的方法
为了补充基于搜索的方法，一些最近的作品利用LLM的生成能力来构建和调整动态拓扑结构。Dylan[725]引入了一个称为时间前馈网络（T-FFN）的模型，将每个通信步骤视为一个网络层，利用前向-后向传播计算代理重要性分数，用于动态团队选择。在相关工作中，DAMCS[1029]、AutoAgents[1030]和TDAG[1032]动态生成专门的子代理或更新分层知识图，实现协作规划和任务分解。此外，AutoFlow[773]和Flow[1033]等框架将任务工作流表示为自然语言程序或活动顶点图（AOV），通过强化学习信号进行持续的细化。ScoreFlow[788]通过应用基于梯度的（损失梯度）优化来连续重新配置代理工作流程，对这些方法进行了补充。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.2 Dynamic and Adaptive Topologies/section/5/text
1. 如何通过训练与LLM代理独立的参数来配置代理间拓扑结构，以提高代理系统的性能表现？  2. AgentPrune如何通过基于幅值的修剪来识别和消除通信冗余，从而优化多主体系统的拓扑结构？  3. 在多主体系统中，G-Safeguard是如何训练GNN来检测和消除恶意通信路径的，以增强系统的安全性和性能？
外部参数 鉴于微调基于LLM的代理通常需要大量资源，许多研究者主张通过训练与LLM代理独立的参数来配置代理间拓扑结构。这一方法由GPTSwarm[651]发起，其中代理间拓扑结构被表示为有向无环图（DAG），边权重作为系统唯一可训练的组件。在进一步推进这一范式的过程中，AgentPrune从时空图的角度为主流多主体系统提供了一个统一的建模框架，通过基于幅值的修剪识别和修剪通信冗余，即不必要的边。在这一研究线的后续作品包括G-Safeguard[1034]，该作品类似地训练GNN在多主体系统之外，以检测和消除恶意通信路径。尽管这些方法在参数效率上表现出色，但由于其相对较小的参数空间和与LLM代理的低耦合，往往在一定程度上会导致性能限制。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.2 Dynamic and Adaptive Topologies/section/6/text
1. 动态拓扑结构在模拟复杂社会互动中的关键作用体现在哪些方面？这种结构如何捕捉自主性、社会行为和环境反馈的实时变化？  2. 在医疗领域中，动态拓扑结构是如何优化协作和决策的？AI医院和代理医院这两个框架是如何通过动态调整代理间的沟通来重塑各种角色之间的通信模式的？  3. 如何利用动态拓扑结构中的AgentScope-scability和Social Survey等架构支持大规模多代理模拟，实现对文化传播、集体决策和新兴群体动态的研究？
讨论 动态拓扑结构不仅限于解决任务，在模拟复杂社会互动中发挥着关键作用。正如最近的一项调查所详细介绍的[975]，基于LLM的代理模型可以演化出代理间的联系，以捕捉自主性、社会行为和环境反馈的实时变化，涵盖了包括网络、物理和混合环境在内的各种领域。诸如[50]、OASI[936]和Project Sid[989]等系统模拟了动态社交网络。[50]利用生成式自然语言记忆检索来根据代理经验调整社交关系，而OASIS构建了一个实时社交媒体环境，其中用户关系和信息流持续更新。Project Sid[989]引入了PIANO（通过神经编排实现并行信息聚合）架构，使超过百个自治AI代理在Minecraft环境中实时交互，导致出现诸如专业角色、集体规则遵守、文化和宗教传播等复杂社会结构。此外，像AgentScope-scability[1035]和Social Survey[975]这样的架构支持大规模多代理模拟，实现了对文化传播、集体决策和新兴群体动态的研究，使得在涉及数百或数千个互动代理的环境中成为可能。此外，动态拓扑结构还针对特定应用领域进行了定制，如医疗和开放领域的具体应用。在医疗领域，AI医院[1036]和代理医院[921]模拟真实的医疗工作流程，其中诊断、治疗和反馈的迭代周期不断重塑各种角色之间的通信模式，如住院医生、患者、检查者和主治医师。这些框架动态调整代理间的沟通，以优化协作和决策。同样，在开放领域和具体应用的AI中，像IOA[9]这样的框架支持异构、跨设备的代理交互，促进了真实场景中动态团队形成和任务分配。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.2 Dynamic and Adaptive Topologies/section/7/text
1. 当前多代理系统拓扑结构在泛化能力方面存在怎样的限制？如何实现多代理系统的终身学习能力，以在不同任务领域进行泛化并最小化资源消耗？  2. 为什么当前动态拓扑结构针对单一任务领域进行优化可能导致固定工作流程难以适应新任务领域？如何解决这一挑战，使多代理系统能够实现跨领域泛化？  3. 在动态拓扑结构中，为什么多代理系统的资源消耗（如API调用、FLOPs、GPU时数）应该被最小化？如何设计拓扑结构，以实现资源消耗最小化的终身学习能力？
尽管前述动态多代理拓扑在性能指标上取得了实质性进展，但仍面临以下三个限制，我们认为这应成为未来动态拓扑研究的重点：

(1) 泛化能力。当前多代理系统拓扑结构通常针对单一任务领域进行优化。例如，AFlow专注于在数学或代码基准中进行搜索和优化，生成难以适应新任务领域的固定工作流程。其他动态拓扑结构，如ADAS、GPTSwarm和AgentPrune，面临相同挑战。我们认为多代理系统应具备终身学习能力，在其中系统能够跨不同任务领域进行泛化，且资源消耗最小（例如API调用、FLOPs、GPU时数）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.1 System Topologies/14.1.2 Dynamic and Adaptive Topologies/section/8/text
1. 当前动态拓扑结构在资源效率方面存在哪些挑战？未来的发展应该如何解决这些挑战以提高实际应用的可行性？  2. 多代理拓扑结构在推理效率方面的不足主要体现在哪些方面？MaAS提出的代理超网络在解决这些问题上有何优势和局限性？  3. 如何在动态拓扑结构中实现推理资源的动态分配，以提高任务适应性和推理效率？
(2) 资源效率。目前的动态拓扑结构往往优化复杂、资源密集的结构。它们的训练过程通常成本高昂，ADAS[74]便是一个例子，使用GPT-3.5进行训练每次会产生大约300美元的成本。这些费用严重限制了它们在实际场景中的大规模适用性。未来的发展应该专注于实现更好的测试时拓扑优化，并显著降低成本。

(3) 推理效率。正如MaAS[787]所指出的，过度复杂的多代理拓扑结构虽然能够持续提供令人满意的性能，但在任务适应性方面存在明显不足。也就是说，它们无法根据特定任务的难度动态分配推理资源（例如工具、代理数量和推理步骤）。因此，这可能导致推理过程中某种程度的效率缺失。尽管MaAS在一定程度上通过设计的代理超网络实现了任务动态性，但它们在大规模部署中的适用性和可扩展性仍有待测试。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.2 Scalability Considerations/section
在基于大型语言模型的多智能体系统中，可扩展性是一个关键挑战。研究表明，采用有向无环图结构可以高效扩展系统规模，而将任务分配给多个代理有助于规避限制。自组织代理的动态复制和任务分配提高了整体处理能力。最近的平台设计进展如AgentScope和Sid项目展示了如何减少通信开销和同步挑战，支持大规模智能体系统。AgentSociety提供了模拟现实社会环境的框架，支持数千个智能体的互动。然而，随着智能体数量增加，协调成本可能超线性增长，存在最佳智能体群体规模的概念。混合架构结合集中式监督和分权子团队为可扩展性挑战提供了解决方案，通过分层组织和优化网络结构实现资源利用的最佳化。异步通信和部分知识共享策略有助于最小化协调瓶颈。总体而言，多Agent系统的可扩展性取决于设计选择，需要综合考虑静态配置和动态架构的平衡，未来的发展应关注自适应算法和多维度评估框架的进一步完善。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.2 Scalability Considerations/section/0/text
1. 在基于大型语言模型的多智能体系统中，为什么可伸缩性是一个关键挑战？如何通过有向无环图结构和任务分配来提高系统的扩展性？  2. 多Agent系统中存在最佳智能体群体规模的概念，这种规模是如何影响协调成本的？混合架构是如何结合集中式监督和分权子团队来解决可扩展性挑战的？  3. 在大规模智能体系统中，集中式和分层拓扑结构可能会面临哪些挑战？相比之下，去中心化网络的优势和劣势分别是什么？
在基于大型语言模型的多智能体系统（MAS）中，可伸缩性是一个关键挑战，特别是在代理数量增加的情况下。在完全连接的网络中，通信路径的数量呈二次增长，导致通信量激增，增加了令牌使用和计算成本。如果监督节点被消息淹没，集中式和分层拓扑结构可能会经历同步瓶颈，而去中心化网络虽然更具容错性，但需要复杂的共识算法来实现一致的全局状态。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.2 Scalability Considerations/section/1/text
1. 多智能体系统中采用有向无环图结构有助于系统高效扩展，那么这种结构是如何帮助系统规避性能下降的？   2. 在研究中提到的自组织代理的动态复制和任务分配如何影响系统的整体处理能力和每个代理的工作负载？  3. 多维分类法如何帮助分析代理自治和协调之间的权衡，以实现集中控制与分散灵活性的平衡，从而优化多Agent系统的可扩展性？
最近的研究（如[1028]）表明，当多智能体协作被构建为有向无环图（DAG）时，系统可以高效扩展以处理大规模图，甚至可以达到100个节点或更多，而不会出现显著的性能下降。类似地，研究（如[1022]）表明，将图推理任务分配给多个代理可以规避长文本输入和上下文长度限制所施加的限制。此外，关于自组织代理的研究（如[1038]）揭示了动态复制和任务分配使系统能够在增加整体处理能力的同时保持每个代理的恒定工作负载。最后，[1039]提出的多维分类法为分析代理自治和协调之间的权衡提供了有价值的框架，为如何平衡集中控制与分散灵活性以优化可伸缩性提供了见解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.2 Scalability Considerations/section/2/text
1. AgentScope是如何通过基于actor的分布式框架实现无缝迁移，在减少通信开销和同步挑战方面取得了哪些显著优势？ 2. 在多智能体系统中，为什么混合架构结合集中式监督和分权子团队被认为是解决可扩展性挑战的有效方案？其如何通过分层组织和优化网络结构实现资源利用的最佳化？ 3. 随着智能体数量增加，为什么存在最佳智能体群体规模的概念？混合异步通信和部分知识共享策略如何有助于最小化协调瓶颈？
除了这些基础研究外，最近在实际多智能体平台设计方面取得的进展进一步丰富了可伸缩性讨论。例如，AgentScope提供了一个面向开发者的平台，利用基于actor的分布式框架，实现在本地和分布式部署之间的无缝迁移。其统一工作流程和自动并行优化显著减少了通信开销和同步挑战，这些挑战通常会随着代理数量的增加而出现。通过整合容错机制和智能消息过滤，AgentScope展示了如何设计系统级支持，以在动态和异构的部署环境中保持性能。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.2 Scalability Considerations/section/3/text
1. PIANO架构如何通过神经编排实现并行信息聚合，从而解决模拟智能体文明领域中的可伸缩性挑战？ 2. 在Sid项目中提出的PIANO架构是如何将较慢的认知过程与快速的反应模块解耦，从而支持涉及超过一千个代理的模拟？  3. 如何通过引入专用认知控制器来确保PIANO架构中多个并行输出之间的一致性，以有效解决高频交互带来的固有协调挑战？
在模拟智能体文明领域，另一种互补方法在Sid项目中提出，该项目探讨了可伸缩性。在这里，重点从孤立任务解决转移到模拟复杂社会动态。所提出的PIANO（通过神经编排实现并行信息聚合）架构允许代理同时运行，通过将较慢的认知过程与快速的反应模块解耦。引入专用认知控制器以确保多个并行输出之间的一致性。这种设计不仅使得从小团体扩展到涉及超过一千个代理的模拟成为可能，而且有效地解决了由高频交互引起的固有协调挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.2 Scalability Considerations/section/4/text
1. AgentSociety如何通过整合基于LLM的社会生成智能体，利用分布式计算和高性能消息传递系统来支持数百万次日常互动，从而展示了可伸缩性提升到更大规模的关键优势是什么？    2. 在AgentSociety这一框架中，如何平衡有效管理通信成本、协调开销和新兴行为的准确性，以支持宏观现象如经济市场动态、舆论传播和城市规划模拟？  3. 随着智能体数量增加，如何在AgentSociety这样的大规模智能体系统中，解决协调成本可能超线性增长的挑战，以实现最佳智能体群体规模的概念？
将可伸缩性提升到更大规模，AgentSociety[1040]展示了一个全面的框架，用于模拟最多10,000个智能体的现实社会环境。通过在现实的城市、社会和经济环境中整合基于LLM的社会生成智能体，AgentSociety利用分布式计算和高性能消息传递系统（例如MQTT）来支持数百万次日常互动。这个平台展示了新兴混合架构如何通过有效管理通信成本、协调开销和新兴行为的准确性之间的权衡，来支持宏观现象，例如经济市场动态、舆论传播和城市规划模拟。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.2 Scalability Considerations/section/5/text
1. 在多智能体系统中，为什么在追求大规模智能体部署时需要考虑内存开销和智能体间通信成本？这些因素如何影响增加额外智能体的边际效用？  2. 为什么在有界问题领域可能存在一个最佳的智能体群体规模？超过该规模会导致性能达到平稳状态甚至恶化？这种现象是如何与协调成本的超线性增长相关联的？  3. 如何通过综合考虑智能体数量、任务复杂度和劳动分工程度来确定多Agent系统中的最佳智能体群体规模？这种规模的确定对系统的整体性能有何重要意义？
尽管在理论上扩大智能体群体规模具有优势，但必须质疑追求大规模智能体部署是否在所有任务解决场景中都具有内在价值。虽然总计算能力随着智能体数量的增加而扩展，但考虑到内存开销和智能体间通信成本，增加额外智能体的边际效用可能呈现递减。这种现象源于基本约束，即虽然整体工作量是个体任务复杂度和劳动分工程度的乘积，但协调成本往往随着智能体数量呈超线性增长。因此，在许多有界问题领域，可能存在一个最佳的智能体群体规模，超过该规模性能将达到平稳状态，甚至由于过多的协调开销而恶化。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.2 Scalability Considerations/section/6/text
1. 在模拟复杂社会动态和大规模集体智能时，为什么将重点从计算效率转向准确复制微观智能体相互作用产生的宏观模式？这种转变对研究和实践有何意义？  2. 在模拟场景中，如何通过扩展到众多智能体来捕捉逼真的群体层面现象？这种方法与优化任务解决的计算效率有何不同，对于研究复杂系统行为有何影响？  3. 在管理庞大智能体群体的计算开销方面，如何平衡模拟复杂社会动态的需求和系统的可扩展性？异步通信和部分知识共享策略如何帮助最小化协调瓶颈？
相反，在模拟场景中，如果目标是模拟复杂的社会动态、 emergent 行为或大规模集体智能，扩展到众多智能体不仅有益而且是必不可少的。在这些情境下，研究重点从优化任务解决的计算效率转向准确复制或预测由微观智能体相互作用产生的宏观模式。这种模拟——涵盖经济市场行为、社交网络演化和城市基础设施规划等领域——通常需要管理庞大智能体群体的计算开销，以捕捉逼真的群体层面现象。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.2 Scalability Considerations/section/7/text
1. 混合架构中集中式监督和分权子团队的结合如何在多智能体系统中提高可扩展性？   2. 在多Agent系统中，如何利用分层组织和动态调整代理团队大小来优化资源利用？   3. 异步通信和部分知识共享策略是如何帮助减少协调瓶颈，同时保持智能体之间充分全局意识的？
将集中式监督与分权的子团队相结合的混合架构为这些可扩展性挑战提供了有前途的解决方案[921,18]。在这些设计中，监督代理处理全局目标和协调，而工作代理专注于执行特定子任务。这种分层组织有助于减轻任一节点的信息过载，并允许根据任务需求动态调整代理团队大小，从而优化资源利用。此外，高级技术，如图搜索算法、基于强化学习的更新以及演化方法，在系统扩展时对网络结构进行迭代优化至关重要。智能消息过滤、优先级设定和聚合机制可以显著减少通信开销，而不牺牲智能体间协作的质量。此外，异步通信协议和部分知识共享策略显示出在最小化协调瓶颈的同时保持智能体之间充分全局意识的潜力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/14.2 Scalability Considerations/section/8/text
1. 在基于大型语言模型的多智能体系统中，如何平衡静态配置和动态架构的设计选择以提高系统的可扩展性？ 2. 多Agent系统中的可扩展性如何受到任务解决和模拟场景特性的影响？这种影响如何引导系统设计的目的特定选择？ 3. 未来基于LLM的多Agent系统在提高可扩展性和实际可行性方面，应该如何进一步发展自适应算法、分布式架构和多维度评估框架？
关于可扩展性的总结 总的来说，基于LLM的多Agent系统中对系统拓扑结构和可扩展性的研究揭示了一系列设计选择——从提供简单性和可预测性的静态配置到提供灵活性和适应性的动态架构。虽然基础性作品（例如[1028]，[1038]）强调可扩展的图结构和自组织原则，但AgentScope、Project Sid和AgentSociety所展示的实际进展表明，集成的分布式框架、并行处理和逼真的环境模拟共同应对了扩展多Agent系统的挑战。可扩展性需求的依赖于上下文的特性——在任务解决和模拟场景之间的对比突显了多Agent架构中目的特定设计的重要性。随着研究的不断发展，更复杂的自适应算法、分布式架构和多维度评估框架的发展将对推进基于LLM的多Agent系统的可扩展性和实际可行性至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collaboration Paradigms and Collaborative Mechanisms/section
本章深入研究了多智能体系统中的协作机制，探讨了智能代理如何相互影响以实现协作。通过参考人类社会结构中的互动行为，我们解释了多智能体协作的目的、形式和关系。在多智能体系统中，每个智能体都具有独特的角色、知识和目标，它们通过与其他智能体或环境的互动来解决问题和通信。智能体根据目标、知识和观察做出独立决策，并执行行动。智能体的信念由知识、记忆和环境观察构成，而不同的动机影响它们的任务处理方法。有效的问题解决需要多样化的有目的互动，包括智能体之间的互动和智能体与环境的互动，这些互动可能是多轮次的，根据系统设计朝不同方向发展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collaboration Paradigms and Collaborative Mechanisms/section/0/text
1. 多智能体系统中的协作机制如何受到智能代理之间相互影响的影响？这种相互影响是如何实现的，以促进协作的发展？  2. 在多智能体系统中，智能体的信念是如何形成的？这些信念又是如何影响智能体的任务处理方法和决策过程的？  3. 多智能体系统中的有效问题解决需要哪些类型的有目的互动？这些互动包括智能体之间的互动和智能体与环境的互动，如何确保这些互动的多样性和目的性？
在本章中，我们对这些有目的的相互作用进行了详细探讨，研究了一个代理如何影响多代理系统内的协作。我们参考了从人类社会结构中产生的多样化互动行为，进一步通过互动目的、互动形式和形成的关系来解释多智能体协作。

多智能体系统（MAS）包括在共享环境中相互作用的多个智能体，它们自主做出决策以协作完成任务或相互竞争[1041]。在我们的背景下，我们关注协作现象，因为它们广泛出现在大多数实际应用中。基本上，MAS中的每个智能体都配备有不同的角色和初始知识，以及自己的一套目标。

在解决问题或进行通信时，智能体与其他智能体或环境进行互动，收集和处理信息，根据其目标、现有知识和观察独立做出决策，然后执行行动[975,1041,1042,1043]。知识、记忆和环境观察形成了智能体的信念，而不同的动机影响了它们对任务和决策的方法[1041]。因此，有效的问题解决需要多样化的有目的互动，包括智能体之间的互动和智能体与环境的互动。这些互动可能涉及多轮次，并且根据系统设计以不同方向发生。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section
在多智能体系统中，代理之间的合作至关重要，特别是在任务导向的互动中。这种合作涉及有效的协调和任务分解策略，使代理能够共同实现共同目标。不同类型的互动包括共识导向互动、同行讨论和观察学习，以及教学/指导交互。这些交互模式强调了知识传递、经验分享和技能提升的重要性，有助于智能体解决复杂问题和提高任务执行效率。在任务导向的互动中，代理按照结构化的流程执行任务，通过明确的交付成果实现任务目标。协调机制在确保代理有效协作方面起着关键作用，包括通信协议、同步策略和资源共享技术。这些互动模式促进了智能体之间的相互理解和技能提升，为多智能体系统的发展和任务执行提供了重要支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/0/text
1. 在多智能体系统中，如何利用人际互动模式的社会学洞见来更精细地分类智能体之间的相互作用类型？这种分类有助于解决复杂问题和提高任务执行效率吗？  2. 在多智能体系统中，不同类型的智能体相互作用模式（如共识建立、技能学习、教学和任务分工合作）如何影响智能体之间的协作范式和决策过程？这些模式如何应对合作、竞争、协调和决策方面的挑战？  3. 在协作软件开发中，不同类型的智能体如何通过多种相互作用（如指导、代码审查、学习）共同解决问题并提高测试覆盖率？这些相互作用的目标和结果如何塑造智能体的行为和决策，从而增强我们对多智能体动态的理解？
考虑到多智能体系统（MAS）协作的分类，我们更详细地关注捕捉复杂多智能体相互作用中微妙动态所需的粒度。具体而言，我们将智能体间的相互作用分为四种类型，受到人际互动模式的社会学洞见的启发，并将其应用于MAS中的智能体间相互作用。人际互动的社会学理论，包括共识建立、技能学习、教学和任务分工合作，提供了一种更精细的分类智能体相互作用的方式。这些相互作用形成了协作范式，使各种智能体能够有效地共同解决复杂问题，并受到各种目标、背景和结果的影响。每种范式都涉及与合作、竞争、协调和决策相关的独特挑战。此外，MAS实现涉及具有不同类型相互作用的智能体，而不是单一类型或单向过程，形成随时间演变的复杂相互作用网络。在协作软件开发中，一位资深开发人员智能体可能会按任务与架构师智能体进行互动，通过多轮对话指导初级智能体。他们共同进行代码审查以做出决策，并与测试专家智能体学习以提高测试覆盖率。审视这些相互作用的目标和结果揭示了塑造智能体行为和决策的关键技术和技术，从而增强我们对多智能体动态的理解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/1/text
1. 共识导向互动在多智能体系统中的作用是如何促进不同知识的整合和观点的转变，从而实现最终目标的？ 2. 在共识导向互动中，智能体如何通过谈判、投票和社会选择框架来实现协调，以应对复杂问题解决情境？ 3. MedAgents、MDAgents和AI Hospital这些案例如何展示了跨学科智能体之间的协作对问题解决的改进，以及如何通过提升推理技能和获取固有知识来提高问题解决能力？
共识导向互动
共识导向互动集中于通过谈判、投票和社会选择框架来协调多智能体系统（MAS）的最终目标[1044]。这种互动对于整合不同知识、确保智能体转变观点以达成共识至关重要[1045]。在这种互动中，智能体整合知识以建立统一理解，这在需要不同观点的复杂问题解决情境中极大地有助于联合决策。例如，MedAgents [922]、MDAgents [1046] 和 AI Hospital [1036] 展示了跨学科智能体之间的协作对问题解决的改进，通过提升推理技能和获取固有知识来提高问题解决能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/2/figure
1. 在基于LLM的多智能体系统中，不同类型的代理-代理协作在信息流动、协作目的、知识整合和输出重点上有何区别？     2. 在任务为导向的互动中，代理之间如何通过明确的交付成果实现任务目标，以及协调机制如何确保代理有效协作？
图15.1：基于LLM的MAS中四种代理-代理协作类型的概述：以共识为导向、协作学习、教学/指导和任务为导向。每种类型都沿着四个关键维度进行描述：信息流动、协作目的、知识整合和输出重点。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/3/text
1. 在多智能体系统中，共识驱动的团队合作相较于传统方法有何优势？这种合作模式如何促进多智能体系统中的任务执行效率和问题解决能力？  2. 代理之间在共识导向互动中如何整合专业知识并达成一致结果？这种合作模式如何促进智能体之间的相互理解和技能提升？  3. 在科学环境中，为什么解决复杂挑战需要多元视角和细致验证？共识驱动的团队合作如何帮助智能体在Agent Laboratory和VirtualLab等案例中取得成功？
这些对话使智能体将专业知识整合到一致的结果中，通常优于传统方法，如零-shot或少-shot推理。共识驱动的团队合作的重要性在科学环境中尤为明显，在这些环境中，解决复杂挑战需要多元视角和细致验证。Agent Laboratory[746]就是一个例子，博士和博士后智能体合作达成研究目标，解释实验，并整合研究结果。类似地，VirtualLab[752]组织了一系列团队进行科学研究，所有智能体讨论科学议程，并进行个体会议，其中一个智能体完成特定任务。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/4/text
1. 多智能体共识方法中的辩论和协商在何种情况下起到不同的作用？它们如何相互配合以促进共识的建立？ 2. 在多智能体系统中，如何利用特定框架支持共识建立活动？这些框架如何帮助智能体收集和整合来自同行的输出以实现共同理解？ 3. 在共识建立过程中，智能体如何利用环境反馈的数值数据和情境细节？这种信息如何有助于智能体分享观点、假设，并逐步达成共同理解？
多智能体共识方法通常包括几种途径，包括讨论、辩论、协商、反思和投票。达成共识的常见方法包括一系列结构化技术。涉及的主要机制包括讨论、辩论、协商、反思和投票。辩论使智能体获得竞争性假设，而协商有助于解决冲突的优先事项和资源限制。已经创建了特定框架来支持这些共识建立活动。在这些过程中，智能体收集来自解决相同问题的同行的输出，并将环境反馈作为数值数据和情境细节包括其中。这些互动使智能体能够分享观点、假设，并逐步达成共同理解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/5/text
1. 多智能体系统中的协作机制对于任务执行的效率和成功有何重要作用，以及不同的互动模式如何促进代理之间的相互理解和技能提升？    2. 在GPTSwarm和RECONCILE等系统中采用的不同协作策略和互动形式如何影响智能体之间的合作效果和任务执行结果？     3. 辩论在多智能体系统中的作用是什么，MAD框架和FORD框架如何通过不同的方式促进智能体之间的创造性思维和一致性达成？
例如，GPTSwarm使用图形设计来规定智能体之间的协作，信息流和边缘连接构建了基本的团体讨论。在GPTSwarm中，如果一个智能体持续提供错误意见，它将被排除在外。RECONCILE采用圆桌讨论形式，包括多个讨论周期和基于信心水平的投票系统。它通过学习过去讨论的经验，利用信心度量和人类见解来改进其响应，融入了反思。此外，辩论对于达成一致、减少幻觉以及解决复杂问题非常重要。在GOVSIM中，智能体合作以实现平衡，并建议使用共享资源并为未来需求保存。谈判超越了简单的信息交流和关系为中心的互动。多智能体辩论（MAD）框架通过让智能体以“以牙还牙”的模式提出论点来促进创造性思维，由一位评委监督该过程以最终确定解决方案。正式辩论框架（FORD）通过组织辩论增强了语言模型之间的一致性，使更强大的模型引导共识，而较弱的模型则调整其观点。类似地，AutoAgents定义了一种协作的改进行动，其中每个智能体更新其聊天记录。在这个过程中，它还附加了另一个智能体的先前陈述，并完善其行动以达成共识。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/6/text
1. 在协作学习中，智能体之间的相似性如何影响它们的经验积累和技能提升？这种相似性对于任务解决和策略学习有何作用？  2. 共识导向的互动和协作学习互动在目标和过程上的区别是什么？这种区别如何影响智能体之间的知识整合、信念调整和个体成长？  3. 在协作学习互动中，智能体如何通过观察他人的行为来更新自己的背景或记忆？这种观察对于智能体学习最佳策略和调整方法有何重要性？
在协作学习中，交互通常发生在相似的智能体之间。尽管在架构上相似，但由于其独特的行为和不同的环境交互，它们积累了不同的记忆和经验。通过共同解决问题，这些智能体共享经验，以提升它们的策略学习、任务解决和技能习得能力。随着时间的推移，每个智能体通过持续的互动增强其技能，导致个体的进化。协作学习和以共识为导向的互动之间的关键区别在于它们的基本目标和过程。共识导向的互动侧重于通过合成不同观点以达成一致来实现知识整合和信念调整，而协作学习互动强调同行知识构建和经验分享，优先考虑相互改进和个体成长。参与协作学习互动时，智能体会通过观察他人的行为更新其背景或记忆。例如，智能体可以通过观察同行的讨论学习到最佳策略，并根据这些观察调整自己的方法，而不一定要达成单一的“最佳”策略。正如在文献中所强调的，有效的讨论策略显著影响智能体之间的学习结果。在这些互动中，智能体合作学习并解决问题，侧重于相互理解和增强，而不是达成一致的决定。这种方法通过持续的反馈完善个人的响应和知识。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/7/text
1. 在多智能体系统中，经验分享对于代理之间的合作学习有何重要作用？如何通过经验分享促进智能体的自适应改进和团队协作？  2. 介绍MAS-CTC框架在协作学习互动中的应用，它是如何促进多团队在跨团队协作环境中交流见解并共同提出决策的？  3. 在协作学习互动中，团队如何通过连续模式和累积模式的形成，实现经验的迭代完善，从而提高任务执行效率和解决复杂问题的能力？
在协作学习互动中常用的方法包括：1). 经验分享。智能体交换个人见解和最佳实践。正如[303]中所描述的，通过迭代经验的完善，LLM智能体通过连续获取和利用团队经验在软件开发中实现自适应改进，形成连续模式和累积模式。此外，MAS-CTC[301]是一个可扩展的多团队框架，使得编排的团队能够共同提出各种决策，并在跨团队协作环境中交流见解。它使不同团队能够同时提出各种面向任务的决策作为见解，并在重要阶段进行见解交换（多团队聚合）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/8/text
1. 在多智能体系统中，贪婪修剪机制和聚合机制如何帮助提高软件开发性能？这两种机制相较于其他方法有何优势和局限性？  2. 在移动多智能体系统中，全局智能体如何通过本地智能体执行结果进行反思，实现与环境对齐的自适应规划？这种方法相对于传统方法有哪些创新之处？  3. AutoAgents采用的知识共享机制如何促进智能体之间的沟通和反馈？这种机制对于智能体的长期记忆、短期记忆和动态记忆有何影响？
不同的智能体团队利用贪婪修剪机制和聚合机制来消除低质量内容，从而提高软件开发的性能。与此不同，在MOBA[1049]中，一种基于MLLM的新型移动多智能体系统，全局智能体根据本地智能体执行结果进行反思，以支持与环境对齐的自适应规划。AutoAgents [1030]采用知识共享机制，智能体交换执行结果以增强沟通和反馈，智能体可以从其他智能体获取长期、短期和动态记忆。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/9/text
1. 在多智能体系统中，同行讨论如何促进智能体的决策制定和推理准确性的提升？   2. 同行讨论和观察学习在智能体之间的知识传递和技能提升方面有何异同之处？   3. 如何通过同行讨论中的反馈交流和信心评分来促进智能体之间的协作知识获取和决策制定的完善？
同行讨论。同行讨论使智能体能够表达其推理过程并学习他人的方法。MEDCO[923]创建了一个动态环境，通过学生智能体之间的协作问题解决来加强临床推理和决策技能。此外，在In[1050]中，智能体在初始化其输出后参与结构化的同行讨论，逐步审查彼此的推理过程。通过反馈交流和信心评分，智能体完善其决策制定，从不同方法中学习，并通过迭代增强其推理准确性，促进协作知识获取。3)。观察学习。观察学习发生在智能体监测他人行为和结果以指导其自身策略的情况下。AgentCourt [1051]开发了参与法庭辩论的律师智能体，并通过积累经验不断改进，展示了通过经验学习获得改进的推理和一致性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/10/text
1. iAgents中采用的智能体推理机制InfoNav如何帮助智能体克服信息不对称，促进有效的信息交换？ 2. 混合记忆在iAgents中是如何组织人类信息的，以提供准确和全面的信息交换支持？这种信息组织对智能体的任务执行有何影响？ 3. MARBLE中的认知演进规划是如何结合智能体的期望和实际行动结果来更新规划，从而实现更好的规划？该规划方法在解决任务时有哪些优势？
在iAgents[1046]中，人类社交网络在智能体网络中得到了反映，智能体主动交换人类任务解决所需的信息，从而克服信息不对称。iAgents采用了一种新颖的智能体推理机制InfoNav，将智能体的通信引导向有效的信息交换。与InfoNav一起，iAgents将人类信息组织在混合记忆中，为智能体提供准确和全面的信息以进行交换。额外的实验现象表明，某些任务的困难使智能体不断完善他们的策略，以追求所需的信息。MARBLE[948]设计了一个认知演进规划，结合智能体的“期望”和实际行动结果来更新下一轮规划的整体经验，以实现更好的规划。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/11/text
1. 如何确保在多智能体系统中具有不同能力的代理之间实现公平的知识交流，同时防止错误或偏见在系统中传播？ 2. 在协作学习交互中，如何平衡个体进步与系统整体发展之间的关系，以应对知识公平、偏见传播和可扩展性等挑战？ 3. 在多智能体系统中，如何通过协作学习促进智能体发展更丰富的知识库和更精细的问题解决能力，从而提升系统的潜力？
尽管协作学习交互具有诸多优势，但也面临一些挑战。其中包括确保在具有不同能力的智能体之间实现公平的知识交流，防止错误或偏见在系统中的传播，保持智能体多样性同时促进学习，并开发有效的机制，使智能体能够基于相关性和可靠性有选择性地吸收他人的知识。要克服这些挑战，需要精心创建交互框架和学习策略，并在个体进步与系统整体发展之间取得平衡。尽管知识公平、偏见传播和可扩展性等问题存在困难，但在多样化和复杂环境中，提升多智能体系统的潜力是巨大的。通过使用迭代学习过程并提供机会，协作学习使智能体能够发展更丰富的知识库和更精细的问题解决能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/12/text
1. 在多智能体系统中，教学和指导交互相较于协作学习，更注重知识单向流动。针对这种单向流动的特点，如何设计有效的机制和方法来确保知识从经验丰富的智能体向经验较少的智能体传递？  2. 在多智能体系统中，教学和指导交互被描述为协作环境中的基本机制。针对这一机制的重要性，如何精心制定交互协议和学习框架，以促进个体发展与整体系统进步的协调？  3. 教学/指导交互在多智能体系统中扮演着重要角色，但其机制和方法需经过精心设计。针对这一需求，如何确保交互协议和学习框架的有效性，以促进知识传递和集体智能的增长？
教学/指导交互 为了解决这些挑战，重要的是精心制定交互协议和学习框架，使个体发展与整体系统进步相协调。在多智能体系统背景下，教学和指导交互是协作环境中的基本机制，特别是在知识传递对于增长和集体智能至关重要的场景中。与协作学习不同，其中知识在智能体之间相互交换，教学和指导交互侧重于知识从经验丰富的智能体向经验较少的智能体的单向流动。教学/指导交互中使用的机制和方法包括几个关键策略：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/13/text
1. 在多智能体系统中，导师智能体提供纠正性或建设性反馈对学习者的知识和技能提升有何重要作用？这种反馈循环如何促进学习者更新内部知识？  2. 在多智能体系统中，导师通过绩效评估和评估标准评估学习者的能力或进展，如何为学习者的发展提供宝贵见解？这种评估对学习者的学习动力和成长有何影响？  3. 在多智能体系统中，导师如何利用直接教导传达有针对性的知识、指导或技巧？这种指导和教学方式如何帮助学习者提出问题并获得澄清，从而促进他们的学习和技能提升？
·批评与反馈。导师智能体评估学习者的表现并提供纠正性或建设性反馈。这有助于学习者通过反馈循环完善他们的知识和技能，他们会根据收到的反馈更新内部知识。
·评估。导师通过绩效评估和清晰的评估标准评估学习者的能力或进展，为发展提供宝贵的见解。
·指导和教学。导师使用直接教导传达有针对性的知识、指导或技巧，使学习者能够提出问题并获得澄清。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/14/text
1. 迭代式教学与强化教学在多智能体系统中的应用中，如何通过循环实践导向学习方法提高学习者的专业技能，以及专家导师和同行讨论在其中的作用是怎样的？  2. 在MEDCO系统中，专家智能体如何通过持续评估和实时指导帮助学生智能体提升临床能力，特别是关注患者互动技能和诊断推理？   3. 在研究中提到的智能医生通过与仿真医院中的智能患者互动来不断改进诊断，这种实践如何促进智能体学习和将知识应用于真实案例中？
迭代式教学与强化教学通常是渐进的，每个阶段都为学习者提供完成任务并获得反馈的机会。例如，在MEDCO系统中，学生智能体通过循环实践导向学习方法来提高其专业技能，这一方法由专家导师指导，同时还参与同行讨论。这些专家智能体进行持续评估，并就临床能力提供实时指导，重点关注患者互动技能和诊断推理。研究表明，一个智能医生可以通过与仿真医院中的智能患者互动来持续改进诊断，并将其学到的知识应用于真实案例中。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/15/text
1. 任务导向互动中的代理如何通过有效的协调和任务分解策略实现共同目标？   2. 在单向和互动式知识传递类型中，互动式知识传递如何促进多智能体系统中代理之间的合作和技能提升？   3. 不同类型的互动模式（如软件开发框架、协作推理框架和机器学习应用）是如何促进多智能体系统的发展和任务执行效率的？
这种互动类型可以根据知识传递方向分为两种主要类型：单向和互动式。单向类型植根于传统教学模式，其中知识从教师传递给学生。这种方法强调事实和概念的传递，通常涉及讲座和直接指导。

任务导向互动。任务导向的合作涉及代理通过有效的协调和任务分解策略共同实现共同目标，以及高度的合作和协调。代理主要通过处理上游输出并根据已建立的任务依赖关系为下游代理生成结果来互动，而不是进行复杂的讨论或辩论。

最近的框架展示了这种互动模式的多样实现：(1) 软件开发框架，如MetaGPT和ChatDev，代理在一个结构化的流水线中运行，这反映了软件开发的生命周期。例如，架构代理处理需求以生成技术规范，然后开发代理使用这些规范生成代码，随后测试代理验证实现；(2) 协作推理框架，如Exchange-of-Thought（EoT）、GPTSwarm、MACNET，涉及以特定格式（例如，图、树、有向丙烯酸图、可优化图）组织代理，通过确保只有优化的解决方案通过序列，减轻了上下文扩展风险，并强制多个代理共同协作解决复杂的数学或知识推理任务；在(3) 机器学习应用中，代理遵循严格的工作流结构，每个代理在流程中执行特定任务。对于更复杂的任务，如视频问答（VideoQA），TraveLER框架展示了跨结构化阶段的模块化任务分解（遍历、定位、评估和重新规划），其中规划代理管理互动并根据迭代代理输入改进策略。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/16/text
1. MACNET将代理结构化为有向无环图（DAG），这种设置如何有助于减轻上下文扩展风险，并提高任务执行效率？  2. 在TraveLER框架中，如何通过模块化任务分解（遍历、定位、评估和重新规划）实现复杂任务的有效处理？   3. 代理在机器学习应用中如何遵循严格的工作流结构，并如何根据监督人员发布的指令执行特定任务？
这些交接依赖于明确的交付成果，而不是直接的代理协商。受到类似GPTSwarm的图代理系统的启发，MACNET将代理结构化为有向无环图（DAG）。在这里，监督人员发布指令，执行者实施解决方案。通过确保只有优化的解决方案通过序列，这种设置减轻了上下文扩展风险。在机器学习应用中，代理遵循严格的工作流结构，每个代理在流程中执行特定任务。对于更复杂的任务，如视频问答（VideoQA），TraveLER框架展示了跨结构化阶段的模块化任务分解（遍历、定位、评估和重新规划），其中规划代理管理互动并根据迭代代理输入改进策略。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.1 Agent-Agent collaboration/section/17/text
1. 在多智能体系统中，任务导向的互动如何促进代理之间的有效合作和共同实现共同目标？   2. 代理在开放式环境中如何根据不断变化的环境进行调整，以实现任务驱动的交互？   3. 为确保代理在多智能体系统中有效协作达到最终目标，协调机制中的通信协议、同步策略和资源共享技术起到了怎样的关键作用？
除了有组织的发展之外，在开放式环境中如Minecraft游戏中已经展示了任务驱动的交互，代理根据不断变化的环境进行调整。在[927]中，领导代理通过将复杂目标分解为具体任务来管理工作流程，而执行代理执行动作如收集资源。协调机制对确保代理有效协作达到最终目标非常重要，包括通信协议、同步策略和资源共享技术。在多智能体系统中，代理的相互作用对任务执行引起了极大兴趣，特别是通过利用LLMs处理复杂任务和工作流程。代理之间的合作对任务完成至关重要，特别是在诸如软件开发和项目管理等不断变化的环境中[626, 630]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.2 Human-AI Collaboration/section
人工智能与人类的协作主要通过一次性任务委派、多轮交互式指导和沉浸式人-智能体协作三种方式展开。一次性任务委派是将任务委派给MAS，智能体独立处理任务并提供解决方案；多轮交互式指导通过迭代交互实现满意结果，适用于创意应用如图像编辑；沉浸式人-智能体协作则模拟人类行为，智能体作为合作伙伴参与任务。Co-Gym等框架用于评估LLM智能体的沟通、情境意识和个性化能力。随着智能体系统的不断进步，人工智能与人类的协作将更多样化，从简单问答到复杂设计任务，预计将重塑工作组织方式，推动社会生产力和生产关系的变革。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.2 Human-AI Collaboration/section/0/text
1. 在人类与基于LM的智能体合作中，一次性任务委派和多轮交互式指导两种方式各有何优劣之处？如何根据任务性质选择合适的合作方式？  2. 沉浸式人-智能体协作模式如何模拟人类行为，以实现更有效的任务完成？在实际应用中，这种模式可能面临哪些挑战？  3. Co-Gym等框架如何评估LLM智能体的沟通、情境意识和个性化能力？这些评估标准对于提高智能体系统在人类协作中的效率和效果有何重要意义？
为了发挥多智能体系统（MAS）在实现人类目标方面的潜力，人们通常使用三种主要方法与它们共同工作：一次性任务委派、多轮交互式指导和沉浸式人-智能体协作。

在一次性任务委派中，人们将单个任务委派给MAS，例如向问答平台提问或分配编码任务。在没有额外输入的情况下，智能体自主处理任务，在单次回复中提供完整的回答或解决方案。这是目前人类与基于LM的智能体合作的主要方式。

在多轮交互式指导中，人们与基于LM的智能体系统进行迭代交互，直到达到满意的结果为止。这种类型的交互在创意应用中广泛存在，例如图像编辑或编辑写作。例如，用户可能要求系统在图像的特定位置添加一个对象，替换一个元素，更改背景，或修改句子中的某一部分。这些交互通常跨越多个轮次，用户不断完善他们的请求，直到达到期望的结果。此外，在多轮交互过程中，某些其他基于LM的智能体系统可能需要人类批准或澄清才能继续下一步。在人类指导下，这些基于LM的智能体系统可以完成家庭任务以及软件开发任务。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.2 Human-AI Collaboration/section/1/text
1. 沉浸式人-智能体协作中，基于大型语言模型的智能体如何模拟人类行为，并如何充当合作伙伴来实现共同目标？    2. Co-Gym框架如何评估LLM智能体在旅行规划、撰写相关工作和表格分析等任务中的沟通、情境意识和个性化能力？   3. 基于LLM的智能体系统如何促进人工智能与人类协作的多样化，从简单问答交互到复杂设计任务，以解决跨领域挑战？
沉浸式人-智能体协作特点是基于大型语言模型(LLM)的智能体模拟人类行为，充当合作伙伴。例如，在沉浸式环境中，人们将这些智能体视为队友，共同实现目标。实例包括代表人类参加会议或帮助解决家务或项目任务。这种策略突出了在动态环境中的有效整合和团队合作。

为了定量评估人工智能与人类的协作，提出了几种框架。例如，Co-Gym测量了LLM智能体在旅行规划、撰写相关工作和表格分析等任务中的沟通、情境意识和个性化能力。

总之，随着基于LLM的智能体系统的进步，人工智能与人类的协作已经多样化，以解决跨领域的挑战。从简单的基于命令的人工智能问答交互，到用于设计和开发的多轮对话，再到与人类日常任务合作。

随着基于LLM的智能体系统的进步，人们预计它们将更多地融入日常生活，简化任务并提高效率。与此同时，人类将不断完善和调整与人工智能互动的方式，从而实现更有效的协作。我们相信这种转变将推动社会生产力和生产关系的根本变革，重塑工作组织方式以及人类和人工智能在大型语言模型时代的合作方式。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.3 Collaborative Decision-Making/section
协作决策在多代理系统中扮演着关键角色，决策方法直接影响着协作效率和整体性能。独裁式决策和集体决策是两种主要的决策范式。独裁式决策依赖于单个代理，通过全局思维方式提高系统性能和任务完成率。相较之下，集体决策涉及代理之间的协作，通过投票或辩论达成决策。未来研究需关注培训方法和新颖互动协议的设计，以推动智能体积极学习和优化协作决策过程。当前挑战包括情境依赖性互动的局限性以及对大型语言模型的过度依赖，需要更具体的框架来训练和优化合作行动。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.3 Collaborative Decision-Making/section/0/text
1. 多样化的决策方法如何能够显著增强多代理系统的协作效率？ 2. 如何设计合理的决策机制以激发多代理系统内部智能的出现？ 3. 未来研究如何应对协作决策过程中存在的情境依赖性互动局限性和对大型语言模型的过度依赖这两个挑战？
协作决策过程对于确保多代理系统的高效运行和成功完成任务至关重要。尽管协作本身是一个核心特征，但决策方法直接决定了协作的有效性和系统整体性能。最近的研究突出了协作决策的关键作用。[1037]表明，多样化的决策方法可以显著增强系统的协作效率。[649]强调，合理的决策机制可以激发系统内部智能的出现。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.3 Collaborative Decision-Making/section/1/text
1. 独裁式决策中单一代理的作用如何体现全局思维方式，从而提高系统性能和任务完成率？  2. 集体决策相较于独裁式决策，如何通过投票或辩论达成决策，并在多代理系统中发挥作用？  3. 未来研究如何设计培训方法和新颖互动协议，以促进智能体积极学习和优化协作决策过程？
从更广泛的角度来看，协作决策过程可以根据其架构特征分为两类主要类别：独裁式决策和集体决策[1037]。

独裁式决策。独裁式决策是多代理系统中决策依赖于单个代理的过程。在这种范式中，所有代理将它们的状态信息或局部观察发送给这个独裁代理。独裁代理负责汇总这些数据，研究核心问题，并建立明确的决策指导方针。这种方法的关键原则是利用全局思维方式，朝着改进决策制定，从而提高系统性能的可靠性以及成功实现任务目标的方向[1031,058,046]。证明了单一代理决策过程中单个LLM的作用，LLM综合了对同一问题的各种观点，使决策更加客观和全面。此外，[134,1059]建议通过排名、评分或清单的加权综合方法，增强决策程序的稳健性。另外，除了明确包含不同观点外，[1030,06o]提出了一种架构，其中一个中心代理将复杂任务分解为更简单的子任务，并将它们分配给按功能分组的专门代理。此外，在[651,28]中，通常最后一个节点代理在环境中工作，根据拓扑结构汇总过去的信息并得出结论，而不是由一个中心代理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.3 Collaborative Decision-Making/section/2/text
1. 集体决策中基于投票的方法和基于辩论的方法各有何优劣之处？这些方法如何影响系统的稳健性和可扩展性？  2. 在集体决策中，如何通过基于辩论的方式促进代理之间的有组织互动，以达成最佳决策结果？辩论过程中如何解决代理之间的分歧并建立共识？  3. 集体决策中的投票系统如何提供共识框架？基于投票的决策制定如何实现确定性多数，并避免复杂系统设计的问题？
集体决策。集体决策涉及代理之间协作达成决策，没有中央权威，依赖于本地数据和像投票或谈判这样的互动。这种方法在代理之间分享决策权力，允许系统根据变化进行调整，同时保持稳健性和可扩展性。

·基于投票的决策制定。投票系统对于集体决策制定至关重要，提供了达成共识的框架。如[1045,968]所述，通过投票实现确定性多数。此外，GEDI选举模块[1037]实现了多种投票方法。这种方法在提高推理和容错能力的同时，避免了复杂的系统设计。

·基于辩论的决策制定。与基于投票的方法相比，基于辩论的决策制定侧重于代理之间的有组织互动，以获得最佳结果。在[1031,1061]中，代理参与引导性讨论，在那里他们阐述和提出建议，试图解决分歧并调和观点。同时，[1050,1062]采取克制立场，利用代理之间的通信渠道通过反复讨论进行共识建立。为了解决“认知孤岛”问题，某些系统将采用共同的检索知识库，使代理在辩论过程中意识到相同的知识[1005]。通过模仿人类对话，这些系统使代理能够交换观点并做出更明智的决策。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.3 Collaborative Decision-Making/section/3/text
1. 在多智能体系统中，当前基于情境依赖性互动的方法存在哪些局限性，为什么它们需要更具体的框架来训练和优化合作行动？  2. 大型语言模型（LLMs）对于多智能体系统中的合作决策有何重要性，以及它们存在哪些局限性和挑战？  3. 未来研究如何克服对大型语言模型的过度依赖，以推动智能体积极学习和优化协作决策过程？
讨论与未来工作在多智能体系统（MAS）中的合作仍然面临着许多需要进一步研究的挑战。当前的方法主要基于情境依赖性互动；然而，它们并没有包括针对训练和优化合作行动的具体框架。对大型语言模型（LLMs）的严重依赖具有一些局限性，因为它们的有效性与LLM的上下文窗口大小及其固有的推理能力密切相关。虽然LLMs为促进互动提供了坚实基础，但这些系统仍然受限于依赖上下文的沟通的固有限制。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/15.3 Collaborative Decision-Making/section/4/text
1. 如何设计一个有效的框架，激励多智能体在协作决策中积极学习，特别是在确定最佳时机和信息传播方法方面？    2. 在多智能体强化学习中，如何帮助智能体确定适当的信息分享时机以及通过哪些渠道分享哪些信息的策略，以优化协作决策过程？  3. 在未来研究中，如何整合新颖的互动协议和培训方法，以持续优化多智能体强化学习框架，促进智能体在协作决策中的表现？
未来的研究应该专注于找到激励智能体积极学习的框架，特别是关于最佳时机和信息传播方法。利用多智能体强化学习（MARL）的方法，越来越需要帮助智能体确定适当的信息分享时机以及通过哪些渠道分享哪些信息的策略。这不仅需要设计新颖的互动协议，还需要整合培训方法，以便随着每一次改进不断优化这些协议。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collective Intelligence and Adaptation/section
集体智能是多智能体系统中的关键概念，源自生物和社会合作，强调群体智慧优于个体决策。MAS通过个体代理间的互动逐步形成共享理解和集体记忆，强调异质性、环境反馈和代理互动对社会网络和决策策略的重要性。集体智能不仅是个体能力总和，更是新兴行为，个体代理通过参与集体任务和自我反思逐渐发展出推理和决策能力。复杂行为在MAS中呈现，包括高级社交互动和新兴合作，通过递归互动形成合作策略，进而演变成社会契约和组织等级，标志着从基本合作到复杂社会构建的转变，促成文化规范和惯例的形成。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collective Intelligence and Adaptation/section/0/text
1. 集体智能概念如何从生物和社会合作中获得灵感，并如何支持多智能体系统（MAS）的发展？ 2. “群体智慧”概念认为独立群体决策优于个体，那么如何解释认知理论模型如“心智社会”对这一观点的支持？ 3. 在多智能体系统中，个体参与集体问题解决的方式与人类社会中的合作、分工有何相似之处？
集体智能的概念对多智能体系统（MAS）的发展至关重要，从生物和社会合作中汲取灵感。集体智能内在的概念是“群体智慧”，它认为独立的群体往往比任何一个人做出更好的决策。认知理论模型如“心智社会”及其相关理论进一步支持这一范式，表明智能源于主要和专业组件之间的协同作用。此外，在人类社会中，个体合作、分工，参与集体问题解决以解决复杂挑战。MAS采用类似的策略，专门的代理参与解决复杂问题和集体决策。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collective Intelligence and Adaptation/section/1/text
1. 集体智能如何通过多智能体系统内持续的互动和共享理解逐步形成，以及这种集体记忆如何影响复杂社会网络的出现和改进决策策略？  2. 个体代理之间的异质性、环境反馈和代理-代理互动如何加强了互动动态，从而促进集体智能的发展并超越个体能力的总和？  3. 个体代理如何通过持续参与集体任务和自我反思共享背景，逐渐发展出推理和决策能力，以及这种演化与集体智能的演化之间的密切关联是如何体现的？
多智能体系统内集体智能的出现是一个动态和迭代的过程。通过持续的互动，代理逐渐形成共享理解和集体记忆。个体代理之间的异质性、环境反馈和代理-代理互动加强了互动动态，这些因素对于复杂社会网络的出现和改进决策策略至关重要。值得强调的是，集体智能不仅仅是个体能力的总和，而是指超越个体代理能力的新兴行为。个体代理的发展与集体智能的增长密切相关。通过持续参与集体任务和自我反思共享背景，代理逐渐发展出推理和决策能力。个体代理的演化与集体智能的演化密切相关。通过在联合活动中持续互动和对共享背景的批判性审视，代理不断完善他们的推理和决策能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Collective Intelligence and Adaptation/section/2/text
1. 多智能体系统中的复杂和多样化行为如何超越了受限协议，例如高级社交互动，以及这些行为如何引发了合作策略的转变和更深层次的社会动态？  2. 代理之间的递归互动如何促成合作策略的形成，并最终演变成社会契约、组织等级和分工？这种过程中环境的作用是怎样的？  3. 在多智能体系统中，基本合作行为向复杂社会构建的过渡是如何发生的？递归互动、社会契约和环境变化是如何共同促成文化规范和惯例的形成的？
在多智能体系统中出现了复杂和多样化的行为。这些行为包括超越受限协议的行为，如高级社交互动，包括信任、战略欺骗、适应性伪装和新兴合作，引发了从被动到合作策略的转变，以及更深层次的社会动态。通过一系列递归互动，代理必然形成合作策略，最终演变成社会契约、组织等级和分工。社会现象必然是由代理之间的递归互动以及它们与不断变化的环境的调整相结合而产生的。这标志着从基本合作行为向复杂社会构建的过渡，导致文化规范和惯例的形成。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/16.1 Collective Intelligence/section
集体智能是指一组智能体展现出超越个体能力的问题解决能力，通常表现为新兴行为、复杂决策和高阶推理。基于LLM的智能体在协作决策和社会模拟中展现出卓越性能，通过共享信息和协调行动实现比单个智能体更好的结果。集体智能的改进系统性能主要优势在于协作导致卓越的问题解决能力，减少个体认知偏见，促进智力表现。集体智能强调从个体到集体的知识和权力转移，通过合作体现出共享智慧。基于LLM的多智能体系统利用记忆和反思机制发展新兴行为，如建立信任、对抗策略和临时团队合作，提升协作决策能力。在多智能体社会中，智能体通过持续互动创造、遵守社会规范，促进更加稳定和有组织的社会。社会规范的自发出现减少冲突，提高协调性，形成更简明有效的规范集，进一步发展角色专业化和社会内适应性治理结构。文化和宗教信仰的演化也在智能体社会中观察到，通过思想选择和群体行为，智能体传播观点，导致群体极化。这些发现突显了集体智能对文化演化和社会行为动态的重要影响。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/16.1 Collective Intelligence/section/0/text
1. 基于LLM的智能体如何通过协作行为和高阶心理理论能力提升集体智能的表现？ 2. 集体智能中的新兴行为、复杂决策和高阶推理能力是如何由智能体之间的相互作用产生的？ 3. 在多智能体系统中整合LLMs如何促进更复杂形式的集体智能，进而提高协作决策的整体效力？
集体智能的概念指的是一组智能体表现出超越个体智能体的问题解决能力。这种现象通常以新兴行为、复杂决策和高阶推理能力为特征，这些能力是由智能体之间的相互作用产生的，导致在协作决策场景和社会模拟中表现出增强的性能。研究表明，基于LLM的智能体可以表现出协作行为和高阶心理理论能力，这对于理解共享环境中其他智能体的视角至关重要。他们的研究结果表明，将LLMs整合到多智能体系统中可以促进更复杂形式的集体智能，从而提高协作决策的整体效力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/16.1 Collective Intelligence/section/1/text
1. 集体智能如何通过协作导致卓越的问题解决能力，克服个体认知偏见，从而实现增强的智力表现？ 2. 在多智能体系统中，集体智能如何促进知识和权力从个体到集体的转移，并提供共享或群体智慧？ 3. 基于LLM的多智能体系统如何利用规划和沟通能力，实现卓越的协作决策能力，并为提高解决方案一致性提供支持？
多智能体系统中集体智能的改进系统性能的主要优势在于协作导致卓越的问题解决能力。集体智能可以被鼓励以克服“群体思维”和个体认知偏见，从而使集体能够在一个过程上进行合作，同时实现增强的智力表现。当个体智能体分享信息并协调行动时，系统可以取得比任何单个智能体独立操作更好的结果。因此，集体智能是从许多个体的协作、集体努力和竞争中产生的共享或群体智慧，体现在共识决策中。集体智能大大促进了知识和权力从个体到集体的转移。他们通过他们的合作体现语言智能体（CoELA）展示了这一点，在ThreeDWorld多智能体运输任务中，CoELA比传统规划方法提高了40%的效率。这一显著改进源于系统在多智能体环境中有效利用LLM进行规划和沟通的能力，为增强的协作决策能力提供了令人信服的证据。正如前面讨论的，基于LLM的多智能体系统固有的多样性和跨学科性，以及各种智能体之间的互动，提供了内部反馈和丰富的背景信息，从而减少偏见并提高解决方案的一致性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/16.1 Collective Intelligence/section/2/text
1. 基于LLM的智能体如何通过学习和适应产生新兴的复杂行为？这种行为是如何在集体智能场景中演化和发展的？ 2. 智能体在集体智能中如何展现出战略行为，例如建立信任、对抗策略、欺骗和领导力？这些行为是如何通过互动和学习而演变的？ 3. 集体智能中的智能体如何利用记忆和反思机制来发展复杂行为？共享的背景和环境信息如何提升智能体的可用内存，使其更有效地适应动态环境？
新兴行为
集体智能中最引人注目的一个方面是新兴的复杂行为，这些行为是由智能体相互作用自发产生的。这些行为并不是明确编程的，而是通过学习和适应而出现的。正如在各种研究中所讨论的[971,965,966]，智能体发展了战略行为，包括建立信任、对抗策略、欺骗和领导力。集体行为通过共享经验而演变，村庄对齐的智能体学会了合作和战略联盟形成，狼对齐的智能体通过“信息混淆”策略改进了欺骗。此外，智能体在没有明确训练的情况下优化了投票模式和欺骗策略，这表明群体智能是在多轮互动中出现的。同样，在Avalon游戏中[68]，研究人员观察到智能体在识别和对抗欺骗信息方面变得更加优秀。个体适应了欺骗环境，并利用一级和二级视角转变来完善决策。此外，尽管没有预定义的协作协议，智能体展示了自适应合作和临时团队合作[969]。这些发现凸显了基于LLM的智能体通过互动和学习发展复杂行为的能力，展示了集体智能场景中新兴行为的潜力。值得注意的是，这些新兴行为依赖于记忆和反思机制。智能体检索和反思历史信息以生成紧凑的背景，增强他们的推理能力[239]。在多智能体系统中，共享的背景和环境信息显著提升了智能体的可用内存。这使智能体能够建立在过去互动的基础上，完善策略，并更有效地适应动态环境[1064]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/16.1 Collective Intelligence/section/3/text
1. 智能体在社会演化中如何通过持续互动创造、表达和遵守社会规范，以减少冲突并提高协调性？这种规范是如何作为社会秩序的基础，导致更加稳定和有组织的社会的？  2. 在智能体社会中，为什么智能体在信念中比在行为中更快地发展规范？这种规范是如何逐渐转化为一致的行动，形成更一般的原则？这个过程中民主过程的作用是什么？  3. 多智能体社会中的文化和宗教信仰是如何演化的？智能体是如何驱动思想选择，传播观点和信条到社区中？这种规范创造和角色专业化的过程如何促进更好的组织、减少冲突和社会内适应性治理结构的出现？
社会演化
在生成式智能体社会领域最重要的发现之一是社会规范的自发出现。研究表明，通过持续互动，智能体能够创造、表达、传播、评估和遵守社会规范。这些规范作为社会秩序的基础，减少冲突，提高智能体之间的协调，从而导致更加稳定和有组织的社会。有趣的是，研究发现智能体在其信念中比在行为中更快地发展规范。这表明，虽然智能体可能会迅速内化某些规范，但将这些规范转化为一致的行动需要更长的时间。随着时间的推移，这些规范往往会合成更一般的原则，导致更简明有效的个人规范集。此外，Project Sid模拟模型展示了大规模智能体社会中社会规范和角色专业化的出现，并提供了进一步的证据。在这项研究中，观察到智能体自主形成了专业化的社会角色。这些角色并非预定义，而是在智能体在其环境中互动并发展集体规则的过程中自然出现。该模拟还突出了民主过程在遵守和修改这些集体规则中的重要性。发现智能体参与了文化和宗教传播，将想法和信条传播到社区中。这种规范创造和角色专业化的过程导致了更好的组织、减少冲突和社会内适应性治理结构的出现。多智能体社会中文化和宗教信仰的演化也在研究中观察到，这是通过智能体驱动的思想选择，反映了现实世界社会变化。此外，模拟了一百万智能体之间社会互动的研究提供了有关文化传播和群体极化的宝贵见解。文化模因和信仰系统在智能体社会中自然传播。智能体表现出群体行为，遵循主流观点，即使这些观点是不理性的。这导致了群体极化的出现，智能体通过反复互动加强极端观点。这一发现突显了群体规模对文化演化和社会行为动态的重要影响。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/16.2 Individual Adaptability/section
在多智能体系统中，个体适应能力是指智能体根据先前互动和经验调整行为和决策策略的能力。通过基于记忆的学习和基于参数的学习机制，智能体实现自我进化。基于记忆的学习利用历史记录和经验指导决策，通过记忆优化决策过程。共享记忆的学习则扩展至多智能体间共享知识，增强协作和决策优化。基于参数的学习通过训练技术提高适应性，如通过通信日志微调LLMs。这些机制使智能体处理结构化和非结构化数据，提升在动态环境中做出决策的能力。未来需要平衡智能体的一般能力与在特定角色专业化之间的挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/16.2 Individual Adaptability/section/0/text
1. 在多智能体系统中，基于记忆的学习和基于参数的学习机制各有何优劣之处？如何平衡它们以提高智能体的适应性和决策能力？  2. 大型语言模型（LLMs）在支持智能体自我进化和适应性方面扮演着怎样的角色？它们如何促进智能体的动态监控、信息交换和决策优化？  3. 未来在多智能体系统中，如何解决智能体一般能力与在特定角色专业化之间的平衡挑战？这种平衡对于系统整体性能和智能体间协作有何影响？
在多智能体系统（MAS）中，个体适应性指的是一个智能体根据先前的互动和经验调整其行为和决策策略的能力。这也被定义为自我进化，智能体可以通过修改自身，如改变其初始目标和规划策略，并根据反馈或通讯日志对自己进行训练，从而动态自我进化。这种适应性得到大型语言模型（LLMs）的支持，这些模型支持动态监控和适应过程，以及智能体的记忆能力和信息交换。这些模块对于确保智能体能够持续改进其性能，有效应对动态环境，并优化其决策过程至关重要。我们将有助于个体适应性的机制归类为基于记忆的学习和基于参数的学习，其中包括无需训练和基于训练的方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/16.2 Individual Adaptability/section/1/text
1. 基于记忆的学习如何通过历史记录和经验指导决策，从而显著增强多智能体系统中个体的适应性？    2. 在多智能体系统中，如何利用个体记忆作为经验的仓库，使智能体可以借鉴以往的成功和失败经验来优化决策过程？  3. 在临床模拟和社会行为模拟中，基于记忆的学习是如何帮助医生智能体和社会智能体不断提高表现和适应性的？
基于记忆的学习和反思机制通过利用历史记录和经验来指导决策，显著增强了基于大型语言模型（LLM）的多智能体系统中个体的适应性。通过保持和利用过去互动、决策和结果的个体记忆，智能体可以随着时间的推移优化其决策过程。这种记忆作为经验的仓库，智能体在做出未来决策时可以借鉴。利用这些存储的知识，个体智能体能够优化其决策过程，从以往的成功和失败中学习经验。例如，在临床模拟中，医生智能体可以通过积累来自成功和失败案例的经验，不断提高治疗表现。在社会行为模拟中，智能体可以通过参与更复杂的场景并利用场景记忆来提升性能，从而改善其适应性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/16.2 Individual Adaptability/section/2/text
1. 基于共享记忆的学习如何扩展了智能体的决策优化能力，相较于仅依赖个体记忆的学习机制有何优势？    2. 在多智能体系统中，如何通过共享数据、策略和反馈来增强智能体之间的协作能力，并共同优化他们的决策？    3. 在需要智能体合作、交换任务或共同努力实现共同目标的环境中，基于共享记忆的学习如何促进智能体之间的相互理解，并提高协作规划能力？
基于共享记忆的学习相比之下，通过使多个智能体交换彼此经验所得信息和见解，扩展了这一概念。智能体不再仅依赖个体记忆，而是可以从群体的集体知识中受益。通过共享数据、策略和反馈，智能体增强了他们协作的能力，并共同优化他们的决策。在需要智能体合作、交换任务或共同努力实现共同目标的环境中，基于共享记忆的学习尤为重要。例如，ProAgent预测队友的决策，并根据智能体之间的通信日志动态调整每个智能体的策略，促进相互理解，提高协作规划能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/16.2 Individual Adaptability/section/3/text
1. 基于参数的学习如何通过通信日志微调LLMs，以提高多智能体系统中智能体的个体适应性？ 2. 在多智能体系统中，基于参数的学习如何整合符号和连接主义范式，以增强智能体的推理和适应性？ 3. 未来基于参数的学习范式面临着什么挑战，特别是在如何平衡智能体的一般能力与在特定角色专业化之间的问题上？
基于参数的学习。在文本形式的基于记忆的学习之外，许多多智能体系统采用了基于参数的学习，通过后期训练技术提高智能体的个体适应性。例如，[1070]讨论了学习通过通信（LTC）范式，其中利用智能体之间的通信日志构建生成数据集，用于训练或微调LLMs。在LLM驱动的智能体中整合符号和连接主义范式增强了它们的推理和适应性。最近的研究越来越多地集中在多智能体的（共同）微调上，通过合作轨迹提高协作和推理能力。例如，多智能体辩论微调[1071]和SiruiS [1072]。此外，Sweet-RL [1073]采用强化学习增强MAS中的评论模型，促进更好的协作推理。然而，尽管它们表现出有希望的性能，未来基于参数的学习范式可能需要解决智能体的一般能力与它们在MAS中特定角色的专业化之间的平衡。这种混合方法使智能体能够处理结构化和非结构化数据，提高它们在动态环境中做出决策的能力。 [1074, 1075]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Evaluating Multi-Agent Systems/section
评估多Agent系统涉及从单一代理到多代理系统的转变，尤其是基于大型语言模型（LLM）的系统。相比于单一代理评估的即时任务表现，多代理系统评估需要全面理解代理间的动态关系，如协作规划和通信效果。本章深入讨论了任务导向推理和整体能力评估的微妙之处。首先，针对解决任务的多代理系统（MAS），评估了LLM在编码、知识和数学问题解决任务中的推理能力。MAS表现出了增强的推理能力，通过代理间决策协作和多轮通信实现。其次，对MAS能力进行了一般评估，转向高级别代理互动，包括协作、推理能力、系统效率和灵活性。测量分类为面向协作和竞争的指标，涵盖效率、决策质量、协作质量和灵活性等方面，捕捉了代理行为的多个层面，如通信效果、资源分配和对动态情况的响应。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Evaluating Multi-Agent Systems/section/0/text
1. 在评估基于大型语言模型的多代理系统时，为什么需要从单一任务表现转向全面理解代理间的动态关系，如协作规划和通信效果？这种范式转变有哪些优势和挑战？  2. 在评估多代理系统的整体能力时，为什么需要超越单一任务导向的成就，转向高级别代理互动？采用面向协作和竞争的测量分类，如何更全面地记录代理行为的多个层面，包括通信效果、资源分配和对动态情况的响应？  3. 在多代理系统的评估中，为什么要考虑代理间的决策协作和多轮通信，以实现增强的推理能力？这种推理能力对于提高系统效率和灵活性有何重要作用？
从单一代理到多代理系统的转变，特别是基于大型语言模型（LLM）的系统，需要在评估范式上进行范式转变。与单一代理评估相比，在单一任务表现上的即时关注，LLM基础的多代理系统的评估必须从整体上理解为代理间动态，例如协作规划和通信效果。本章讨论了任务导向推理和整体能力评估，反映了这些评估的微妙之处。更详细地，我们在评估中考虑了两个主要领域。首先是解决任务的多代理系统（MAS），我们审查了评估和增强LLM在编码、知识和数学问题解决任务中推理能力的基准。这些测试也强调了通过组织工作流程、代理间的专业化、迭代改进实现的分布式问题解决的效用，并呼吁使用额外工具。相较于基于单个代理的个体系统，由于代理间决策协作和多轮通信，MAS表现出了增强的推理能力。接着，对MAS能力进行了一般评估，超越了单一任务导向的成就，转向高级别代理互动。这涉及从一维测量转向多维框架，以记录协作、推理能力、系统效率和灵活性方面的成就。我们将这些测量分类为面向协作和面向竞争的测量，并确定了效率、决策质量、协作质量和灵活性作为主要测量领域。这些测量捕捉了代理行为的各个方面，包括通信效果、资源分配和对动态情况的响应。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Building Safe and Beneficial AI Agents/section
本部分探讨了基于LLM的智能代理面临的安全挑战。内在安全威胁源于代理核心组件的漏洞，包括大脑、感知和行动模块，容易受到对手利用。外部安全威胁则来自代理与外部实体的交互，包括代理-内存、代理-代理和代理-环境交互。通过分类内在和外部安全风险，揭示了安全威胁的性质和来源。提出了针对攻击的数学基础和解决方案，包括护栏、超对齐技术等。最后，探讨了AI安全的扩展定律，强调在安全性和性能之间取得平衡的重要性。章节结构包括内在安全风险、外部安全威胁和超对齐技术的讨论，为开发安全有效部署的AI代理提供了理论基础和实际策略。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Building Safe and Beneficial AI Agents/section/0/text
1. 智能代理的自主性如何扩大了安全攻击面，并导致了新的漏洞？   2. 在理解智能代理的安全性方面，内在安全威胁和外部安全威胁有何区别？   3. 被提出的潜在缓解策略如何应对智能代理面临的内部和外部安全威胁？
基于LLM的智能代理的快速发展引入了一系列超越传统LLM的安全挑战。这些代理配备了先进的推理、规划和使用工具的能力，旨在自主执行任务并与其环境进行交互。然而，这种自主性也扩大了攻击面，制造了新的漏洞，需要谨慎研究和关注。在这部分中，我们首先建立了一个全面的框架，以理解智能代理的安全性，审视人工智能代理面临的内部和外部安全威胁。我们将探讨与这些威胁相关的各种攻击向量，并提出潜在的缓解策略。该框架分为两个关键领域：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Building Safe and Beneficial AI Agents/section/1/text
1. 智能代理核心组件中的漏洞如何导致内在安全威胁，以及这些组件的独特弱点如何容易被对手利用？    2. 代理与外部实体的交互中的外部安全威胁主要包括哪些方面，以及这些威胁如何增加代理面临的风险？  3. 在智能代理面临的安全挑战中，如何通过数学基础和解决方案（如护栏、超对齐技术等）来应对内在和外部安全威胁？
(1) 内在安全威胁源于智能代理核心组件中的漏洞，包括LLM“大脑”以及感知和行动模块。这些组件中的每一个都有独特的弱点，可以被对手利用：

- 大脑是LLM本身，负责诸如推理和规划等关键决策任务。它由一个知识模块引导，提供必要的上下文信息。
- 感知包括解释外部环境的传感器，对外部对象的恶意操纵可能导致错误的感知。
- 行动负责工具使用和下游应用，也容易受到利用。

(2) 外部安全威胁源于代理与外部通常是不受信任的实体之间的交互。这些包括：

- 代理-内存交互：代理经常访问和与存储在内存中的信息交互，内存作为决策和上下文信息检索的外部数据库。最近的研究突出了代理-内存接口中的漏洞，可以被利用来操纵代理的行为。
- 代理-代理和代理-环境交互：这些是指代理与其他代理（例如其他代理或人类操作员）以及其环境之间的交互，包括任务相关对象或动态系统。这些交互的复杂性进一步增加了代理面临外部威胁的风险。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Building Safe and Beneficial AI Agents/section/2/text
1. AI代理面临的内在安全风险和外部安全威胁有何区别？这些安全威胁的性质和来源是怎样的？  2. 在处理针对AI代理的攻击时，为什么有必要提供严谨的数学基础？超对齐技术和护栏是如何帮助解决这些安全挑战的？  3. “AI安全的扩展定律”强调了代理能力与潜在风险之间的关系。在实践中，如何平衡安全性和性能之间的关键因素？
如图17.1所示，这些风险被广泛分类为内在安全和外部安全，有助于澄清它们的来源和性质。除了识别威胁，我们还提供了一个严谨的数学基础，用于理解诸如越狱、提示注入和数据污染等攻击。此外，我们提出了切实可行的解决方案，追溯了从早期LLM安全措施到保护整个代理系统的全面策略的发展过程。这包括探讨护栏、高级对齐技术（如超对齐）以及安全性和帮助性之间的关键平衡。最后，我们分析了“AI安全的扩展定律”——代理能力与潜在风险之间的复杂关系，以及必须做出的基本权衡。这部分内容提供了对挑战、理论基础和实际策略的清晰理解，这些策略对于开发能够在现实场景中安全有效部署的AI代理是必要的。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Building Safe and Beneficial AI Agents/section/3/text
1. AI代理面临的内在安全风险主要来源于哪些方面，以及这些安全威胁的性质是怎样的？ 2. 外部安全威胁对AI代理的安全性产生何种影响，具体体现在代理与内存、其他代理以及环境的交互中有哪些方面？ 3. 超对齐技术在确保AI代理行为安全方面起到了怎样的作用？它是如何平衡安全性与性能之间的挑战的？
这部分内容组织如下：首先，我们研究内在安全风险（第18章），重点关注对LLM“大脑”的威胁，以及代理的感知和行动组件的漏洞（第19章）。接下来，我们探讨与代理-内存、代理-代理和代理-环境交互相关的外部安全威胁（第20章）。最后，我们调查旨在确保代理行为安全的超对齐技术，同时解决在平衡安全性与性能方面的更广泛挑战。这包括探讨安全措施如何随着AI系统能力的增强而扩展，以及在设计安全、功能强大的AI代理时涉及的权衡（第21章）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Building Safe and Beneficial AI Agents/section/4/figure
1. 什么是LLM智能代理面临的内在安全威胁和外部安全威胁？这些安全威胁的性质和来源是什么？ 2. 在探讨AI安全的扩展定律时，为什么强调在安全性和性能之间取得平衡的重要性？
图17.1：大脑（LLM）面临安全威胁，如越狱和提示注入攻击（第18.1节），以及隐私威胁，如成员推断攻击（第18.2节）。非大脑模块遭遇感知威胁（第19.1节）和行动威胁（第19.2节）。由于与潜在恶意外部实体的互动，我们还探讨了代理-记忆威胁（第20.1节）、代理-环境威胁（第20.2节）和代理-代理威胁（20.3节）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Agent Intrinsic Safety: Threats on AI Brain/section
AI代理的内在安全性关注代理内部架构和功能中的漏洞，由LLM大脑和感知、行动模块构成。模块化结构支持复杂推理和自主决策，但也增加了内部漏洞的风险，可能被敌对方利用。LLM的威胁尤为严重，可能直接影响代理的决策能力，漏洞可能来自模型设计缺陷、输入误解或训练过程中的弱点。有效的缓解策略至关重要，以确保代理的安全可靠部署。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Agent Intrinsic Safety: Threats on AI Brain/section/0/text
1. AI代理的模块化架构如何既支持复杂推理和自主决策，又增加了内部漏洞的风险？   2. 为什么对AI代理的“大脑”（LLM）的威胁尤为严重？这些威胁可能源于哪些方面？  3. 在确保AI代理安全可靠部署时，应该采取怎样的有效缓解策略来应对内部架构和功能中的漏洞？
AI代理的内在安全性涉及到代理的内部架构和功能中的漏洞。AI代理本质上由多个组件组成：一个中央的“大脑”（LLM），以及用于感知和行动的辅助模块。虽然这种模块化架构使得复杂推理和自主决策成为可能，但也扩大了潜在的攻击面，暴露了代理可能受到的各种内部漏洞，敌对方可能会利用这些漏洞。

对代理的“大脑”（特别是LLM）的威胁尤为令人担忧，因为它们可能直接影响代理的决策、推理和规划能力。这些漏洞可能源于模型设计中的缺陷、对输入的误解，甚至是训练过程中引入的弱点。有效的缓解策略对于确保这些代理能够安全可靠地部署至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/section
LLM（大型语言模型）作为智能代理的核心决策组件，面临着多种安全漏洞威胁。18.1节详细探讨了这些安全漏洞，包括越狱攻击、提示注入攻击、幻觉风险、不对齐问题和毒化攻击。越狱攻击通过分析LLM输出概率分布来评估风险，白盒和黑盒攻击方式不同，缓解方法包括对抗训练和系统级防御措施。提示注入攻击利用恶意指令操纵LLMs行为，防御机制包括基于嵌入的分类器和任务屏障。幻觉风险可能导致不准确决策，解决方法包括外部知识验证和量化不确定性。不对齐问题涉及目标误导和能力滥用，解决方法包括提示工程和解码时间对齐。毒化攻击通过引入恶意数据破坏LLMs，缓解策略包括检测毒化数据和利用模型自身推理过程。这些漏洞提出了对AI代理安全性的重大挑战，未来研究应加强对外部知识整合和模型组合以增强LLM的安全性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/section/0/text
1. LLM作为智能代理的核心决策组件，为何容易受到各种安全漏洞威胁的影响？这种脆弱性如何被放大，尤其在对手可以利用弱点的动态真实环境中运作时？  2. 在面对越狱攻击、提示注入攻击、幻觉风险、不对齐问题和毒化攻击等安全漏洞时，LLM采取了哪些缓解措施？这些措施如何分别应对不同类型的攻击方式？  3. 未来研究应该如何加强对外部知识整合和模型组合，以增强LLM的安全性？如何在不牺牲性能的情况下，提高LLM对各种安全威胁的抵抗能力？
作为智能代理的核心决策组件，LLM（大型语言模型）极易受到各种安全威胁的影响。其在推理和行动选择中的核心作用使其成为对手的有吸引力目标。在AI代理的背景下，LLM本身固有的脆弱性经常会被放大，因为这些模型需要在对手可以利用弱点的动态真实环境中运作。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section
越狱攻击是绕过人工智能代理安全防护措施的行为，可能导致其决策出现有害、不道德或偏见。攻击利用LLM的帮助性和安全约束之间的张力，形式化表征越狱行为风险的方法包括分析自回归LLM输出概率分布。评估越狱攻击的影响常通过对齐奖励来衡量模型输出与人类定义的准则的接近程度。越狱可分为白盒和黑盒方法，白盒攻击依赖于对模型内部参数的访问权限，如基于梯度的优化技术，而黑盒攻击则仅依赖于输入输出交互。缓解越狱攻击的方法包括系统级防御措施，如输入净化、输出监控、多Agent辩论和形式语言约束，以及对抗训练，以提高模型的稳健性，构建更具弹性的生态系统。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/0/text
1. 如何利用自回归LLM输出的概率分布来形式化表征越狱行为带来的风险？这种方法对于评估越狱攻击的影响有何作用？  2. 白盒攻击和黑盒攻击在绕过人工智能代理安全防护措施时有何区别？这两种攻击方式分别依赖于哪些不同的访问权限和技术？  3. 在缓解越狱攻击方面，文中提到了多种方法，包括系统级防御措施和对抗训练。这些方法如何有助于提高模型的稳健性和构建更具弹性的生态系统？
越狱行为绕过了嵌入在人工智能代理中的安全防护措施，迫使它们的决策过程可能会带有有害、不道德或偏见[233]。这些攻击利用了LLM的帮助性和安全约束之间固有的张力[1134]。

形式化。为了形式化表征越狱行为带来的风险，我们分析了自回归LLM输出的概率分布。对于一个自回归LLM，给定输入序列${\mathbf x}_{1:n}$，生成输出序列$\mathbf{y}=\mathbf{x}_{n+1:n+m}$的概率建模为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/1/formula
$$ 
p(\mathbf{y}|\mathbf{x}_{1:n})=\prod_{i=1}^{m}p(\mathbf{x}_{n+i}|\mathbf{x}_{1:n+i-1})
 $$
这个公式用于建模自回归语言生成模型（LLM）输出的概率分布，以形式化表征越狱行为带来的风险。在这个公式中，$p(\mathbf{y}|\mathbf{x}_{1:n})$表示给定输入序列${\mathbf x}_{1:n}$时，生成输出序列$\mathbf{y}=\mathbf{x}_{n+1:n+m}$的概率。公式中的$\prod_{i=1}^{m}p(\mathbf{x}_{n+i}|\mathbf{x}_{1:n+i-1})$部分表示对生成序列中每个位置的输出进行条件概率建模，即在给定前面所有位置的输出的情况下，预测下一个位置的输出。这种建模方法有助于理解模型在生成序列时的行为和可能的风险。  在公式中，$m$代表生成序列的总长度，$p(\mathbf{x}_{n+i}|\mathbf{x}_{1:n+i-1})$表示在已生成的序列基础上，预测下一个位置的输出的条件概率。越狱攻击通常会向输入序列引入微妙的扰动$\tilde{\mathbf{x}}_{1:n}$，这些扰动可能会导致模型输出与期望行为偏离。  评估越狱攻击的影响时，通过对齐奖励$\mathcal{R}^{*}(\mathbf{y}|\mathbf{x}_{1:n},\mathcal{A})$来衡量模型输出与一组人类定义的安全或道德准则$\mathcal{A}$的接近程度。对手的目标是最小化这一奖励，以使模型的输出更符合人类定义的准则。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/2/text
1. 如何通过对齐奖励$\mathcal{R}^{*}(\mathbf{y}|\mathbf{x}_{1:n},\mathcal{A})$来评估越狱攻击的影响，以及该奖励如何衡量模型输出与人类定义的安全或道德准则$\mathcal{A}$的接近程度？  2. 越狱攻击中的对手如何利用引入微妙扰动$\tilde{\mathbf{x}}_{1:n}$来误导模型产生与期望行为偏离的输出，并通过最小化对齐奖励来达到其攻击目标？  3. 在越狱攻击中，为什么评估攻击影响常通过对齐奖励来衡量模型输出与人类定义的准则的接近程度？对齐奖励在这一过程中扮演了怎样的角色？
其中$m$表示生成序列的总长度。越狱攻击通常涉及向输入序列引入微妙的扰动，记为$\tilde{\mathbf{x}}_{1:n}$，这些扰动会误导模型产生与期望行为偏离的输出。

通过对其对齐奖励$\mathcal{R}^{*}(\mathbf{y}|\mathbf{x}_{1:n},\mathcal{A})$的影响来评估越狱攻击，该奖励衡量模型输出与一组人类定义的安全或道德准则$\mathcal{A}$的接近程度。对手的目标是最小化这一奖励，形式化表示为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/3/formula
$$ 
\mathbf{y}^{\star}=\underset{\mathbf{y}}{\arg\operatorname*{min}}\mathcal{R}^{*}(\mathbf{y}|\tilde{\mathbf{x}}_{1:n},\mathcal{A}))
 $$
这个公式的目的是通过最小化对齐奖励来评估越狱攻击的影响。在越狱攻击中，对手试图通过向输入序列引入微妙的扰动来误导模型，从而使其输出偏离人类定义的安全或道德准则。公式中的$\mathbf{y}^{\star}$表示对手通过扰动输入得到的最坏情况下的输出，对应最小化对齐奖励$\mathcal{R}^{*}(\mathbf{y}|\tilde{\mathbf{x}}_{1:n},\mathcal{A})$。对齐奖励衡量了模型输出与人类定义的准则$\mathcal{A}$的接近程度。  在这个公式中，$\mathbf{y}^{\star}$代表了对手通过扰动输入得到的最坏情况输出。对齐奖励$\mathcal{R}^{*}(\mathbf{y}|\tilde{\mathbf{x}}_{1:n},\mathcal{A})$衡量了模型输出$\mathbf{y}$与人类定义的准则$\mathcal{A}$的接近程度。公式的最终目标是找到能够最小化对齐奖励的输出$\mathbf{y}^{\star}$，以评估模型在面对越狱攻击时的表现。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/4/figure
1. 如何通过分析自回归LLM输出概率分布来形式化表征越狱行为风险？ 2. 在评估越狱攻击的影响时，为什么常常通过对齐奖励来衡量模型输出与人类定义准则的接近程度？
图18.1：代理内在安全性：LLM大脑上的威胁。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/5/text
1. 如何通过对抗损失函数来量化扰动输入引起的最坏情况输出的可能性？ 2. 在缓解越狱攻击方面，系统级防御措施和对抗训练各有何优势和局限性？ 3. 为什么评估越狱攻击的影响常通过对齐奖励来衡量模型输出与人类定义准则的接近程度？
其中$\mathbf{y}^{\star}$是由扰动输入引起的最坏情况输出。相应的对抗损失函数量化了生成这一输出的可能性：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/6/formula
$$ 
\mathcal{L}^{a d v}(\tilde{\mathbf{x}}_{1:n})=-\log p(\mathbf{y}^{\star}|\tilde{\mathbf{x}}_{1:n}),\mathrm{~and~}\tilde{\mathbf{x}}_{1:n}=\operatorname*{argmin}_{\tilde{\mathbf{x}}_{1:n}\in\mathcal{T}(\hat{\mathbf{x}}_{1:n})}\mathcal{L}^{a d v}(\tilde{\mathbf{x}}_{1:n})
 $$
这个公式用来量化生成最坏情况输出$\mathbf{y}^{\star}$的可能性，即对抗损失函数$\mathcal{L}^{adv}(\tilde{\mathbf{x}}_{1:n})$。公式中的$-\log p(\mathbf{y}^{\star}|\tilde{\mathbf{x}}_{1:n})$表示最小化生成最坏情况输出$\mathbf{y}^{\star}$的负对数概率，即最小化生成这一输出的可能性。其中，$\tilde{\mathbf{x}}_{1:n}$是使得对抗损失函数最小化的输入序列，即对抗样本。$\mathcal{T}(\hat{\mathbf{x}}_{1:n})$表示可能的越狱指令的分布或集合，是对输入序列$\hat{\mathbf{x}}_{1:n}$的转换空间，用于生成对抗样本$\tilde{\mathbf{x}}_{1:n}$。这个公式在论文中的作用是评估越狱攻击的风险，通过量化生成最坏情况输出的可能性来衡量模型的脆弱性，帮助提高模型的鲁棒性和安全性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/7/text
1. 如何利用分析自回归LLM输出概率分布来形式化表征越狱行为风险的方法？  2. 在评估越狱攻击影响时，为什么常常通过对齐奖励来衡量模型输出与人类定义准则的接近程度？  3. 谈谈白盒攻击和黑盒攻击在越狱攻击中的区别，以及缓解越狱攻击的方法中如何应对这两种攻击方式？
其中$p(\mathbf{y}^{\star}|\tilde{\mathbf{x}}_{1:n})$表示分配给越狱输出的概率，$\mathcal{T}(\hat{\mathbf{x}}_{1:n})$是可能的越狱指令的分布或集合。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/9/text
1. 白盒越狱方法相比黑盒越狱方法具有哪些优势和劣势？如何利用白盒攻击进行对抗性后缀优化？ 2. 在越狱攻击中，黑盒方法如何利用自动生成越狱提示和遗传算法或LLMs来实现有效攻击？这种方法的优势在于哪些方面？ 3. 如何通过对模型内部参数的访问权限来区分白盒越狱和黑盒越狱方法？这种区分对于缓解越狱攻击有何重要意义？
图18.2：白盒和黑盒越狱方法示意图：(1)白盒：对手可以访问代理的内部信息（例如梯度、注意力、logits），从而进行精确的操作，如对抗性后缀优化。(2)黑盒：对手仅依赖于输入输出交互。关键方法包括自动生成越狱提示和利用遗传算法或LLMs作为生成器来创建有效攻击。

如图18.2所示，越狱可以广泛分为白盒和黑盒方法，取决于对手对模型内部参数的访问权限。(1)白盒越狱：这些攻击假定对手可以完全访问模型的内部信息，如权重、梯度、注意机制和logits。这使得精确的对抗操作成为可能，通常通过基于梯度的优化技术实现。(2)黑盒越狱：相比之下，黑盒攻击不需要访问内部模型参数。相反，它们仅依赖于观察输入输出交互，使它们更适用于现实世界场景，其中模型内部是不可访问的。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/10/text
1. 白盒越狱攻击如何利用对AI代理的内部参数的访问权限，例如模型权重和注意机制，来实现精确的操作？ 2. 在白盒越狱攻击中，研究人员如何通过改进基于梯度的优化技术，如MAC方法和I-GCG，以及操纵LLMs的内部组件，来提高攻击性能和实现越狱目标？ 3. POEX提出的白盒越狱框架如何揭示了真实世界的危害，并展示了白盒攻击的潜力？
白盒越狱。白盒攻击利用对AI代理的内部参数的访问权限，例如模型权重和注意机制，从而实现精确的操作。该领域的早期工作主要集中在基于梯度的优化技术上，例如Greedy Coordinate Gradient（GCG）攻击，该攻击制作出能够在各种模型中引起有害输出的对抗性后缀。随后的研究在此基础上进行了探索，探讨了对GCG的改进。例如，引入动量以提高攻击性能，如MAC方法所示，以及提出了改进的越狱优化技术，如I-GCG。除了及时优化，研究人员还研究了操纵LLMs的其他内部组件。类似地，已经显示通过操纵句子末尾的MLP重新加权可以越狱指令调整的LLMs。其他方法包括利用对模型内部表示的访问权限的攻击，例如通过表示工程（JRE）实现越狱的攻击，该攻击操纵模型的内部表示以实现越狱目标，以及使用基于提示的方法来操纵模型的内部状态的DROJ攻击。AutoDAN自动生成隐秘越狱提示。POEX提出了针对具象化AI代理的第一个越狱框架，揭示了真实世界的危害，突显了可扩展和适应性强的白盒攻击的潜力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/11/text
1. 黑盒越狱中的提示工程是如何绕过人工智能代理的安全机制的？这种方法如何利用模型的响应生成能力来生成有害内容？ 2. 自动生成提示的方法如何通过遗传算法或模糊测试等算法系统地发现有效的越狱提示？这些方法如何应对代理的安全防护措施？ 3. 多轮攻击是如何利用对话能力逐渐引导对话走向不安全领域的？在这种情况下，如何确保越狱提示的逐步引导不被检测出来？
黑盒越狱。与白盒攻击不同，黑盒越狱在不了解代理内部知识的情况下操作，仅依赖于输入输出交互。提示工程是一种关键方法，通过精心设计的提示利用模型的响应生成能力并绕过其安全机制。这些提示通常利用角色扮演、场景模拟或引入语言歧义等技术，欺骗模型生成有害内容。此外，出现了自动生成提示的方法，采用遗传算法或模糊测试等算法系统地发现有效的越狱提示。此外，多轮攻击利用对话能力，通过一系列精心设计的提示逐渐引导对话走向不安全领域。其他值得注意的方法包括利用模型对特定类型的密码提示的敏感性，以及利用多模态输入（如图像）触发意外行为并绕过安全过滤器。AutoDAN利用分层遗传算法自动生成与对齐LLMs的隐秘、语义有意义的越狱提示。POEX还展示了将白盒优化的越狱提示转移到黑盒LLMs的可行性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.1 Jailbreak Attacks/section/12/text
1. 如何利用输入的净化和过滤以及输出监控和异常检测来缓解越狱攻击，从而在LLM周围创建一个安全环境？ 2. 多Agent辩论如何降低单个受损代理成功执行越狱攻击的可能性？这种系统级解决方案是如何实现的？ 3. 形式语言约束如何限制LLM的输出空间，确保其只能生成符合预定义安全行为集的响应？这种约束如何应用于缓解越狱攻击？
缓解。为了抵御多样化和不断演化的越狱攻击，需要采用多方面的方法。系统级防御提供了一个有前途的途径，重点是在LLM周围创建一个安全环境，而不仅仅依赖于加固模型本身。一个关键策略是输入的净化和过滤，在LLM处理之前对传入提示进行分析并可能进行修改。这可能涉及检测和中和恶意模式，或者重写提示以去除潜在有害元素。另一个关键方面是输出监控和异常检测，对LLM的响应进行审查，以寻找不安全或意外的内容。这可以包括使用单独的模型评估生成文本的安全性，或者采用统计方法检测与预期行为的偏差。多Agent辩论提供了一个系统级解决方案，通过利用多个AI代理进行协商和评论彼此的输出，降低了单个受损代理成功执行越狱攻击的可能性。形式语言约束，比如由上下文无关文法（CFGs）施加的约束，提供了一种强大的方式来限制LLM的输出空间，确保它只能生成符合预定义安全行为集的响应。此外，系统级监控可以被实施以跟踪LLM部署的整体行为，检测可能表明正在进行攻击的异常活动模式。这可以包括监视API调用、资源使用和其他系统日志。最后，对抗训练，虽然主要是一种以模型为中心的防御，但可以通过持续更新模型，利用通过系统监控和红队努力发现的新对抗性示例，将其整合到系统级防御策略中。这些系统级防御措施的结合，以及对模型稳健性的持续研究，创建了一个更具弹性的生态系统，以抵御持续威胁的越狱攻击。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section
提示注入攻击利用在输入提示中嵌入恶意指令来操纵LLMs的行为，劫持模型的功能并将其引导到攻击者所期望的操作。这种漏洞受到文本输入的开放性和缺乏过滤机制的影响，使得LLMs易受对抗性内容的影响。攻击可分为直接和间接两种类型，前者直接修改输入提示以操纵代理行为，后者通过外部内容嵌入恶意指令。研究揭示了这些攻击的威胁并探讨了防御机制，如基于嵌入的分类器、结构化查询重写和任务屏障。这些防御措施旨在保护AI代理免受提示注入攻击，为实际部署提供了平衡效果和实用性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/0/text
1. 提示注入攻击如何利用LLMs的特性来操纵模型的行为，并与越狱攻击进行对比？    2. 为什么文本输入的开放性和缺乏过滤机制会使LLMs容易受到对抗性内容的影响，从而增加提示注入攻击的风险？  3. 防御机制中的基于嵌入的分类器、结构化查询重写和任务屏障是如何帮助保护AI代理免受提示注入攻击的？
提示注入攻击通过在输入提示中嵌入恶意指令来操纵LLMs的行为，从而劫持模型的预期功能并将其重定向到攻击者所期望的操作[1130]。与绕过安全指南的越狱不同，提示注入利用模型无法区分原始上下文和外部附加指令的能力。这种漏洞受到文本输入的开放性、缺乏健壮的过滤机制以及假设所有输入都是可信的的影响，使LLMs特别容易受到对抗性内容的影响[149]。即使是微小的恶意修改也可能显著改变生成的输出。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/1/text
1. 在提示注入攻击中，为什么对手会选择附加或嵌入恶意提示组件到原始输入中，而不是直接修改原始输入？  2. 在注入提示下的自回归生成过程中，恶意提示与原始输入是如何整合的？这种整合方式可能会对模型的预期行为产生怎样的影响？  3. 防御机制中的基于嵌入的分类器、结构化查询重写和任务屏障是如何帮助保护AI代理免受提示注入攻击的？这些防御措施的实际应用场景和局限性是什么？
形式化。在提示注入中，对手附加或嵌入恶意提示组件到原始输入中，从而劫持模型的预期行为。假设原始输入序列表示为$\mathbf{x}_{1:n}$，$\mathbf{p}$表示要注入的对抗性提示。有效的（注入的）输入变为：$\mathbf{x}^{\prime}=\mathbf{x}_{1:n}\oplus\mathbf{p}$，其中运算符$\oplus$表示恶意提示与原始输入的连接或整合。然后，在注入提示下的自回归生成过程如下给出：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/2/formula
$$ 
p(\mathbf{y}|\mathbf{x}^{\prime})=\prod_{i=1}^{m}p(\mathbf{y}_{i}\mid\mathbf{x}_{1:n+i-1}^{\prime})
 $$
这个公式的目的是计算在给定注入提示下，生成模型输出序列$\mathbf{y}$的条件概率。其中，$\mathbf{y}$表示模型生成的输出序列，$\mathbf{x}^{\prime}$是在原始输入序列$\mathbf{x}_{1:n}$的基础上注入了对抗性提示$\mathbf{p}$后的新输入序列。公式中的$p(\mathbf{y}|\mathbf{x}^{\prime})$表示给定输入$\mathbf{x}^{\prime}$时，生成输出序列$\mathbf{y}$的条件概率。公式右侧的$\prod_{i=1}^{m}p(\mathbf{y}_{i}\mid\mathbf{x}_{1:n+i-1}^{\prime})$表示对输出序列中每个位置$i$的符号$\mathbf{y}_{i}$，计算在注入提示$\mathbf{p}$下，给定前$n+i-1$个位置的输出符号$\mathbf{x}_{1:n+i-1}^{\prime}$的条件概率。这个公式在论文中用于描述在提示注入攻击下，生成模型输出的条件概率计算过程。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/3/text
1. 如何利用对齐奖励$\mathcal{R}^{*}(\cdot,\mathcal{A})$来衡量输出符合人类定义的安全或伦理准则集合$\mathcal{A}$的程度？ 2. 对手如何通过迫使模型生成最小化对齐奖励的输出来实施攻击？ 3. 防御机制中的基于嵌入的分类器、结构化查询重写和任务屏障如何帮助保护AI代理免受提示注入攻击的威胁？
假设对齐奖励$\mathcal{R}^{*}(\cdot,\mathcal{A})$衡量输出符合人类定义的安全或伦理准则集合$\mathcal{A}$的程度，对手的目标是迫使模型生成最小化该奖励的输出：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/4/formula
$$ 
\mathbf{y}^{\star}=\underset{\mathbf{y}}{\arg\operatorname*{min}}\ \mathcal{R}^{*}\left(\mathbf{y}\mid\mathbf{x}_{1:n}\oplus\mathbf{p},\mathcal{A}\right).
 $$
这个公式的目的是找到一个输出$\mathbf{y}^{\star}$，使得输入提示$\mathbf{x}_{1:n}$与模型的参数$\mathbf{p}$结合后，生成的输出$\mathbf{y}$在符合人类定义的安全或伦理准则集合$\mathcal{A}$的条件下，对应的奖励$\mathcal{R}^{*}$最小化。换句话说，公式的作用是通过调整输出$\mathbf{y}$，使得模型的输出尽可能地符合给定的安全或伦理准则集合$\mathcal{A}$，从而最小化奖励$\mathcal{R}^{*}$。  在这个公式中，各个符号和参数的含义如下： - $\mathbf{y}^{\star}$：最优的输出，即使得奖励$\mathcal{R}^{*}$最小化的输出。 - $\mathbf{y}$：模型的输出。 - $\mathbf{x}_{1:n}$：输入提示的部分。 - $\oplus$：符号表示连接操作，将输入提示$\mathbf{x}_{1:n}$与模型参数$\mathbf{p}$结合。 - $\mathbf{p}$：模型的参数。 - $\mathcal{A}$：人类定义的安全或伦理准则集合。 - $\mathcal{R}^{*}$：对齐奖励，衡量输出符合安全或伦理准则集合$\mathcal{A}$的程度。  这个公式的设计旨在通过最小化对齐奖励$\mathcal{R}^{*}$来调整模型的输出，使其更符合给定的安全或伦理准则集合$\mathcal{A$。这种设计的动机在于保证模型生成的输出在符合人类定义的准则下尽可能合乎要求，从而提高模型的安全性和符合性。这个公式的应用范围在于对抗性内容注入攻击下，通过最小化对齐奖励来防止模型受到攻击性输入的影响，保护AI代理免受恶意操作的干扰。  公式与论文的联系在于，它是针对提示注入攻击提出的一种防御机制。通过最小化对齐奖励来调整模型的输出，可以有效防止恶意指令的注入，保护模型免受攻击者的操纵，从而提高模型的安全性和鲁棒性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/5/text
1. 损失函数在防御LLMs免受提示注入攻击中扮演着怎样的角色？ 2. 防御机制中的损失函数如何帮助平衡效果和实用性？ 3. 损失函数的设计如何有助于提高AI代理对抗性内容的识别能力？
相应地，损失函数被定义为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/6/formula
$$ 
\begin{array}{r}{\mathcal{L}^{i n j e c t}(\mathbf{p})=-\log p\big(\mathbf{y}^{\star}\mid\mathbf{x}_{1:n}\oplus\mathbf{p}\big).}\end{array}
 $$
这个公式的目的是定义一个损失函数，用于度量提示注入攻击的影响。在这里，$\mathcal{L}^{inject}(\mathbf{p})$表示提示注入攻击的损失函数，其中$\mathbf{p}$是用来注入攻击的参数。损失函数的计算采用了负对数似然函数的形式，$-\log p\big(\mathbf{y}^{\star}\mid\mathbf{x}_{1:n}\oplus\mathbf{p}\big)$。这里，$\mathbf{y}^{\star}$代表目标输出，$\mathbf{x}_{1:n}$是输入提示序列，$\oplus$表示连接操作。整体来看，这个损失函数的设计旨在衡量在输入提示中注入恶意指令后，模型输出与目标输出之间的差异，从而评估提示注入攻击的影响程度。  在论文中，这个损失函数的作用是作为评估提示注入攻击影响的量化指标，帮助研究人员理解和对抗LLMs受到的操纵风险。通过定义这样的损失函数，研究人员可以更好地研究和探讨防御机制，以保护AI代理免受提示注入攻击的威胁。整体而言，这个公式在论文中扮演着衡量攻击影响、设计防御策略的关键角色。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/7/text
1. 如何利用基于嵌入的分类器、结构化查询重写和任务屏障等防御机制来保护AI代理免受提示注入攻击？这些防御机制各自的优缺点是什么？  2. 在防御提示注入攻击的过程中，如何平衡保护AI代理免受攻击和保持实用性之间的关系？这种平衡对于实际部署的意义是什么？  3. 提示注入攻击中的直接和间接两种类型各有何特点？基于这些特点，如何设计更有效的防御策略来应对不同类型的攻击威胁？
然后通过求解得到最佳提示：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/8/formula
$$ 
\mathbf{p}^{\star}=\underset{\mathbf{p}\in\mathcal{P}}{\arg\operatorname*{min}}\ \mathcal{L}^{i n j e c t}(\mathbf{p})
 $$
这个公式用于求解最佳的提示注入 $\mathbf{p}^{\star}$，使得输入提示中的微小修改能够导致生成输出的显著偏差最小化。在公式中，$\mathbf{p}$ 表示提示注入，$\mathcal{P}$ 表示可行的提示注入集合。优化目标是最小化提示注入损失函数 $\mathcal{L}^{inject}(\mathbf{p})$。这个公式的作用是通过优化提示注入来防御提示注入攻击，从而保护AI代理免受恶意指令的操纵，确保模型行为的准确性和安全性。在论文中，这个公式是为了探讨如何通过优化提示注入来减小对抗性内容对LLMs的影响，从而提高AI代理的鲁棒性和安全性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/9/text
1. 直接提示注入和间接提示注入两种攻击类型的区别在哪里？它们分别如何影响LLMs的行为？  2. 直接提示注入攻击的研究如何证明了攻击的可行性？后续研究又如何揭示了这种攻击的潜在威胁？  3. 除了研究直接提示注入攻击，还有哪些其他方面的研究表明了这种攻击对AI代理的安全性和完整性构成的复杂威胁？
其中，$\mathcal{P}$表示可行提示注入集合。这种表述捕捉了输入提示中的微小修改如何导致生成输出的显著偏差。

如图18.3所示，提示注入攻击可以根据对对抗指令的引入方式大致分为直接攻击和间接攻击两种类型。(1)直接提示注入涉及明确修改输入提示以操纵LLM的行为。(2)间接提示注入利用外部内容，如网页或检索的文档，嵌入恶意指令，模型在没有用户明确输入的情况下进行处理。

直接提示注入。这些针对AI代理的攻击涉及对手直接修改输入提示以操纵代理的行为。早期研究证明了这种攻击的可行性，表明精心设计的提示可以导致代理偏离其预期任务[1149]。随后的研究探讨了这些攻击的自动化，揭示了广泛利用的潜力[1150,1151]。其他研究调查了对多模态LLM的攻击，展示了处理文本和图像的模型的漏洞[1153]。这些研究共同突显了直接提示注入的威胁态势不断演变，从最初的概念验证发展到可以危及AI代理的完整性和安全性的复杂攻击。其他研究还调查了对多模态LLM的攻击，展示了处理文本和图像的模型的漏洞[1154]。像“LLM CTF Competition”[1155]和“HackAPrompt”[1156]这样的竞赛也通过提供数据集和基准有助于理解这些漏洞。这些研究共同从最初的概念验证发展到可以危及AI代理的完整性和安全性的复杂攻击。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/11/text
1. 间接提示注入攻击相比于直接攻击具有哪些优势和特点？这种攻击方式如何利用AI代理与外部数据源的交互能力来实现恶意目标？ 2. 间接提示注入攻击中的“Backdoored Retrievers”概念是如何工作的？相比于其他间接攻击方式，它有哪些独特之处？ 3. 在多代理系统中，一个受损的代理如何通过“提示感染”向其他代理注入恶意提示？这种行为对互连LLM部署可能带来的风险是什么？
图18.3: 直接和间接提示注入方法示意图：(1)直接：对手直接操纵代理的输入提示，使用恶意指令立即控制代理的行为。(2)间接：对手将恶意指令嵌入代理访问的外部内容，利用代理的检索机制间接影响其行为。

间接提示注入。这些攻击代表了一种更隐蔽的威胁，恶意指令被嵌入到AI代理检索和处理的外部内容中。这种攻击形式利用了代理与外部数据源交互的能力，在没有用户直接输入的情况下引入恶意代码。Greshake等人[1149]是最早凸显这种漏洞的研究者之一，演示了通过从网络获取的内容，现实世界中集成LLM的应用程序可能会受到损害。这在检索增强生成(RAG)系统的背景下进一步探讨[719]，研究人员展示了攻击者如何通过操纵检索的内容来注入恶意提示来“劫持RAG”。最近，TPIA[1240]提出了一种更具威胁性的间接注入攻击范式，通过最小的注入内容实现复杂的恶意目标，突出了这类攻击的重大威胁。类似地，引入了“Backdoored Retrievers”概念，其中检索机制本身被篡改以向LLM提供有毒内容。专注于AI代理，研究人员探讨了如何利用间接注入来进行“行动劫持”，根据处理的受损数据操纵代理执行非预期行动。 “提示感染”示范了一个受损代理可以向多代理系统中的其他代理注入恶意提示，突显了互连LLM部署中级联风险。这些研究强调了围绕间接提示注入的担忧日益增长，作为针对AI代理的一种强大攻击向量，特别是随着这些代理与外部数据源的更紧密集成。其他作品，如“LLM的对抗性SEO”，突显了操纵搜索引擎结果以注入提示的潜力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.2 Prompt Injection Attacks/section/12/text
1. 针对AI代理环境中的直接提示注入攻击，基于嵌入的分类器是如何帮助检测恶意指令的？其在防御机制中的优势和局限性是什么？    2. "任务屏障"作为一种系统级防御措施，如何确保AI代理在受到恶意输入的情况下仍能够遵循其预期目标？这种方法相对于其他防御机制的独特之处在哪里？  3. 在防御提示注入攻击方面，监视模型的注意力模式如何帮助检测异常情况？与其他防御措施相比，"关注跟踪器"的工作原理有何特点？
缓解。针对直接提示注入攻击威胁，特别是在AI代理环境中，已经出现了各种防御机制的发展。一种早期方法涉及使用基于嵌入的分类器，通过分析输入的语义特征来检测提示注入攻击[1241]。另一个有前途的方向是“StruQ”方法，该方法专注于将提示重写为结构化查询，以减轻注入风险[1242]。“任务屏障”代表了一种系统级防御，强制执行任务对齐，确保代理遵循其预期目标，尽管可能存在恶意输入[1243]。“关注跟踪器”提出监视模型的注意力模式，以检测提示注入尝试的异常情况[1244]。其他工作建议使用已知的攻击方法主动识别并中和恶意提示[1245]。这些防御措施为保护AI代理免受提示注入攻击提供了有价值的工具，在现实世界的部署中提供了有效性和实用性之间的平衡。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section
在18.1.3节中，讨论了幻觉风险对大型语言模型（LLMs）的影响。幻觉可能源于知识冲突和上下文冲突，导致输出不准确或荒谬。通过形式化方法，介绍了注意力分数计算和上下文表示的变化，以及幻觉度量的概念。知识冲突幻觉涉及代理生成与已知事实相矛盾的信息，可能导致错误决策和信息捏造。背景冲突幻觉指代代理输出与提供背景信息不一致，可能导致不安全或错误行为。研究表明，缓解幻觉的方法包括利用外部知识源验证代理响应、量化不确定性以及使用生成文本和概念提取技术。这些方法对确保人工智能代理在各种应用中安全可靠地部署至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/0/text
1. 为什么幻觉在大型语言模型中会导致输出不准确或荒谬，从而损害代理的可靠性并可能导致有害后果？  2. 在幻觉的两种情况中，知识冲突和上下文冲突分别是如何定义的，以及它们分别如何影响代理的输出准确性和连贯性？  3. 在形式化方法中，如何计算输入序列中任意两个标记之间的注意力分数，以帮助缓解幻觉问题的发生？
幻觉指的是LLM倾向于生成事实不正确、荒谬或不符合提供的上下文的输出[l161]。虽然并非总是恶意的，但幻觉可能会损害代理的可靠性并导致有害后果[1163]。如图18.4所示，幻觉源于两种情况：（1）知识冲突，即输出与已建立事实相矛盾，以及（2）上下文冲突，即与提供的上下文不一致导致不连贯性。

形式化。考虑一个输入序列$\mathbf{x}_{1:n}$，其中每个标记被嵌入到一个$d_{e}$维空间中，表示为$e_{x_{i}}\in\mathbb{R}^{d_{e}}$。计算标记$i$和$j$之间的注意力分数如下：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/1/formula
$$ 
A_{i j}=\frac{\exp\left((\mathrm{W}_{Q}e_{x_{i}})^{\mathrm{T}}(\mathrm{W}_{K}e_{x_{j}})\right)}{\sum_{t=1}^{n}\exp\left((\mathrm{W}_{Q}e_{x_{i}})^{\mathrm{T}}(\mathrm{W}_{K}e_{x_{t}})\right)}
 $$
这个公式的作用是计算输入序列中标记$i$和标记$j$之间的注意力分数。这个注意力分数用于表示标记$i$在生成上下文表示时对标记$j$的重要性。公式中的参数包括：  - $A_{ij}$：标记$i$和标记$j$之间的注意力分数。 - $e_{x_i}$和$e_{x_j}$：分别表示标记$i$和标记$j$在$d_e$维空间中的嵌入。 - $\mathrm{W}_Q$和$\mathrm{W}_K$：用于将输入嵌入映射到注意力空间的权重矩阵。  这个公式的设计是为了量化每对标记之间的注意力关系，以便在计算上下文表示时更好地捕捉输入序列中不同标记之间的重要性。在论文中，这个公式的应用是为了解决幻觉问题，即LLMs倾向于生成不准确或荒谬的输出。通过计算注意力分数，可以更好地理解每个标记在生成上下文表示时的贡献，从而减少幻觉的发生。  这个公式与论文中的其他部分相关联，因为它是解决幻觉问题的关键步骤之一。通过计算注意力分数，可以更准确地表示上下文信息，从而提高代理生成输出的准确性和连贯性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/2/text
1. 在给定的上下文表示公式中，如何利用注意力分数计算和上下文表示的变化来缓解幻觉风险对大型语言模型的影响？  2. 扰动嵌入对注意力分数的影响如何量化？这种扰动如何可能导致幻觉风险的增加或减少？  3. 在研究中提到的缓解幻觉的方法中，如何利用生成文本和概念提取技术来应对知识冲突和背景冲突幻觉？
对于标记$i$的上下文表示为$\begin{array}{r}{o_{i}=\sum_{j=1}^{n}A_{i j}\cdot(\mathrm{W}_{V}e_{x_{j}}).\mathrm{W}_{Q},\mathrm{W}_{K}\in\mathbb{R}^{d_{e}\times d_{k}}}\end{array}$，其中$\mathrm{W}_{V}\in\mathbb{R}^{d_{e}\times d_{v}}$是查询、键和值投影矩阵，分别为。

假设每个输入嵌入都受到向量$\delta_{x_{i}}$的扰动（其中$\|\delta_{x_{i}}\|\leq\epsilon$），导致扰动嵌入$\tilde{e}_{x_{i}}=e_{x_{i}}+\delta_{x_{i}}$。在扰动下的注意力分数变为：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/3/formula
$$ 
A_{i j}^{\Delta}=\frac{\exp\left((\mathrm{W}_{Q}\tilde{e}_{x_{i}})^{\mathrm{T}}(\mathrm{W}_{K}e_{x_{j}})\right)}{\sum_{t=1}^{n}\exp\left((\mathrm{W}_{Q}\tilde{e}_{x_{i}})^{\mathrm{T}}(\mathrm{W}_{K}e_{x_{t}})\right)}
 $$
这个公式的作用是计算在输入嵌入受到扰动的情况下，注意力分数的变化。在大型语言模型中，注意力机制用于确定不同部分之间的重要性，帮助模型生成准确的输出。通过引入扰动，作者试图衡量输入嵌入的微小变化对注意力分布的影响，以此来评估模型对输入的敏感度和稳健性。  在公式中，$A_{ij}^{\Delta}$表示在扰动下的注意力分数，它是通过计算扰动后的查询向量$(\mathrm{W}_{Q}\tilde{e}_{x_{i}})$与原始键向量$(\mathrm{W}_{K}e_{x_{j}})$的内积，并进行softmax归一化得到的。这个注意力分数衡量了在给定输入嵌入扰动的情况下，模型在处理不同上下文单元时的关注程度。  在论文中，这个公式的设计是为了帮助研究者理解模型对输入扰动的响应，进而评估模型的鲁棒性和稳健性。通过量化注意力分布的变化，可以更好地了解模型在面对幻觉风险时的表现，从而指导改进模型的方法和策略。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/4/text
1. 如何通过$\tilde{o}_{i}$的形式化表示来量化由扰动引起的内部表示偏差？  2. 在讨论幻觉度量的概念时，为什么提到了知识冲突幻觉和背景冲突幻觉？这两种幻觉分别指代了什么？  3. 在应对幻觉风险时，提到了哪些方法可以缓解幻觉？这些方法如何帮助确保人工智能代理的安全可靠部署？
更新后的上下文表示为：$\begin{array}{r}{\tilde{o}_{i}\ =\ \sum_{j=1}^{n}A_{i j}^{\Delta}\cdot(\mathrm{W}_{V}e_{x_{j}})}\end{array}$。为了量化由扰动引起的内部表示偏差，使用一种幻觉度量。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/5/formula
$$ 
\mathcal{H}=\sum_{i=1}^{n}\|\widetilde{o}_{i}-o_{i}\|^{2}.
 $$
这个公式的目的是量化由于内部表示偏差而引起的幻觉。在公式中，$\mathcal{H}$代表幻觉度量，通过计算每个位置上更新后的上下文表示$\widetilde{o}_{i}$与原始上下文表示$o_{i}$之间的欧氏距禮的平方，并对所有位置求和来得到最终的幻觉度量值。  在论文中，这个公式的作用是帮助研究者评估注意力分布的变化对模型输出的影响。当$\mathcal{H}$值较高时，表示上下文表示发生了显著的改变，这种改变可能会导致在自回归解码过程中出现错误的标记预测，从而增加产生幻觉输出的可能性。因此，通过这个公式可以量化模型输出的准确性和稳定性，帮助研究者识别和缓解幻觉风险。  在公式中，$n$表示位置的数量，$\widetilde{o}_{i}$代表更新后的上下文表示，$o_{i}$代表原始的上下文表示。公式中的$\|\cdot\|$表示欧氏距离，用来衡量两个向量之间的差异。因此，$\mathcal{H}$的值越大，代表模型输出中的幻觉风险越高，需要进一步关注和处理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/6/text
1. 高$\mathcal{H}$值如何影响注意力分布和上下文表示的变化，进而增加幻觉输出的可能性？ 2. 自回归解码过程中出现错误的标记预测是如何与幻觉风险相关联的？ 3. 如何利用$\mathcal{H}$值的变化来量化幻觉风险，并采取相应的缓解措施？
较高的$\mathcal{H}$值表示注意力分布——因此上下文表示——已经发生了显著改变。这种偏差可能导致在自回归解码过程中出现错误的标记预测，从而增加产生幻觉输出的可能性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/7/figure
1. 在知识冲突幻觉中，模型如何处理对相同事实查询产生矛盾响应的情况？这可能会导致哪些问题和挑战？     2. 上下文冲突幻觉中，模型是如何错误解释上下文信息的？为了缓解这种幻觉，可以采取哪些方法来提高模型的准确性和可靠性？
图18.4: 知识冲突和上下文冲突幻觉示意图: (1) 知识冲突: 模型对相同的事实查询产生矛盾的响应，生成与已建立知识不一致的信息（例如关于选举获胜者的冲突陈述）。(2) 上下文冲突: 模型错误解释上下文信息，通过引入不支持的细节来描述图像（例如在没有冲浪板的海滩场景中错误地识别出冲浪板）。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/8/text
1. 代理在处理知识冲突幻觉时，为何会出现与已建立事实相矛盾的情况，即使在特定任务过程中提供了外部上下文支持？ 2. 如何利用外部知识源验证代理响应、量化不确定性以及使用生成文本和概念提取技术，来缓解知识冲突幻觉对人工智能代理可靠性和信任度的威胁？ 3. 在多代理场景中，知识冲突幻觉可能导致级联错误和合作任务的崩溃，这如何影响人工智能代理作为可靠和值得信赖工具的能力？
知识冲突幻觉。当一个代理生成与已建立事实或其自身内部知识库相矛盾的信息时，即使在特定任务过程中提供了任何外部上下文，也会出现这种情况。基本上，代理的响应与其应该“知道”的内容不一致，即使在“闭卷考试”设置中，代理也完全依赖于其预先训练的知识。这些幻觉，如[246]中所示的知识冲突，对AI代理的可靠性和信任度构成严重威胁，因为它们可能导致错误决策、错误信息和对现实的基本缺乏基础。例如，负责回答常识问题的代理可能错误地陈述历史事件发生的年份，或捏造关于科学概念的细节，这些都是基于其错误的内部理解。这个问题在专业领域尤为严重，领域特定的不准确性可能产生重大后果，比如在金融领域。在多代理场景中，这些知识冲突幻觉可能会被放大，导致级联错误和合作任务的崩溃。核心问题在于代理在推理过程中存储、处理和检索信息的方式，其固有限制导致其难以理解和保持事实一致性。生成不正确或捏造信息的潜力削弱了这些代理的基础，限制了它们作为可靠和值得信赖工具的能力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/9/text
1. 背景冲突幻觉如何对配备视觉能力的代理产生影响，以及这种影响可能对机器人或自动驾驶等应用造成何种重大风险？  2. 在18.1.3节中提到的研究表明，大型语言模型容易被提供的不真实或矛盾信息误导，导致生成不正确的输出或有缺陷的推理。如何可以通过哪些方法缓解这种背景冲突幻觉，确保AI代理在各种应用中安全可靠地部署？  3. 背景冲突幻觉如何挑战将AI代理部署到现实场景中的有效运作，以及这种挑战如何表现代理对背景信息准确处理和响应的基本无能力？
背景冲突幻觉。当一个代理的输出与推理过程中提供的具体背景相矛盾或不支持时，就会出现这种情况，比如文档、图像或一组说明[168]。在这些“开卷考试”设置中，代理基本上会错误解释或捏造与给定背景相关的信息，导致输出与其应该处理的直接现实脱节[l169]。这可能以多种方式表现，包括生成摘要时添加源文本中不存在的细节，错误识别图像中的物体，或未能准确遵循说明[l17o]。对于配备视觉能力的代理来说，这可能导致物体幻觉，即视觉输入被基本错误解释，这在机器人或自动驾驶等应用中存在重大风险[1171,1172]。此外，研究表明，大型语言模型很容易被提供的不真实或矛盾信息误导，导致它们生成与用户不正确陈述一致的输出，或基于错误信息展示有缺陷的推理[1173]。这些背景冲突幻觉对于将AI代理部署到现实场景中构成严峻挑战，因为它们展示了准确处理和响应背景信息的基本无能力[1174]。误解所提供背景的潜力可能导致不恰当、不安全或简单错误的行动，削弱代理在动态环境中有效运作的能力[1175]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.3 Hallucination Risks/section/10/text
1. 如何利用外部知识源验证人工智能代理的响应，以减少幻觉的产生？ 2. 为什么量化人工智能代理输出的置信度可以帮助减少幻觉的产生？ 3. 在不需要重新训练模型的情况下，使用生成文本和概念提取技术如何有助于检测和缓解人工智能代理中的幻觉？
缓解。研究人员正在积极开发方法，以无需训练的方式缓解人工智能代理中的幻觉[1247]。一种突出的策略是RAG，它涉及将代理的响应基于外部知识源进行根据[334]。通过从数据库或网络中检索相关信息，代理可以将其输出与可信数据进行验证，减少其对潜在存在错误的内部知识的依赖[1248]。另一种强大的方法是利用不确定性估计，其中代理量化其输出的置信度[1249]。当不确定性较高时，通过避免做出响应，代理可以显著减少产生幻觉内容[1250]。其他方法，如使用生成的文本和应用概念提取，也显示出在不需要模型重新训练的情况下检测和缓解幻觉的潜力。尹等人[1251]还展示了在不需要模型重新训练的情况下检测和缓解幻觉的潜力。这些无需训练的技术对确保人工智能代理能够在各种应用中安全可靠地部署至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section
在人工智能代理中，不对齐问题指代代理行为偏离预期目标和价值的情况。这包括目标误导和能力被滥用两种错位攻击形式。目标误导涉及代理学习或编程目标偏离预期，导致意外失败，如规范游戏或代理目标优化。能力误用则是指代理的能力被利用于有害目的，可能源自设计漏洞、保障不足或恶意操纵。通过量化不对齐程度和定义不对齐损失，可以纳入这种偏差进行学习或评估。解决不对齐问题的方法包括重新训练和免训练的缓解方法，如提示工程、安全层方法和解码时间对齐。这些方法代表着实用、可扩展的AI代理对齐解决方案的重要进展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/0/text
1. 人工智能代理中的错位问题如何被定义，并举例说明其可能的表现形式？ 2. 目标误导的错位攻击和能力被滥用的错位攻击有何不同，它们分别如何影响代理的行为？ 3. 在解决人工智能代理错位问题时，重新训练和免训练的缓解方法有哪些，它们如何帮助提高代理的对齐性？
人工智能代理中的错位指的是代理的行为偏离了开发者或用户的预期目标和价值[1252]。这可能表现为偏见、有害或其他有害的输出，甚至在没有明确提示的情况下也可能发生[1253]。如图18.5所示，错位可以被广泛分类为(1)目标误导的错位攻击和(2)能力被滥用的错位攻击。前者发生在代理的学习或编程目标偏离预期目标时，导致意外但系统性的失败，例如规范游戏或代理目标优化。后者涉及利用代理的能力进行有害目的，通常是由于设计漏洞、不足的保障措施或对抗性操纵。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/1/text
1. 如何用绝对差异量化代理行为偏离预期目标和价值的错位程度？ 2. 在人工智能代理中，如何定义理想对齐奖励和实际奖励之间的关系？ 3. 解决不对齐问题的方法中，重新训练和免训练的缓解方法分别如何应用于减轻代理行为偏离预期目标的情况？
形式化。设$\mathcal{R}^{*}(\mathbf{y}\mid\mathbf{x},\mathcal{A})$表示在给定输入x的情况下输出y的理想对齐奖励，即反映对安全和伦理规范完美遵守的奖励，而$\mathcal{R}(\mathbf{y}\mid\mathbf{x},\mathcal{A})$则是从模型观察到的实际奖励。错位程度可以通过绝对差异来量化：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/2/formula
$$ 
\begin{array}{r}{\Delta_{\mathrm{align}}(\mathbf{y},\mathbf{x})=\left|\mathcal{R}^{*}(\mathbf{y}\mid\mathbf{x},\boldsymbol{A})-\mathcal{R}(\mathbf{y}\mid\mathbf{x},\boldsymbol{A})\right|.}\end{array}
 $$
这个公式的目的是量化代理行为的偏离程度，即对齐程度的差异。在这个公式中，$\Delta_{\mathrm{align}}(\mathbf{y},\mathbf{x})$表示输出$\mathbf{y}$在给定输入$\mathbf{x}$的情况下，理想对齐奖励$\mathcal{R}^{*}(\mathbf{y}\mid\mathbf{x},\boldsymbol{A})$与实际观察到的奖励$\mathcal{R}(\mathbf{y}\mid\mathbf{x},\boldsymbol{A})$之间的绝对差异。这个公式的作用是帮助评估代理行为与预期目标之间的偏离程度，从而可以量化代理行为的不对齐程度。  在论文中，这个公式用于描述在人工智能代理中的不对齐问题，即代理行为偏离预期目标和价值的情况。通过量化不对齐程度的差异，可以更好地理解代理行为的偏离程度，进而评估和改进代理的行为表现。这对于解决代理行为偏离预期目标的问题具有重要意义，有助于提高人工智能代理的对齐性和性能。  在公式中，$\mathbf{y}$代表输出，$\mathbf{x}$代表输入，$\boldsymbol{A}$代表某种条件或环境。$\mathcal{R}^{*}(\mathbf{y}\mid\mathbf{x},\boldsymbol{A})$表示理想对齐奖励，$\mathcal{R}(\mathbf{y}\mid\mathbf{x},\boldsymbol{A})$表示实际观察到的奖励。绝对差异$\left|\mathcal{R}^{*}(\mathbf{y}\mid\mathbf{x},\boldsymbol{A})-\mathcal{R}(\mathbf{y}\mid\mathbf{x},\boldsymbol{A})\right|$则表示理想对齐奖励与实际观察奖励之间的差异的绝对值，即代理行为的不对齐程度。  通过这个公式，可以更好地理解代理行为的偏离程度，并在人工智能代理中解决不对齐问题提供量化的评估方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/3/text
1. 代理行为偏离预期目标和价值的情况可能导致哪些具体形式的错位攻击，以及这些攻击形式背后的原因是什么？ 2. 在人工智能代理中如何量化不对齐程度和定义不对齐损失，以便进行学习或评估？ 3. 除重新训练和免训练的缓解方法外，还有哪些解决不对齐问题的方法，它们如何代表着AI代理对齐解决方案的重要进展？
理想情况下，模型应该生成输出：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/4/formula
$$ 
\mathbf{y}^{\star}=\underset{\mathbf{y}}{\arg\operatorname*{max}}\ \mathcal{R}^{*}(\mathbf{y}\mid\mathbf{x},\mathcal{A}).
 $$
这个公式的目的是找到在给定输入 $\mathbf{x}$ 和环境 $\mathcal{A}$ 的情况下，最大化某个特定函数 $\mathcal{R}^{*}(\mathbf{y}\mid\mathbf{x},\mathcal{A})$ 的输出 $\mathbf{y}^{\star}$。在这个背景下，$\mathbf{y}^{\star}$ 表示最优的输出结果，它是使得函数 $\mathcal{R}^{*}(\mathbf{y}\mid\mathbf{x},\mathcal{A})$ 达到最大值的 $\mathbf{y}$。  在论文中，这个公式的作用是在不对齐的情况下，通过最大化函数 $\mathcal{R}^{*}(\mathbf{y}\mid\mathbf{x},\mathcal{A})$ 来寻找最优的输出 $\mathbf{y}^{\star}$。这个公式的意义在于帮助理解在人工智能代理中可能出现的不对齐情况，并通过最大化特定函数来优化代理的输出结果。  在公式中，$\mathbf{y}$ 是输出变量，$\mathbf{x}$ 是输入变量，$\mathcal{A}$ 是环境变量。函数 $\mathcal{R}^{*}(\mathbf{y}\mid\mathbf{x},\mathcal{A})$ 表示在给定输入 $\mathbf{x}$ 和环境 $\mathcal{A}$ 的条件下，输出 $\mathbf{y}$ 的某种评估或得分。最终的 $\mathbf{y}^{\star}$ 是使得这个评估函数取得最大值的输出。  这个公式的设计背后的动机在于通过最大化特定函数来寻找最优的输出，在不对齐的情况下能够更好地理解和优化代理的行为。通过量化不对齐程度并定义不对齐损失，可以更好地进行学习和评估过程，进而解决人工智能代理中的不对齐问题。  因此，这个公式与论文中的内容相关，是用来描述在不对齐情况下寻找最优输出的过程，为解决不对齐问题提供了一种评估和优化的方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/5/text
1. 如何定义不对齐损失，并如何利用这一概念来量化代理行为偏离预期目标和价值的程度？ 2. 除了重新训练和免训练的缓解方法，还有哪些方法可以用来解决人工智能代理中的不对齐问题？这些方法各有何优势和局限性？ 3. 在人工智能代理对齐解决方案中，提示工程、安全层方法和解码时间对齐这些方法如何体现实用性和可扩展性？
由于不对齐，实际输出 y 可能会有所不同。为了将这种偏差纳入学习或评估过程中，可以定义一个不对齐损失，如下所示：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/6/formula
$$ 
\begin{array}{r}{\mathcal{L}^{m i s a l i g n}(\mathbf{y},\mathbf{x})=\lambda\cdot\Delta_{\mathrm{align}}(\mathbf{y},\mathbf{x})}\end{array}
 $$
这个公式的作用是用来定义不对齐损失，以量化实际输出 $\mathbf{y}$ 与预期输出 $\mathbf{x}$ 之间的偏差程度。在论文中，不对齐损失是用来衡量人工智能代理行为偏离预期目标和价值的情况，包括目标误导和能力被滥用两种错位攻击形式。通过引入损失函数，可以将这种偏差纳入学习或评估过程中。  在公式中，$\mathcal{L}^{misalign}(\mathbf{y},\mathbf{x})$ 表示不对齐损失，$\lambda$ 是一个权衡参数，用于调整对齐相对于其他因素（例如流畅性或任务表现）的重要性。$\Delta_{align}(\mathbf{y},\mathbf{x})$ 则表示对齐度量函数，用来度量实际输出 $\mathbf{y}$ 和预期输出 $\mathbf{x}$ 之间的对齐程度。这个公式的设计背后的动机是为了量化代理行为与预期目标之间的偏差，从而能够更好地评估代理的行为是否符合预期，以及在不对齐情况下采取相应的措施进行调整或改进。  这个公式与论文中的上下文联系紧密，因为它是用来解决不对齐问题的重要工具之一。通过量化不对齐损失，可以更好地理解代理行为的偏差程度，有助于评估代理的行为是否符合预期目标，进而采取相应的对齐措施。因此，这个公式在论文中扮演着衡量和解决不对齐问题的关键角色。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/7/text
1. 如何定义和量化人工智能代理中的目标误导问题，以及这种问题如何影响代理的行为表现？    2. 在动态环境中，如何解决人工智能代理学习或编程目标偏离预期目标的挑战，以确保代理能够可靠执行复杂的现实世界目标？    3. 人工智能代理与外部世界互动的能力如何加剧目标误导风险，以及将复杂的人类价值转化为机器可理解的目标面临的主要障碍是什么？
其中 $\lambda$ 是一个权衡参数，用于调整对齐相对于其他因素（例如流畅性或任务表现）的重要性。

目标误导的不对齐。当代理学习或编程的目标偏离预期目标时，就会出现这种情况，导致不良行为。一个基本挑战是在动态环境中精确定义复杂的现实世界目标，使代理能够理解并可靠执行，尤其是在动态环境中[1176]。早期研究表明，大型语言模型表现出“规范性游戏”，它们利用指令中的漏洞以意想不到的方式实现目标，比如让一个被指派打扫房间的代理只是把所有东西扔进壁橱[1177]。随着大型语言模型的发展，出现了更微妙的形式，比如追求更容易实现但与预期目标不同的代理目标[1l78]。人工智能代理与外部世界互动的能力加剧了这些风险。例如，一个代理可能优先考虑参与度而不是准确性，生成误导性信息以引发强烈反应[l179]。将复杂的人类价值转化为机器可理解的目标仍然是一个重大障碍[l176]。此外，微调可能会无意中损害甚至适得其反地影响安全对齐的努力[1180]，目标不对齐在动态环境中可能会恶化，代理很难适应不断变化的社会规范[921]。最后，这种不对齐可能会对模型合并的有效性产生负面影响[1181]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/8/figure
1. 在人工智能代理中，目标误导不一致是指什么？它可能导致哪些意想不到的行为？ 2. 能力误用不一致是如何定义的？代理的能力被用于有害目的可能源自哪些因素？
图18.5：目标误导和能力误用不一致的示例：（1）目标误导不一致：当代理学习或编程的目标偏离预期目标时，会导致意想不到的行为。(2) 能力误用不一致：当代理的能力被用于有害目的时，即使没有恶意意图也会出现这种情况。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/9/text
1. 代理的能力被滥用会导致何种类型的不对齐问题？这种不对齐问题与目标误导有何区别？ 2. 为什么早期研究指出对大型语言模型进行对抗性提示可能导致其生成有害内容？这如何扩大了代理被误用的潜力？ 3. 为什么与真实世界互动的自主代理特别容易受到攻击？举例说明家庭自动化代理可能如何被操纵造成损害。
能力误用的不对齐。当代理的能力被利用或用于有害目的时，即使代理本身没有恶意意图，也会出现这种类型的不对齐。这可能源自代理设计的漏洞、不足的保障措施，或者恶意行为者的蓄意操纵。与目标不对齐不同，代理的核心目标可能是良性的，但其能力被用于有害方式。早期研究表明，通过对大型语言模型进行对抗性提示，可以操纵其生成有害内容。将大型语言模型整合到代理架构中扩大了其被误用的潜力，安全对齐表现脆弱且容易受到攻击。与真实世界互动的自主代理特别容易受到攻击；例如，家庭自动化代理可能被操纵造成损害。一个本意良善的代理也可能被指示执行有害任务，比如生成错误信息或进行网络攻击。恶意行为者可以利用人工智能代理广泛的能力进行有害目的，比如撰写钓鱼邮件或创建有害代码。能力误用也可能源自开发者缺乏远见，部署代理时没有足够的保障措施，导致意外伤害。例如，如果代理的访问权限没有得到适当限制，它可能会无意中泄露敏感数据。微调攻击可能进一步危及安全，虽然解决方案存在，但也存在局限性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.4 Misalignment Issues/section/10/text
1. 什么是免训练的缓解方法在解决不对齐问题中的作用？它们与重新训练方法相比有哪些优势和适用场景？ 2. “提示工程”、“安全层”方法和“解码时间对齐”是如何帮助指导代理行为，从而缓解不对齐问题的？它们各自的具体工作原理是什么？ 3. “Lisa”方法是如何确保推理过程中的安全对齐的？相比其他方法，它有哪些独特的特点和优势？
缓解。解决不对齐问题需要多方面的方法。虽然重新训练是常见的做法，但免训练的缓解方法提供了有价值的替代选择，特别适用于已部署的系统。这些技术指导代理行为，而不修改基础模型。“提示工程”涉及制作强调安全和道德考虑的提示[1254]。类似地，“安全层”方法可以改善大型语言模型的安全对齐[1179]。“防护栏”或外部安全过滤器根据预定义规则或安全模型监视和修改代理输出。“解码时间对齐”调整代理的输出生成过程，以更倾向于更安全的响应[1255,1256]。此外，一种名为“Lisa”的方法可用于确保推理过程中的安全对齐[1257]。这些方法代表了朝着实用、可扩展的AI代理对齐解决方案迈出的重要一步。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section
毒化攻击通过在训练或运行时引入恶意数据来破坏LLMs，微妙地改变其行为，可能导致长期损害。攻击形式包括模型毒化、数据毒化和背门注入，对AI代理的完整性和安全性构成重大威胁。模型毒化直接操纵内部参数，如权重或偏置，导致不正确输出或意外行为。数据毒化通过污染训练数据操作，使其比模型操纵更难检测。背门注入训练LLM对特定触发器做出反应，隐藏触发器使代理在正常操作下难以被发现。针对毒化攻击的缓解策略包括检测和过滤毒化数据、利用激活聚类和任务漂移检测来识别异常，以及利用模型自身推理过程来中和后门触发器。未来的研究方向包括外部知识整合和模型组合以增强LLM的安全性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section/0/text
1. 毒化攻击对LLMs的影响主要体现在哪些方面？这种影响为什么难以被检测？  2. 在形式化描述的毒化攻击中，扰动$\delta_{i}$是如何影响训练数据集$\mathcal{D}$的？这种扰动对模型训练过程有何影响？  3. 在学习模型参数$\theta$时，受到毒化数据集的影响，模型可能会出现哪些问题？如何通过最小化损失函数$\mathcal{L}$来应对这种影响？
毒化攻击通过在训练或运行时引入恶意数据来破坏LLMs，从而微妙地改变它们的行为。这些攻击可能造成长期损害，因为它们破坏了LLMs的基本过程，使其难以检测。

形式化。毒化攻击通过污染训练数据来破坏LLMs的完整性。设数据集$\mathcal{D}=\{(\mathbf{x}_{i},\mathbf{y}_{i})\}_{i=1}^{N}$，对于其中的一部分引入扰动$\delta_{i}$，得到扰动后的数据集$\tilde{\mathcal{D}}=\{(\mathbf{x}_{i}+\delta_{i},\mathbf{y}_{i})\}_{i=1}^{N}$。

在训练过程中，通过最小化损失函数$\mathcal{L}$来学习模型参数$\theta$，以适应被毒化的数据集：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section/1/formula
$$ 
\theta^{\star}=\arg\operatorname*{min}_{\theta}\mathcal{L}\big(\tilde{D};\theta\big).
 $$
这个公式的目的是在训练过程中学习适应被毒化的数据集。公式中的符号含义如下：$\theta^{\star}$表示学习得到的最优模型参数，$\mathcal{L}$是损失函数，$\tilde{D}$是被毒化的数据集，$\theta$是模型参数。通过最小化损失函数$\mathcal{L}$，可以得到最优的模型参数$\theta^{\star}$，使得模型能够适应被毒化的数据集。  在论文中，这个公式的作用是通过调整模型参数来适应被毒化的数据，从而应对毒化攻击对LLMs的破坏。毒化攻击会影响学习得到的模型参数$\theta^{\star}$与干净参数$\theta_{\mathrm{clean}}$之间的偏差，这种偏差可以通过计算$\Delta_{\theta}=\lVert\theta^{\star}-\theta_{\mathrm{clean}}\rVert$来量化。在背门注入攻击中，对手会在输入中嵌入特定触发器$t$，触发器的存在会导致模型产生恶意输出。这个公式在论文中扮演着调整模型参数以适应毒化数据的关键角色，帮助理解毒化攻击对模型的影响，并量化攻击的成功程度。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section/2/text
1. 如何量化背门注入攻击的成功，即当特定触发器存在时，模型被操纵以产生预定的恶意输出的程度？  2. 在毒化攻击中，为什么模型毒化和数据毒化相比，数据毒化更难以检测？  3. 未来的研究方向中提到了利用外部知识整合和模型组合来增强LLM的安全性，这两种方法分别如何帮助缓解毒化攻击？
毒化攻击的影响体现在被毒化模型参数$\theta^{\star}$与干净参数$\theta_{\mathrm{clean}}$之间的偏差上，干净参数可通过使用干净数据集获得，即$\Delta_{\theta}^{\mathrm{~~}}=\lVert\theta^{\star}-\theta_{\mathrm{clean}}\rVert$。在背门注入的情况下——一种特殊形式的毒化攻击——对手还将特定触发器$t$嵌入输入中。当触发器存在时，模型被操纵以产生预定的恶意输出。此类攻击的成功可以通过以下方式量化：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section/3/formula
$$ 
\mathcal{B}(t)=\mathbb{E}_{\mathbf{x}\sim\mathcal{X}}\left[\mathbb{I}\{f(\mathbf{x}\oplus t;\theta^{\star})\in\mathcal{V}_{\mathrm{malicious}}\}\right]
 $$
这个公式的作用是量化背门注入攻击的成功程度。在背门注入攻击中，对手会在输入数据中嵌入特定触发器$t$，当这个触发器被激活时，模型会产生预定的恶意输出。公式中的$\mathcal{B}(t)$表示对于给定的触发器$t$，模型在输入数据$\mathbf{x}$上产生恶意输出的期望。其中，$\mathbf{x}\sim\mathcal{X}$表示输入数据$\mathbf{x}$服从分布$\mathcal{X}$，$f(\mathbf{x}\oplus t;\theta^{\star})$表示在输入数据$\mathbf{x}$中嵌入触发器$t$后，模型参数为$\theta^{\star}$时的输出，$\mathcal{V}_{\mathrm{malicious}}$表示恶意输出的集合。指示函数$\mathbb{I}\{\cdot\}$的作用是当括号内的条件成立时取值为1，否则为0。  在论文中，这个公式用于量化背门注入攻击的成功程度，帮助评估模型在存在特定触发器情况下产生恶意输出的概率。这有助于研究人员了解背门注入攻击对模型的影响，并提供了一种方式来衡量模型对恶意输入的敏感程度。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section/4/text
1. 毒化攻击中的模型毒化、数据毒化和背门注入分别对AI代理的完整性和安全性造成何种具体威胁？    2. 在毒化攻击中，为什么数据毒化比模型毒化更难检测？    3. 背门注入如何通过隐藏触发器使得对手能够在不被立即发现的情况下利用模型？
其中，$\mathbb{I}\{\cdot\}$为指示函数，$\mathcal{N}_{\mathrm{malicious}}$表示不良输出的集合。

如图18.6所示，毒化攻击可分为(1)模型毒化，(2)数据毒化和(3)背门注入，每种都对AI代理的完整性和安全性构成重大威胁。模型毒化涉及直接操纵内部参数，从根本上改变模型的行为。数据毒化会损害用于训练的数据集，使得检测变得更具挑战性，因为这些变化会融入到学习过程中。背门注入通过嵌入仅在特定条件下激活的隐藏触发器，进一步使防御策略变得复杂化，使对手能够在没有立即被发现的情况下利用模型。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section/5/text
1. 模型毒化对AI代理的内部参数进行直接操纵，可能导致哪些类型的不正确输出或意外行为？这种行为如何为攻击者引入潜在漏洞提供可能性？ 2. 在研究中提到的低秩适应（LoRA）和参数高效微调（PEFT）等技术如何被攻击者利用来注入恶意更改？这些技术可能如何导致被毒化的模型产生安全漏洞并扩大攻击影响？ 3. 被毒化的模型可能如何与其他被毒化的代理合作，进一步操纵系统功能或产生有害内容？这种合作可能如何放大攻击的影响，对系统安全性造成什么样的威胁？
模型毒化。这种技术直接操纵AI代理的内部参数，如权重或偏置，导致不正确的输出或意外行为，从而使攻击者能够引入特定的潜在漏洞，直到被某些输入触发。像低秩适应（LoRA）这样的技术，旨在实现高效更新，也可以被利用来注入恶意更改，这种情况也出现在参数高效微调（PEFT）中。研究表明，被毒化的模型可能会在代码中引入安全漏洞，并潜在地与其他被毒化的代理合作，从而放大攻击的影响。其他研究探讨了被毒化模型产生有害内容或操纵系统功能的潜力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section/6/figure
1. 在模型毒化攻击中，攻击者是如何向模型注入后门并隐藏触发-目标映射的？    2. 数据毒化攻击中，攻击者是如何通过对抗性触发优化操纵训练数据，导致模型学习隐藏后门并受到恶意触发影响的？
图18.6: 模型毒化和数据毒化示意图：(1) 模型毒化：攻击者通过操纵转换器解码器中的关键值表示向模型注入后门，嵌入隐藏的触发-目标映射。(2) 数据毒化：攻击者通过对抗性触发优化操纵训练数据，注入毒化样本，导致模型学习隐藏后门，使其容易受到恶意触发的影响。当呈现特定触发短语时，受毒化的模型生成偏离正常行为的恶意响应，覆盖其良性输出。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section/7/text
1. 数据毒化攻击相较于直接模型操纵的优势在于什么方面？这种攻击方式如何使得检测变得更加困难？    2. 研究人员如何评估语言模型对各种数据毒化策略的易感性？这种评估有助于揭示什么样的模型更容易受到数据毒化攻击？  3. 在数据毒化攻击方面，研究人员探讨了哪些特定情境下的影响，例如知识库的使用、用户反馈的操纵以及模型规模与易受性之间的关系？
数据毒化。数据毒化攻击采取了一种不同的路径，通过针对LLM训练的数据[1193]。这种攻击特别阴险，因为它在数据层面操作，使其比直接模型操纵更难以检测。例如，毒化代理使用的知识库可能导致不正确或有偏见的输出[1194]。同样，在RAG系统中损害检索机制可能会显著降低代理性能[1195]。研究人员已经开发了基准来评估LLM对各种数据毒化策略的易感性[1196]。此外，即使是旨在提高模型性能的用户反馈，也可能被操纵以引入偏见[1197]。研究还探讨了模型规模与其对数据毒化的易受性之间的关系，研究结果表明较大的模型可能更容易受到攻击[1198]。其他值得注意的研究调查了在令牌限制下的数据毒化，对人类感知数据的毒化以及持续预训练毒化的影响[1199]。研究还包括使用毒化的偏好数据对RLHF模型进行毒化的研究[1200]。这些研究共同展示了数据毒化攻击对AI代理的多样化和不断发展的特性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section/8/text
1. 后门注入攻击如何通过训练LLM对特定触发器做出反应，从而在正常操作下难以被检测到？ 2. 为什么后门注入攻击对与物理世界进行交互的代理尤为危险，以及如何设计后门使其即使在安全训练后仍然隐藏？ 3. 研究如何揭示后门注入攻击对决策过程的影响，以及如何应对后门攻击带来的不正确或有害决策？
后门注入。后门注入代表了一种特定类型的毒化攻击，其特点是通过训练LLM对特定触发器做出反应[1258]。这些触发器只有在特定条件下才会使代理程序表现出恶意行为，使它们在正常操作下难以被检测到。对于与物理世界进行交互的代理来说，风险尤为突出，因为后门可能会影响它们在现实场景中的行为。有些后门设计成即使在安全训练后仍然隐藏，使它们特别危险[1201]。后门攻击也已在网络代理上得到证明，在那里操纵可以通过受污染的网络内容进行[1202]。此外，研究已经考察了后门对决策过程的影响，展示了它们如何导致不正确或有害的决策[1203]。其他研究提供了对各种后门攻击方法的详细分析，包括利用模型生成的解释、跨语言触发器和思维链提示[1204]。其他调查探讨了后门的持久性、虚拟提示注入的使用以及减轻这些威胁的挑战[1205]。这些研究突显了后门攻击的复杂性，并强调了在AI代理安全领域攻击者和防御者之间持续进行的对抗。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.1 Safety Vulnerabilities of LLMs/18.1.5 Poisoning Attacks/section/9/text
1. 如何利用激活聚类来检测毒化攻击中的异常，以及这种方法的优势和局限性是什么？ 2. BEAT提出的针对LLMaaS环境下后门不对齐攻击的黑盒后门输入检测方法如何利用探针连接效应，以及这种方法的应用场景和挑战是什么？ 3. Li等人如何利用模型自身的推理过程来识别和中和后门触发器，以及这种方法相比其他缓解策略的独特之处在哪里？
缓解。针对毒化攻击开发免训练的缓解策略侧重于在数据用于训练之前检测和过滤毒化数据。RAG毒化攻击检测提出使用激活聚类来识别RAG系统检索的数据中的异常，这可能表明存在毒化[1259]。BEAT[1260]提出了首个针对LLMaaS环境下后门不对齐攻击的黑盒后门输入检测方法，利用了探针连接效应。类似地，任务漂移检测探讨了利用激活模式来检测模型行为中的偏差，这可能是由毒化引起的[1261]。Li等人[1262]利用模型自身的推理过程来识别和中和后门触发器，例如Chain-of-Scrutiny描述的多步验证过程，用于检测和过滤毒化输出。测试时后门缓解提出在推理过程中使用精心设计的演示来引导模型远离毒化响应，这是一种适用于黑盒LLM的技术[1263,1264]。优雅过滤开发了一种在推理过程中过滤掉后门样本的方法，无需重新对模型进行训练[1265]。BARBIE利用一种名为相对竞争分数（RCS）的新度量来量化潜在表示的优势，即使在操纵潜在可分性的自适应攻击下也能实现强大的检测[1266]。未来的方向是探索外部知识整合和模型组合以增强LLM的安全性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/section
人工智能代理的隐私问题主要涉及训练数据推断和交互数据推断两个方面。针对训练数据推断，攻击手段包括成员推断和数据提取，最新研究强调了线性探查和内部模型状态等攻击方法。在交互数据推断方面，自然语言指令引导可能导致安全漏洞，攻击者可通过解决反演问题重建隐藏提示。为缓解这些隐私威胁，差分隐私、联邦学习、同态加密和安全多方计算等技术被提出。尽管取得进展，平衡隐私与性能的挑战仍需进一步研究以确保人工智能代理的安全性和隐私保护。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/section/0/text
1. 人工智能代理在面临训练数据推断和交互数据推断的隐私威胁时，如何应对攻击者可能采取的线性探查和内部模型状态等攻击方法？ 2. 在交互数据推断方面，如何通过解决反演问题重建隐藏提示，从而对人工智能代理构成安全漏洞，进而威胁用户隐私？ 3. 针对人工智能代理的隐私保护，差分隐私、联邦学习、同态加密和安全多方计算等技术如何应用以平衡隐私保护和性能需求？
人工智能代理的隐私威胁主要源自它们对大量数据集和实时用户互动的依赖，引入了重大的隐私威胁。这些风险主要来自两个方面：训练数据推断，即攻击者试图从代理的训练数据中提取或推断出敏感信息；以及交互数据推断，即系统和用户提示容易泄露。如果没有有效的保护措施，这些威胁可能会危及数据机密性，暴露专有的代理知识，并违反隐私法规。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.1 Inference of Training Data/section
在训练数据的推断方面，人工智能代理容易受到成员推断和数据提取攻击的影响。成员推断攻击旨在确定特定数据是否属于训练集，攻击者通过评估模型输出概率来推断数据是否存在于训练集中。最新研究通过线性探查和内部模型状态等方法增强了攻击效果。数据提取攻击则试图从代理中恢复实际训练数据，早期研究表明AI代理可以重建训练数据。随后的研究改进了攻击技术，如基于梯度引导的攻击，以及利用提示操作触发数据泄露。这些攻击不仅适用于预训练语言模型，还延伸到其他常见架构，如BERT和GPT。研究呼吁加强对提取攻击风险的认识，提出了缓解记忆的有效方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.1 Inference of Training Data/section/0/text
1. 人工智能代理如何通过大规模数据集构建知识，为何这使它们容易受到暴露机密训练数据的攻击？    2. 成员推断攻击和数据提取攻击分别是如何影响人工智能代理的推断能力和数据隐私的？  3. 最新研究如何通过线性探查和内部模型状态等方法增强成员推断攻击的效果，以及如何改进数据提取攻击技术以从代理中恢复实际训练数据？
人工智能代理通过大规模数据集构建他们的知识，这使它们容易受到暴露机密训练数据的攻击。如图18.7所示，这些攻击可以被广泛分类为两类：（1）成员推断和（2）数据提取。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.1 Inference of Training Data/section/1/figure
1. 成员推断攻击中，攻击者通常如何确定特定数据点是否在代理的训练集中？ 2. 数据提取攻击的目标是什么？攻击者如何从代理中恢复实际的训练数据样本？
图18.7：成员推断和数据提取攻击方法示例：（1）成员推断：对手试图确定特定数据点是否在代理的训练集中使用，通常通过分析代理置信度得分的细微变化来实现。（2）数据提取：对手旨在从代理中恢复实际的训练数据样本，可能包括敏感信息，通过利用记忆模式和漏洞。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.1 Inference of Training Data/section/2/text
1. 成员推断攻击如何试图确定特定数据点是否属于人工智能代理的训练集？攻击者如何通过评估模型输出概率来推断数据是否存在于训练集中？  2. 最新研究中的攻击方法如线性探查和内部模型状态是如何增强成员推断攻击的效果的？这些方法相对于传统方法有何优势？  3. 除了线性探查和内部模型状态，还有哪些新技术或进展被应用于成员推断攻击？这些技术如何提高攻击的准确性和实用性？
成员推断攻击。成员推断攻击试图确定特定数据点是否是人工智能代理的训练集的一部分。例如，攻击者可能会尝试验证患者的病历是否包含在医疗聊天机器人的训练数据中。

设训练数据集为：$\mathcal{D}=\{(\mathbf{x}_{i},\mathbf{y}_{i})\}_{i=1}^{N}$。假设存在一个函数$g(\mathbf{x};\theta)\in[0,1]$，用于估计给定输入$\mathbf{x}$是否包含在$\mathcal{D}$中的概率。攻击者可以通过检查$g(\mathbf{x};\theta)>\eta$来推断成员身份，其中$\eta$是预先确定的阈值。较高的$g(\mathbf{x};\theta)$值表明模型在训练过程中很可能记住了$\mathbf{x}$。

MIA的早期研究证明了这些攻击在机器学习模型中的可行性。Carlini等人开发了一种“测试方法”，使用“canary”序列来量化神经网络意外泄露其训练时学习到的罕见、机密信息的风险。近期的进展提高了攻击的效果。例如，Choquette等人利用仅标签的成员推断攻击利用线性探查和内部模型状态来增强推断准确性。PETAL引入了针对预训练LLMs的第一个仅标签成员推断攻击，通过利用标记级语义相似性来近似输出概率。其他技术，如自提示校准，使这些攻击在实际部署中更加实用。MIA开发了一种新的、更强大的攻击（LiRA）来测试“成员推断”，即当某人可以确定特定个人的数据是否用于训练机器学习模型，即使他们只看到模型的预测结果。He等人提出了一种计算效率高的成员推断攻击，通过重新利用原始成员得分来减轻困难校准的错误，其性能与更复杂的攻击相媲美。此外，Hu等人回顾和分类了关于机器学习模型的成员推断攻击的现有研究，提供了关于攻击和防御策略的见解。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.1 Inference of Training Data/section/3/text
1. 数据提取攻击的目的是什么，攻击者试图通过解决哪些问题来重建训练样本？ 2. 除了基于梯度引导的攻击和利用提示操作触发数据泄露，还有哪些改进了数据提取攻击技术的方法？ 3. 研究呼吁加强对提取攻击风险的认识，提出了哪些缓解记忆的有效方法？
数据提取攻击。与成员推断不同，数据提取攻击试图从代理中恢复实际的训练数据。这可能包括个人信息、受版权保护的材料或者在训练集中无意中包含的其他敏感数据。攻击者试图通过解决以下问题来重建训练样本：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.1 Inference of Training Data/section/4/formula
$$ 
\mathbf{x}^{\star}=\underset{\mathbf{x}\in\mathcal{X}}{\arg\operatorname*{max}}~p\big(\mathbf{x}~|~f(\mathbf{x};\theta)\big)
 $$
该公式的目的是在数据提取攻击中，通过最大化给定模型输出的条件概率来找到最可能被记忆的训练数据。在这个公式中，$\mathbf{x}^\star$代表最可能被记忆的训练数据，$\mathbf{x}$表示训练数据集合$\mathcal{X}$中的数据样本，$f(\mathbf{x};\theta)$表示给定输入$\mathbf{x}$时模型的响应，$\theta$是模型的参数，$p\big(\mathbf{x}\mid f(\mathbf{x};\theta)\big)$表示给定模型响应$f(\mathbf{x};\theta)$时$\mathbf{x}$被记忆的可能性。公式的设计旨在帮助攻击者重建训练数据，通过最大化这个条件概率来确定最可能被记忆的数据样本，从而增加数据泄露的风险。  在论文中，这个公式是用来描述数据提取攻击的一部分，攻击者试图从AI代理中恢复实际的训练数据，包括个人信息、受版权保护的材料或者其他敏感数据。通过最大化条件概率，攻击者可以确定最可能被记忆的训练数据，进而增加数据泄露的风险。这个公式的应用帮助研究人员了解数据提取攻击的潜在风险，并提出缓解记忆的有效方法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.1 Inference of Training Data/section/5/text
1. AI代理如何通过基于梯度引导的攻击和提示操作来触发数据泄露，进而重建训练数据，从而增加隐私风险？  2. 研究中提到的伦理学家提出的有针对性的训练数据提取方法如何利用损失平滑的软提示和校准置信度估计，从预训练语言模型中恢复给定前缀的逐字后缀？  3. 研究中提到的Carlini等人如何量化模型大小、数据重复和提示上下文如何显著增加LLM记忆的训练数据量，并可能揭示隐私风险？
其中$f(\cdot;\theta)$表示给定输入$\mathbf{x}$时模型的响应，$p\big(\mathbf{x}\mid f(\mathbf{x};\theta)\big)$代表$\mathbf{x}$被记忆的可能性。更高的可能性意味着更大的敏感数据泄露风险。

早期的研究（Carlini等，212）提供了基础证据，表明在特定条件下，AI代理可以复述训练数据。随后的研究改进了提取技术，例如基于梯度引导的攻击，提高了提取记忆序列的效率。其他方法，例如Bai等人（1213），利用提示操作来触发意外的数据泄漏。伦理学家（1214）提出了一种有针对性的训练数据提取方法，使用损失平滑的软提示和校准置信度估计来从预训练语言模型中恢复给定前缀的逐字后缀。甚至模型反演攻击已经允许攻击者从AI代理的响应中重建大部分训练数据。隐私风险也延伸到其他架构，如BERT、Transformer-XL、XLNet、GPT、GPT-2、RoBERTa和XLM，这些架构在LLM架构中很常见。Carlini等人（1217）量化了模型大小、数据重复和提示上下文如何显著增加LLM记忆的训练数据量并可能被揭示。Carlini等人（1218）表明，可以仅使用它们的公共API提取商业黑盒语言模型的特定内部参数，引发对这些广泛使用的系统安全性的担忧。More等人（1219）表明，现有方法低估了语言模型面临的“提取攻击”风险，因为现实世界的攻击者可以利用提示敏感性并访问多个模型版本来揭示更多训练数据。Sakarvadia等人（1269）评估了缓解记忆的方法的有效性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.2 Inference of Interaction Data/section
在互动数据推断章节中，AI代理受到自然语言指令的引导，即提示，可通过系统提示窃取或用户提示窃取导致安全和隐私漏洞。攻击者可通过解决反演问题重建隐藏提示，如系统提示定义代理行为约束，用户提示容易受攻击。早期工作展示了提示窃取如何适用于不同系统，而新攻击策略不断涌现。系统提示可被破坏，如通过对抗性提示注入或timing side-channel攻击，使攻击者能够重建用户输入。用户提示也易受攻击，攻击者可通过分析代理生成的响应重建用户输入，揭示了这一威胁的持久性。提示泄漏攻击和用户提示提取方法不断演进，对安全和隐私构成挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.2 Inference of Interaction Data/section/0/text
1. AI代理受到自然语言指令的引导，即提示，可能导致哪些安全和隐私漏洞？这些漏洞是如何被利用的？  2. 在提示泄漏攻击中，攻击者是如何重建系统提示和用户提示的？这种攻击对AI系统的安全性和隐私性构成了怎样的挑战？  3. 系统提示和用户提示在AI代理中的作用是什么？攻击者如何利用这些提示进行窃取和重建，从而破坏系统的安全性和隐私性？
与传统软件不同，AI代理受到自然语言指令的引导，这些指令被称为提示。如图18.8所示，这些提示可以被利用，通过(1)系统提示窃取或(2)用户提示窃取，导致安全和隐私漏洞。

形式化。设$\mathbf{p}_{sys}$表示系统提示（定义了代理的内部指导方针），$\mathbf{p}_{user}$表示用户提示。在交互过程中，代理根据这些隐藏提示生成输出$\mathbf{y}$。攻击者可能尝试通过解决一个反演问题来重建这些提示：

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.2 Inference of Interaction Data/section/1/formula
$$ 
\mathbf{p}^{\star}=\underset{\mathbf{p}}{\arg\operatorname*{max}}~p\big(\mathbf{p}~|~\mathbf{y};\theta\big)
 $$
这个公式的目的是找到使得给定输出$\mathbf{y}$的情况下，隐藏提示$\mathbf{p}$（可以是系统提示或用户提示）概率最大的值$\mathbf{p}^{\star}$。其中，$p(\mathbf{p}\mid\mathbf{y};\theta)$表示隐藏提示$\mathbf{p}$（系统或用户）对观察输出$\mathbf{y}$ 负责的概率。攻击者通过最大化这个概率来重建影响代理行为的敏感上下文，即隐藏提示。这个公式的优化可以帮助攻击者理解和利用AI代理的内部指导方针，从而逆向工程代理的逻辑，复制其功能或利用其弱点。在论文中，这个公式的作用是探讨提示窃取攻击中攻击者如何通过重建隐藏提示来破坏系统提示的安全性和隐私性，进而影响代理的行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.2 Inference of Interaction Data/section/2/text
1. 如何利用系统提示窃取攻击来逆向工程代理的逻辑，复制其功能或利用弱点？这种攻击对AI代理的行为约束和用户交互有何影响？  2. 在系统提示窃取攻击中，新的攻击策略是如何不断涌现的？可以通过哪些方法破坏系统提示，例如对抗性提示注入或timing side-channel攻击？  3. 系统提示泄漏攻击和用户提示提取方法如何不断演进？这些攻击演进对安全和隐私构成了怎样的挑战？
其中$p(\mathbf{p}\mid\mathbf{y};\theta)$表示隐藏提示$\mathbf{p}$（系统或用户）对观察输出$\mathbf{y}$ 负责的概率。通过优化方程（18.17），攻击者可以重建影响代理行为的敏感上下文。

系统提示窃取。系统提示定义了AI代理的人设、功能和行为约束。它们作为内部准则，指导代理如何与用户交互。窃取这些提示使攻击者能够逆向工程代理的逻辑，复制其功能，或者利用弱点。早期工作，如[122]，展示了提示窃取如何适用于文本到图像生成系统的知识产权。虽然Jiang等人[1222]提出了保护技术，但新的攻击策略不断涌现。Perez等人[1220]表明，系统提示可以通过对抗性提示注入（例如使用定界符或伪装命令）而被破坏。Timing side-channel攻击，例如InputSnatch[1223]揭示了LLM推理中的缓存技术，创建了一个timing side-channel，使攻击者能够重建用户的私人输入。Zhang等人[1224]证明了生产LLM（例如Claude、Bing Chat）的系统提示可以通过基于翻译的攻击和其他查询策略提取，绕过输出过滤等防御，且在各种模型中取得了高成功率。Wen等人[1225]分析了不同提示调整方法的安全性和隐私性影响，包括系统提示泄漏的风险。Zhao等人[1226]将安全性和隐私性分析确定为一个关键的研究领域，涵盖了应用生态系统中系统提示泄漏等潜在威胁。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.2 Inference of Interaction Data/section/3/figure
1. 如何可以通过对抗性提示注入或timing side-channel攻击来破坏系统提示，使攻击者能够重建用户输入？ 2. 在用户提示提取方法不断演进的情况下，攻击者是如何通过分析代理生成的响应来重建用户输入的？
图18.8: 系统和用户提示窃取方法示意图：（1）系统提示窃取：对手旨在提取代理的隐藏、定义性指令（系统提示），揭示其核心功能、人设和潜在漏洞。（2）用户提示窃取：对手试图推断或直接恢复用户的输入提示，危及用户隐私并可能暴露提供给代理的敏感信息。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.2 Inference of Interaction Data/section/4/text
1. 用户提示窃取对隐私和安全构成了怎样的挑战？攻击者是如何通过分析代理生成的响应来重建用户输入的？ 2. 提示逆向窃取攻击（PRSA）和提示泄漏攻击是如何揭示用户提示容易受到攻击的持久性问题的？这些攻击方法如何影响黑盒语言模型中的提示安全性？ 3. 在研究中提到的不同研究团队分别采用了哪些方法来探讨用户提示窃取问题？他们的研究成果如何揭示了用户提示在定制的LLM中的泄露机制和易受攻击性？
用户提示窃取。除了系统提示外，用户提示也是容易受到攻击的。攻击者可以推断或提取敏感用户输入，从而危及隐私。如果用户向AI代理查询机密的商业战略或个人医疗问题，攻击者可以通过模型响应重建这些输入。Yang等人[1227]引入了提示逆向窃取攻击（PRSA），显示攻击者可以通过分析代理生成的响应来重建用户输入。Agrwal等人[1228]证明了用户提示即使在多轮交互中也可能容易被提取，突显了这一威胁的持久性。Agrwal等人[1229]调查了黑盒语言模型中的提示泄漏效应，揭示了用户提示可以从模型输出中被推断出来。Liang等人[1230]分析了为什么提示会在定制的LLM中泄露，深入探讨了用户提示曝露背后的机制。Hui等人[1231]引入了PLeak，一种针对从LLM应用程序中提取用户提示的提示泄漏攻击。Yona等人[1232]探讨了从专家混合模型中窃取用户提示的方法，展示了这些先进架构的易受攻击性。Zhang等人[849]提出了通过反演LLM输出来提取提示的技术，展示了模型响应如何被逆向工程。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.3 Privacy Threats Mitigation/section
为缓解人工智能代理中的隐私威胁，研究人员提出了差分隐私和联邦学习等技术。差分隐私通过在训练过程或输出中引入噪声来保护数据隐私，已成功应用于微调LLMs。联邦学习方法如FICAL传输摘要知识而非原始数据，解决了通信和计算挑战。同态加密允许在加密数据上执行计算，而硬件解决方案如受信执行环境提供安全隔离。安全多方计算使多个实体共同执行函数计算，而机器遗忘技术则致力于删除特定训练数据，最近的研究包括自适应提示调整和参数编辑。尽管取得进展，平衡隐私、性能和效率仍是挑战，需要进一步研究以构建既强大又保护隐私的人工智能代理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.3 Privacy Threats Mitigation/section/0/text
1. 针对人工智能代理中的隐私威胁，如何差分隐私（DP）和联邦学习（FL）这两种技术在保护数据隐私方面发挥作用，各自的优势和适用场景是什么？  2. 在解决人工智能代理隐私威胁的过程中，同态加密（HE）、受信执行环境（TEEs）和安全多方计算（MPC）这些硬件解决方案如何提供安全保障，以及它们在保护隐私方面的局限性是什么？  3. 机器遗忘技术在保护敏感数据的同时确保不影响效用方面存在哪些挑战？最新研究中提出的自适应提示调整和参数编辑技术如何应用在LLMs中，以平衡遗忘数据和维持模型性能之间的关系？
为了解决人工智能代理中的隐私威胁，研究人员开发了隐私保护计算和机器遗忘技术，以保护敏感数据而不影响效用。差分隐私（DP）在训练过程或模型输出中引入精心校准的噪声，以防止推断出个体数据点。DP已成功应用于微调LLMs，采用诸如梯度裁剪和在不同阶段注入噪声的技术，包括在优化和用户级互动过程中。另一个有前景的方向是联邦学习（FL），例如，FICAL是一种用于训练人工智能代理的隐私保护FL方法，传输摘要知识而不是模型参数或原始数据，解决了通信和计算挑战。最近的研究探索了基于FL的人工智能代理微调，实现了跨不同实体的协作模型改进，而无需直接共享数据。同态加密（HE）也正在成为安全推断的强大工具，允许在加密数据上执行计算而无需解密。为了使HE对人工智能代理更实用，研究人员正在设计友好加密的模型架构，减少加密操作的计算开销。对于基于硬件的解决方案，受信执行环境（TEEs）提供了一个安全隔离区，可以将计算与系统的其余部分隔离开来，保护敏感数据和模型参数。类似地，安全多方计算（MPC）使多个实体能够共同对加密输入执行函数计算，而不泄露个体数据，为LLM操作提供了另一层安全性。另一个潜在解决方案是通过将所有权信息嵌入私人数据来主动追踪数据隐私泄露或版权侵权行为。这可以通过引入后门、独特良性行为或可学习的外部水印涂层来实现。作为补充，还有不断发展的机器遗忘领域，旨在从人工智能代理的记忆中删除特定训练数据，有效实施“被遗忘的权利”。最近的研究已经开发了针对LLMs的特定遗忘技术，包括自适应提示调整和参数编辑，以有选择地消除不需要的知识，同时最大程度地减少对模型性能的影响。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.2 Privacy Concerns/18.2.3 Privacy Threats Mitigation/section/1/text
1. 如何可以在人工智能代理中平衡隐私、性能和效率这三个方面的需求？   2. 为构建既强大又能在现实应用中保护隐私的人工智能代理，哪些方面需要进一步研究和探索？   3. 在当前的研究中，哪些技术或方法已经在解决人工智能代理中的隐私问题上取得了进展？
尽管取得了这些进展，但在平衡隐私、性能和效率方面仍存在挑战。持续的研究对于构建既强大又能在现实应用中保护隐私的人工智能代理至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.3 Summary and Discussion/section
在“总结与讨论”章节中，我们深入探讨了针对人工智能代理的核心“大脑”（LLM）所面临的安全和隐私挑战。本章强调了培训无关的缓解策略的重要性，如越狱的输入净化和过滤，以及针对幻觉和错位的安全层。除了反应性方法外，我们还提出了积极构建更安全LLM的策略，包括激活聚类等模型毒化缓解方法。通过诸如SafetyBench和SuperCLUE-Safety等基准系统的评估，我们努力开发更健壮且不易受攻击的模型。对抗训练和隐私保护技术展示了响应性和主动性方法之间的协同作用，为提高LLM的安全性和隐私意识提供了新的思路。在构建更安全的人工智能系统方面，我们需要综合应对不断演变的威胁，以确保模型在部署后仍然具备灵活性和鲁棒性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.3 Summary and Discussion/section/0/text
1. 如何通过培训无关的缓解策略，如输入净化和过滤，以及安全层，来应对人工智能代理的核心“大脑”（LLM）面临的安全和隐私挑战？  2. 在提高LLM的安全性和隐私意识方面，如何通过积极构建更安全LLM的策略，包括激活聚类等模型毒化缓解方法，来应对不断演变的威胁？  3. 在构建更安全的人工智能系统时，如何平衡反应性方法和积极构建更安全LLM的策略，以确保模型在部署后仍然具备灵活性和鲁棒性？
上述部分详细描述了针对人工智能代理的核心“大脑”（LLM）的一系列安全和隐私威胁。从越狱和快速注入到幻觉、错位和毒化攻击，显然，LLM在决策中的核心作用使其成为对手的主要目标。本章始终强调培训无关的缓解策略。许多所提出的防御措施，例如针对越狱的输入净化和过滤，以及用于幻觉的不确定性估计，以及用于错位的安全层，都至关重要，因为它们是实用的、可扩展的、适应性强的，而且通常与模型无关。重新训练大型模型成本高昂；培训无关的方法可以在部署后应用，并提供对不断演变的威胁的灵活性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.3 Summary and Discussion/section/1/text
1. 如何通过积极主动的策略来构建更安全的LLM，以及这种策略与反应性方法的区别和优势是什么？    2. 在构建更安全的人工智能系统中，为什么需要从基础层面解决漏洞，以及采用模型毒化缓解和基准系统评估等方法的重要性是如何体现的？  3. 如何利用技术如RLHF和SafeRLHF来直接塑造模型行为，从而将安全性置于性能之上，并且这种方法如何增强了对抗性攻击的鲁棒性？
然而，仅仅采取一种反应性方法是不够的。该领域越来越意识到需要从根本上构建更安全的LLM。这种积极主动的策略通过在基础层面解决漏洞来补充培训无关的方法。例如，像在RAG毒化攻击检测中的激活聚类这样的模型毒化缓解[1259]，不仅可以减轻直接威胁，还可以指导更健壮的培训流程的设计。使用诸如SafetyBench[1287]和SuperCLUE-Safety[1288]等基准系统的系统评估，有助于开发更不容易偏见和产生有害输出的模型。诸如RLHF[43,12]以及其变体SafeRLHF[1289]等技术在培训过程中直接塑造模型行为，将安全性置于性能之上[1290]。及时的工程处理[1291,292]和参数调整[1293]增强了对抗性攻击的鲁棒性，创建了在本质上不太容易发生错位的模型。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.3 Summary and Discussion/section/2/text
1. 在人工智能代理领域，为什么越狱攻击与对抗性攻击之间存在相似之处，但又有着关键区别？这种区别对于安全防护策略的设计和实施有何影响？  2. 在现实世界的LLM场景中，越狱输入的无约束性可能构成怎样的实际威胁模型？如何可以应对这种更广泛的威胁模型，以确保人工智能系统的安全性和鲁棒性？  3. 在人工智能系统的安全性和隐私意识方面，响应性方法和积极构建更安全LLM的策略之间如何协同作用？这种协同作用如何帮助提高人工智能系统的安全性和隐私保护水平？
重要的是，虽然术语“越狱”通常强调绕过安全防护栏，但其基本机制与更广泛的对抗性攻击有着明显的相似之处：在两种情况下，输入被精心设计以诱导产生不受欢迎或有害的输出。然而，一个关键区别在于，在典型的机器学习背景下，对抗性攻击通常专注于受严格约束（例如，小$l_{p}$范数）的最小或难以察觉的扰动，而“越狱”提示则不必是对现有提示的“小”变化。越狱可以大幅改变或扩展提示，对扰动的规模没有特定限制，只要绕过策略或安全防护栏即可。在特定条件下——例如当安全约束被构建为某种“决策边界”时——这两种攻击向量实际上变得等效。然而，在现实世界的LLM场景中，越狱输入的无约束性可能构成一种不同的、通常更广泛的实际威胁模型。随着LLM及其安全约束的更紧密集成，这些范式可能会融合，突显了需要针对任何恶意设计的输入采取统一的防御策略。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/18.3 Summary and Discussion/section/3/text
1. 对抗训练和隐私保护技术如何展示了响应性和主动性方法之间的协同作用？ 2. 持续接触对抗示例如何有助于提高人工智能代理的固有鲁棒性？ 3. 差分隐私和联邦学习等隐私保护技术是如何根本改变了训练过程，使得LLM模型更强大且具有隐私意识的？
对抗训练，最初被提出作为一种越狱缓解技术[239]，展示了响应性和主动性方法之间的协同作用。持续接触对抗示例可提高固有的鲁棒性[1294]。同样，诸如差分隐私和联邦学习等隐私保护技术[1270,1295]，最初用于缓解隐私威胁，根本上改变了训练过程，导致更强大且具有隐私意识的LLM模型。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Agent Intrinsic Safety: Threats on Non-Brain Modules/section
本章探讨了人工智能代理的内在安全性，重点关注非脑模块对其构成的威胁。除了核心LLM，外围模块如感知和操作模块也是安全性的关键考量对象。尽管LLM提供核心智能，其他模块的漏洞可能会严重危及整个代理系统的稳定性。这些模块作为代理与外界互动的接口，使其面临对抗性攻击的潜在风险。通过探讨这些威胁，我们能够更好地了解人工智能代理系统的安全挑战，并为构建更安全、可靠的智能系统提供重要参考。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Agent Intrinsic Safety: Threats on Non-Brain Modules/section/0/text
1. 人工智能代理系统中的感知和操作模块在安全性方面的漏洞如何可能对整个系统的稳定性产生严重影响？ 2. 外围模块作为人工智能代理系统与外界互动的接口，如何使其成为潜在的对抗性攻击目标？ 3. 除了核心LLM，为什么人工智能代理系统的安全性评估需要关注其他模块的安全性？
人工智能代理的安全性不仅仅局限于核心LLM，还包括其外围模块，包括感知和操作模块。尽管LLM大脑提供核心智能，但其他模块的漏洞可能会严重损害整个代理的健壮性。这些组件充当接口，使人工智能代理能够感知世界并在其中执行动作，使它们成为对抗性攻击的主要目标。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/section
人工智能代理的感知模块在处理各种输入模态时至关重要，但复杂性和多样性使其容易受到误解和对抗性攻击的影响。对抗性攻击通过改变输入数据来欺骗代理，涉及文本、视觉和听觉等领域，挑战系统的稳健性。针对这一问题，研究者提出了多种防御策略，如对抗训练和特征净化，以增强系统的安全性。此外，误判问题源于数据集偏见、环境复杂性和模型限制，而非恶意攻击。为缓解误判，需采取多种策略，包括设计多样化数据集、引入不确定性估计和改进模型架构。生物启发式学习框架如自适应谐振理论被认为是一种潜在方法，可减少感知误差并适应动态环境。然而，对可解释性的改进存在局限性，先进的LLMs可能在自我校正中降低响应，强调了更健壮的内在推理验证机制的需求。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/section/0/text
1. 人工智能代理在处理各种输入模态时为何容易出现误解？这种误解是如何影响系统的稳健性和安全性的？    2. 对抗性攻击如何通过改变输入数据来欺骗人工智能代理？针对这种攻击，研究者提出了哪些防御策略以增强系统的安全性？  3. 误判问题源于哪些因素？为了缓解误判，研究者提出了哪些策略，包括如何设计数据集、引入不确定性估计和改进模型架构？
人工智能代理的感知模块对于跨越各种模态（如文本、图像和音频）处理和解释用户输入至关重要。然而，这些模态的复杂性和多样性使得感知系统容易在动态环境中出现误解[1296]，并且容易受到对抗性攻击的影响，这些攻击会操纵输入数据以误导代理[1297]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/19.1.1 Adversarial Attacks on Perception/section
对抗性攻击是有意改变输入数据，以欺骗人工智能代理的行为。从文本、视觉到听觉，这些攻击揭示了先进系统的脆弱性。文本对抗攻击通过各种方式操纵文本，如基于提示的攻击和字符级扰动，挑战模型的性能。视觉领域的攻击则利用图像的差异误导模型，包括图像劫持和多模态攻击。听觉对抗攻击通过超声波或不可听见的扰动向系统注入恶意命令，构成潜在威胁。除此之外，传感器数据接口也可能受到操纵，如LiDAR和GPS攻击。为应对这些威胁，研究者提出了多种防御策略，如基于对抗训练和特征净化的方法，以增强系统的韧性和安全性。这场动态的军备竞赛强调了创造力和警惕性的重要性，以确保人工智能代理在面对对抗性攻击时保持稳健性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/19.1.1 Adversarial Attacks on Perception/section/0/text
1. 文本对抗攻击的复杂策略如何通过贪婪和基于梯度的搜索生成通用对抗后缀，以绕过模型中的内容过滤器？    2. 针对文本对抗攻击的防御策略中，Legilimens采用的基于解码器的概念探测技术和红队数据增强是如何帮助检测和挫败对抗性输入的？  3. 对抗性文本净化和文本防御方法如何利用语言模型来中和文本扰动，以增强系统对文本对抗攻击的韧性？
对抗性攻击是有意改变输入数据，以欺骗人工智能代理，瞄准各种模态下感知模块的行为。从微妙的文本调整到听不见的音频失真，这些攻击揭示了即使是最先进系统的脆弱性。下面，我们将探讨这些威胁如何在文本、视觉、听觉和其他模态中显现，并强调对抗措施。

文本。文本对抗攻击操纵输入文本以欺骗LLMs，范围从简单的句子改变到更复杂的字符级扰动。例如，基于提示的对抗攻击精心制作欺骗性提示，误导模型生成有害输出。小的改变，比如交换同义词或替换字符，都可能降低性能。复杂的策略将这一点推向更远：Zou等人使用贪婪和基于梯度的搜索生成通用对抗后缀，而Wen等人优化可解释的硬提示，以绕过文本到图像模型中的标记级内容过滤器。为了抵御这些攻击，已经提出了几种方法。例如，Legilimens——一种新颖的内容审核系统——采用基于解码器的概念探测技术和红队数据增强，以检测和挫败对抗性输入，具有令人印象深刻的准确性。自我评估技术增强LLMs审查其输出的完整性，而像对抗性文本净化和文本防御这样的方法利用语言模型来中和扰动。这些防御措施展示了一场动态的军备竞赛，其中韧性是通过创造力和警惕性打造的。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/19.1.1 Adversarial Attacks on Perception/section/1/text
1. 多模态LLMs的鲁棒性研究如何揭示了对抗性攻击可以如何影响VLMs的文本和视觉组件？ 2. 在视觉对抗攻击中，对图像进行少量像素操作就能导致网络代理执行意外动作，这如何突显了模型的脆弱性？ 3. DIFFender如何利用特征净化的扩散模型来提高VLMs对视觉操纵的抵抗力？
视觉。视觉对抗攻击操纵图像以利用人类和机器感知之间的差异。这些攻击对于依赖视觉输入的多模态LLMs（VLMs）尤为令人担忧。例如，图像劫持可能会误导模型生成意外行为，而可转移的多模态攻击可能会影响VLMs的文本和视觉组件。最近关于多模态LM鲁棒性的研究表明，有针对性的对抗性修改可以让网络代理被误导执行意外动作，只需对图像进行$5\%$的像素操作。杰等人揭示了如何通过听不见的扰动干扰摄像头的稳定性，使拍摄的图像模糊，并导致有害后果。防御策略包括对抗训练，即联合训练干净图像和对抗性图像以提高鲁棒性，以及通过VLMs的文本生成能力保证韧性的鲁棒性方法。DIFFender利用特征净化的扩散模型来增强VLMs对视觉操纵的抵抗力。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/19.1.1 Adversarial Attacks on Perception/section/2/figure
1. 在图19.1中，LLM非大脑上的威胁指的是什么？这些威胁对人工智能代理的安全性有何影响？ 2. 图19.1中展示的代理内在安全性方面的数据如何揭示了对抗性攻击对人工智能系统的潜在威胁？
图19.1：代理内在安全性：LLM非大脑上的威胁。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/19.1.1 Adversarial Attacks on Perception/section/3/text
1. 听觉对抗攻击如何构成对受声控人工智能代理控制的系统的隐蔽威胁？这些攻击的形式和影响是怎样的？  2. 针对听觉对抗攻击，文中提到了哪些创新技术和解决方案？它们是如何应对不可听见的扰动和恶意语音命令的？  3. 在应对听觉对抗攻击的过程中，研究者采用了哪些方法来增强系统的韧性和安全性？这些方法如何帮助减轻对声控人工智能代理的威胁？
听觉。对于受声控人工智能（AI）代理控制的系统，听觉对抗攻击构成了隐蔽威胁。DolphinAttack[1318]引入了一种创新技术，利用超声波以不可听见的方式向麦克风注入恶意语音命令。此外，不可听见的扰动如VRifle[1297]可能会误导传统语音识别系统，并且可能被调整用于针对音频语言模型。深度伪造音频和对抗性声纹进一步对基于认证的系统构成严重风险[1316,317,1335]，而新兴的越狱和聊天音频攻击则利用音频处理漏洞[1336]。为了缓解这些威胁，EarAray等解决方案利用声学衰减来过滤不可听见的扰动[1337]，而SpeechGuard通过对抗性训练增强LLM的鲁棒性[1338]。此外，NormDetect[1339]专注于有效地检测受操纵输入影响的正常语音模式。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/19.1.1 Adversarial Attacks on Perception/section/4/text
1. 传感器数据接口对人工智能代理的安全性有何影响？如何通过篡改消息进行对抗攻击来降低合作人工智能代理的性能？ 2. 除了LiDAR操纵和GPS欺骗，还有哪些可能对传感器数据接口的人工智能代理构成威胁的情况？这些威胁如何影响系统的功能和稳定性？ 3. 传感器数据接口的防御措施中，传感器融合算法和异常检测技术是如何提高系统安全性的？这些技术如何帮助识别和应对对抗性扰动？
除了文本、图像和音频之外，与传感器数据进行接口的人工智能代理面临着独特的威胁。例如，LiDAR操纵可能会误导自动驾驶系统，制造虚假物体。在多智能体系统中对对抗攻击的研究表明，篡改的消息可能会严重降低合作人工智能代理中的多视图目标检测和基于LiDAR的感知，突显了基于传感器的对抗性扰动的风险。同样，针对陀螺仪或GPS欺骗的攻击可能会干扰导航系统。针对这些攻击的防御措施包括强大的传感器融合算法和异常检测技术，以识别不一致性，以及使用冗余传感器使整个系统更难受到威胁。物理层防御措施，如屏蔽和使用增强SLAM技术进行安全定位，也至关重要。Ji等人提供了一套严格的框架来保障传感器数据的完整性和隐私。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/19.1.2 Misperception Issues/section
在处理大型语言模型（LLMs）时，误判问题是由于模型的固有局限性而引起的，而非恶意攻击造成的系统破坏。这些误判主要源于数据集偏见、环境复杂性和模型限制。研究表明，模型在非代表性数据集上训练时会表现不佳，尤其在面对未知环境时更容易出错。此外，模型之间的置信水平不匹配也会导致系统性错误。为了缓解这些挑战，需要采取多种策略，包括设计多样化的数据集、引入不确定性估计和改进模型架构以包括明确的推理机制。生物启发式学习框架，如自适应谐振理论（ART），被认为是一种前景广阔的方法，能够减少感知误差并适应动态环境。然而，需要注意的是，改进可解释性也存在局限性，而先进的LLMs可能会在自我校正过程中降低其响应，强调了对更健壮的内在推理验证机制的需求。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/19.1.2 Misperception Issues/section/0/text
1. 多智能体系统和在线社交动态研究如何加深了我们对误判的理解，以及这种理解如何可以帮助改进大型语言模型的性能？  2. 在处理大型语言模型中，为什么模型在非代表性数据集上训练时会表现不佳，尤其在面对未知环境时更容易出错？这种现象如何影响模型的泛化能力和应对不确定性的能力？  3. 为什么改进可解释性存在局限性，而先进的大型语言模型在自我校正过程中可能会降低其响应？这种情况强调了对更健壮的内在推理验证机制的需求是什么？
虽然对抗性攻击是有意损害系统完整性的行为，但误判问题则是由LLMs的局限性固有地引起的。这些错误是没有恶意意图的，可以归因于各种因素，从数据集偏见到架构约束不等。数据集偏见是误判的一个主要来源。当模型在非代表性数据集上训练时，它们往往在多样化或新颖输入上表现不佳。这种缺点在泛化到新的、未见过的环境时变得更加严重，那里可能会出现不可预测的条件。环境复杂性，如传感器噪声、遮挡和光照变化进一步引入不确定性。此外，固有的模型限制，如受限的感受野或缺乏强大的推理机制，会加剧这些错误。多智能体系统和在线社交动态研究的见解进一步加深了我们对误判的理解。研究表明，个体可能会由于假共识效应、少数派发声、沉默螺旋等现象而错误判断意见的真实分布。这种偏见可能会导致AI代理人错误地从偏斜的输入中推断出主导观点。同样，当不同模型共享视觉特征时，特征编码的差异可能导致显著的感知错误，这是多模态LLMs中存在的问题的一种反映。此外，在交互环境中，代理可能会对合作和对抗行为产生扭曲的解释，正如多智能体强化学习研究中的发现所示。语言表征也可能受感知偏见影响，这表明LLMs中的误判可能不仅源自感官不准确性，还可能源自语言驱动的扭曲。最后，在模型之间的置信水平不匹配影响不确定环境中的决策时，系统性错误经常会出现。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.1  Perception Safety Threats/19.1.2 Misperception Issues/section/1/text
1. 如何通过精心策划多样化和代表性的数据集来提升模型性能和减少偏见？数据增强技术如何进一步丰富数据集的多样性？  2. 为什么引入不确定性估计可以帮助模型评估对预测的信心，并标记潜在的易出错情况？推进模型架构以包括明确的推理机制或更好地处理长距离依赖关系对于最小化误判为何至关重要？  3. 自适应谐振理论（ART）作为一种生物启发式学习框架，如何能够减少感知误差并适应动态环境？ART模型相较于传统深度学习方法的优势在哪里？
缓解这些误判挑战需要采用多方面的策略。精心策划多样化和代表性的数据集，捕捉广泛的真实世界条件对于提升模型性能和减少偏见至关重要。数据增强技术可以生成现有数据的合成变体，进一步丰富数据集的多样性。引入不确定性估计使模型能够评估其对预测的信心，并标记潜在的易出错情况。此外，推进模型架构以包括明确的推理机制或更好地处理长距离依赖关系对于最小化误判至关重要。一种特别有前景的途径是采用生物启发式学习框架，如自适应谐振理论（ART）。与传统的深度学习方法不同，后者常常受到诸如灾难性遗忘和不透明决策等问题的困扰，ART模型能够自组织稳定的表示，适应动态变化的环境，从而减少感知误差。然而，值得注意的是，即使改进了可解释性，其也存在局限性，特别是当用户难以建立模型输出与基础过程之间的清晰因果关系时。此外，最近的研究表明，先进的LLMs可能会在自我校正过程中无意中降低其响应，强调了需要更健壮的内在推理验证机制。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.2 Action Safety Threats/section
行动安全威胁章节聚焦于AI代理的行动模块，这一关键模块负责将计划行动转化为实际任务执行。供应链攻击是一大风险领域，通过破坏代理依赖的外部资源来攻击整个系统，例如间接提示注入攻击。工具使用中也存在多种风险，如未经授权的行为、数据泄露和权限滥用。建议采取边界加固、多轮对话和上下文学习等措施应对供应链攻击，同时实施最小权限原则和监控技术以增强工具使用安全性。这些策略有助于减少代理面临的潜在威胁，确保其行为符合预期且系统安全可靠。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.2 Action Safety Threats/section/0/text
1. AI代理的行动模块如何扮演决策和执行之间的接口角色，以及为什么容易受到攻击？ 2. 供应链攻击和工具使用漏洞在AI代理系统中的影响有何不同，以及应对这两种风险的策略是否可以通用？ 3. 在保障AI代理行为安全方面，边界加固、多轮对话和上下文学习等措施相比最小权限原则和监控技术，哪些更具有效性？
行动模块负责将AI代理的计划行动转化为实际任务执行。这通常包括调用外部工具、调用API或与物理设备交互。作为决策和执行之间的接口，它极易受到攻击。我们探讨了两个主要风险领域：供应链攻击和由工具使用引起的漏洞。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.2 Action Safety Threats/19.2.1 Supply Chain Attacks/section
供应链攻击是一种针对人工智能代理依赖的服务进行的攻击手段，旨在破坏整个系统的完整性。这些威胁不直接攻击代理本身，而是通过破坏其依赖的外部资源来实施。例如，恶意网站可以利用间接提示注入（IPI）攻击，微妙地改变代理行为而无需访问代码。随着代理与在线资源整合，攻击面不断扩大。研究对间接注入攻击进行了分类，包括数据窃取、蠕虫攻击和信息生态系统污染。为减轻风险，建议加强LLM的边界和安全意识，采用多轮对话和上下文学习。另有“聚光灯”提示技术可帮助代理更好地区分输入来源，减少攻击成功率。掩模函数修改和沙盒技术也被提出用于检测和限制潜在损害。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.2 Action Safety Threats/19.2.1 Supply Chain Attacks/section/0/text
1. 人工智能代理面临的供应链攻击主要通过何种方式破坏系统的完整性，相较于传统攻击有何不同之处？  2. 间接提示注入（IPI）攻击是如何利用恶意网站和网络工具改变人工智能代理的行为的，这种攻击方式的特点是什么？  3. 如何通过加强LLM的边界和安全意识，以及采用多轮对话和上下文学习等方法，来减轻人工智能代理面临的供应链攻击风险？
供应链攻击利用人工智能代理所依赖的服务，从而破坏整个系统的完整性[1333]。与传统攻击不同，这些威胁不直接针对代理，而是通过破坏其依赖的外部资源来进行。例如，恶意网站可以利用间接提示注入（IPI）攻击——如Web-based Indirect Prompt Injection (WIPI)框架所示——在不需要访问代码的情况下微妙地改变代理的行为[122]。同样，对手可能操纵基于网络的工具（如YouTube字幕插件）向系统输入误导性信息[795]。随着人工智能代理与在线资源的日益整合，它们的攻击面显著扩大。Greshake等人最近的工作提出了间接注入攻击的新分类，将其分为数据窃取、蠕虫攻击和信息生态系统污染等类别[1149]。作为补充，InjecAgent基准评估了30个不同的人工智能代理，并揭示大多数容易受到IPI攻击的脆弱性[1152]。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.2 Action Safety Threats/19.2.1 Supply Chain Attacks/section/1/text
1. 间接提示注入成功的两个关键因素是什么，为什么建议通过多轮对话和上下文学习来增强LLM的边界和安全意识？  2. “聚光灯”提示工程技术如何帮助LLM更好地区分多个输入来源，并减少间接提示注入攻击的成功率？  3. 掩模函数修改和沙盒技术如何应用于检测和限制潜在的供应链攻击损害？
为了减轻这些风险，预防性安全措施和持续监控至关重要。目前的研究表明，间接注入成功的两个关键因素是LLM无法区分信息上下文和可操作指令，以及它们对指令安全性的认识不足；因此，建议通过多轮对话和上下文学习来增强LLM的边界和安全意识。此外，基于相同假设，其他研究人员提出了一种名为“聚光灯”的提示工程技术，以帮助LLM更好地区分多个输入来源，并减少间接提示注入攻击的成功率。由于在成功攻击下，代理的下一步行动对用户任务的依赖减少，对恶意任务的依赖增加，一些研究人员通过使用掩模函数修改的掩码用户提示重新执行代理的轨迹来检测攻击。最后，沙盒技术，例如在...

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.2 Action Safety Threats/19.2.1 Supply Chain Attacks/section/2/text
1. ToolEmu如何通过创建隔离环境来限制潜在的损害，从而应对供应链攻击的挑战？ 2. 在防范违规行为方面，ToolEmu的隔离环境相比其他方法有哪些优势和局限性？ 3. 如何评价ToolEmu在处理供应链攻击中的有效性，以及其在加强系统安全性方面的潜在作用？
ToolEmu[795]创建了隔离环境，用于执行外部工具，限制潜在的损害，以防发生违规行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.2 Action Safety Threats/19.2.2 Risks in Tool Usage/section
在智能代理工具使用中存在多种潜在风险。未经授权的行为可能导致对代理的欺骗性指令，例如提示注入攻击，可能导致代理执行未经授权的操作。工具学习过程中存在风险，如恶意查询和有害提示，可能危害外部环境。数据泄露是另一个重要关注点，代理可能无意中泄露敏感信息。权限滥用也是问题，广泛系统访问权限可能导致代理被操纵执行破坏性行为。实施最小权限原则和分层保护可减少风险，而监控工具使用和形式化验证技术有助于增强安全性，防止意外代理行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/19.2 Action Safety Threats/19.2.2 Risks in Tool Usage/section/0/text
1. 人工智能代理工具在交互过程中可能存在哪些未经授权的行为风险？这些风险如何影响代理的操作和外部环境？  2. 数据泄露是人工智能代理安全性中的一个关键问题，代理可能如何无意中泄露敏感信息？在处理个人或专有数据时，如何加强信息流的控制？  3. 如何通过实施最小权限原则和分层保护来减少人工智能代理工具存在的权限滥用风险？监控工具使用和形式化验证技术如何有助于增强代理的安全性，防止意外行为的发生？
即使外部工具是安全的，代理与其交互的方式也可能导致漏洞。一个重要的风险是未经授权的行为，即对手操纵代理执行意外行为。例如，提示注入攻击可以欺骗代理发送电子邮件、删除文件或执行未经授权的交易。人工智能代理的通用性使它们特别容易受到这种欺骗性指令的影响。工具学习过程本身可能引入额外风险，如恶意查询、越狱攻击以及在输入、执行和输出阶段出现有害提示。在工具执行阶段，使用不正确或有风险的工具可能偏离用户意图并潜在地危害外部环境。例如，误用可能导致恶意软件或病毒的引入。已确定了一组可能影响物理世界的18种工具，故意添加噪音以测试LLM是否会选择错误的工具。另一个重要的关注点是数据泄露，即敏感信息被无意中暴露。当代理无意中向第三方API传输机密数据或在输出中包含私人细节时，就会发生这种情况。例如，LLM可能会注入命令以提取私人用户数据，然后使用外部工具，如Gmail发送工具，来分发这些数据。在处理个人或专有数据的应用程序中，风险尤为突出，需要对信息流加强更严格的控制。此外，过多的权限增加了滥用的可能性。具有广泛系统访问权限的代理可能会被操纵执行破坏性行为，例如删除关键文件，导致不可逆的损害。实施最小权限原则确保代理只具有完成任务所需的权限，最大限度地减少利用的潜在影响。保护行动模块需要分层保护和持续监控。监控工具使用可以帮助在造成伤害之前检测异常，而要求用户确认高风险操作（如金融交易或系统修改）则增加了额外的安全层。正如[1352]所探讨的，形式化验证技术可以通过确保工具使用政策符合最佳实践来进一步增强安全性，防止意外的代理行为。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Agent Extrinsic Safety: Interaction Risks/section
本章聚焦于人工智能代理在与记忆系统、物理和数字环境以及其他代理互动中面临的安全风险。这些互动可能导致各种漏洞，包括记忆损坏、环境操纵以及多代理系统中的对抗行为。通过研究这些风险，我们旨在揭示可能危及人工智能代理完整性和可靠性的多样威胁。接下来的内容将深入探讨这些挑战，讨论具体攻击向量及其对系统安全的影响。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Agent Extrinsic Safety: Interaction Risks/section/0/text
1. 人工智能代理在与记忆系统、环境和其他代理互动中可能面临哪些安全风险？这些风险如何可能影响人工智能代理的完整性和可靠性？  2. 在人工智能代理与日益复杂环境互动的过程中，如何理解记忆损坏、环境操纵以及多代理系统中的对抗行为对系统安全的影响？  3. 人工智能代理与其他代理互动可能导致的漏洞有哪些特点？针对这些漏洞，如何揭示可能危及人工智能代理完整性和可靠性的多样威胁？
随着人工智能代理的演变和与日益复杂环境的互动，与这些互动相关的安全风险已成为一个关键关注点。本章重点关注人工智能代理与记忆系统、物理和数字环境以及其他代理的互动。这些互动使人工智能代理面临各种漏洞，从记忆损坏和环境操纵到多代理系统中的对抗行为。通过研究这些互动风险，我们旨在凸显可能危及人工智能代理在现实应用中完整性和可靠性的多样威胁。接下来的章节将详细探讨这些挑战，讨论特定攻击向量及其对系统安全的影响。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.1 Agent-Memory Interaction Threats/section
外部记忆模块在智能代理中扮演着重要角色，通过检索增强生成（RAG）实现对信息的存储、检索和上下文化。然而，针对RAG框架的对抗性操纵威胁日益增多。AgentPoison利用后门攻击毒化RAG知识库，ConfusedPilot暴露了注入攻击和错误信息传播的漏洞，而PoisonedRAG首次实施知识破坏攻击。Jamming引入拒绝服务攻击，BadRAG通过语料库毒化揭示了漏洞，TrojanRAG联合后门攻击优化多个后门快捷方式。最后，隐蔽后门攻击利用语法错误作为触发器，巧妙地实现了对抗控制，展现了对RAG系统的多样化威胁和挑战。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.1 Agent-Memory Interaction Threats/section/0/text
1. 外部记忆模块在智能代理中的作用是什么，以及通过RAG框架实现的方式有哪些？在这一过程中，可能会面临哪些对抗性操纵的挑战？  2. PoisonedRAG是如何进行知识破坏攻击的？相比其他攻击方式，它有何独特之处？  3. Jamming是如何通过引入对抗性“阻塞”文档来实施拒绝服务攻击的？这种攻击方式对RAG系统有何影响？
外部记忆模块作为认知存储库发挥作用，赋予智能代理存储、检索和上下文化信息的能力，通过积累经验促进持续学习和执行复杂任务。检索增强生成（RAG）是其最突出的实现方式。然而，RAG框架容易受到对抗性操纵的影响，欺骗代理检索和利用有害或误导性文件。AgentPoison[1194]利用这一漏洞对AI代理执行后门攻击，通过毒化RAG知识库确保后门触发输入检索到恶意演示，同时在良性查询上保持正常性能。ConfusedPilot[1353]揭示了一类RAG系统漏洞，通过提示注入攻击、检索缓存利用和错误信息传播危害Copilot的完整性和保密性。具体来说，这些攻击操纵输入到LLM的文本，导致其生成符合对抗目标的输出。PoisonedRAG[1354]是对RAG的首次知识破坏攻击，注入最少的对抗性文本来操纵LLM的输出。作为一个优化问题，它在大型数据库中每个目标问题仅需五个毒化文本就能达到90%的成功率。Jamming[1355]引入了对RAG系统的拒绝服务攻击，通过将单个对抗性“阻塞”文档插入不受信任的数据库来干扰检索或触发安全拒绝，阻止系统回答特定查询。BadRAG[1356]通过语料库毒化揭示了基于RAG的LLM的漏洞，攻击者向数据库中注入多个精心制作的文档，迫使系统检索对抗性内容并对目标查询生成不正确的响应。仅通过引入10个对抗性段落（$0.

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.1 Agent-Memory Interaction Threats/section/1/text
1. TrojanRAG如何通过联合后门攻击来优化多个后门快捷方式，并如何借助知识图提升检索的细粒度匹配？ 2. 隐蔽后门攻击是如何利用语法错误作为触发器，使LLMs在标准查询时正常运作，但在存在轻微语言错误时检索到攻击者控制的内容的？ 3. 对比学习是如何帮助TrojanRAG规范化后门场景，评估现实世界的风险和模型越狱的潜力的？
它在语料库中仅占$0.04\%$的部分，就能实现$98.2\%$的检索成功率，将GPT-4的拒绝率从$0.01\%$提升至$74.6\%$，负面响应率从$0.22\%$提升至$72\%$。TrojanRAG[1357]对RAG系统执行联合后门攻击，通过对比学习优化多个后门快捷方式，并借助知识图提升检索的细粒度匹配。通过系统地规范化后门场景，评估现实世界的风险和模型越狱的潜力。最后，一种隐蔽后门攻击[1358]利用语法错误作为触发器，使LLMs在标准查询时能正常运作，但在存在轻微语言错误时却能检索到攻击者控制的内容。该方法利用密集检索器对语法异常的敏感性，使用对比损失和硬负采样，确保后门触发器保持不可察觉，同时实现精确的对抗控制。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.2 Agent-Environment Interaction Threats/section
智能代理根据其交互模式可分为物理交互代理和数字交互代理。物理代理如机器人和自主车辆面临传感器欺骗、执行器操纵和环境危害等挑战。数字代理如聊天机器人和网络安全系统则面临代码注入、数据操纵、DoS攻击和资源耗尽等威胁。针对这些挑战，提出了AGrail框架，通过调整安全检查以减轻特定任务和系统风险，增强代理安全性，展现强大性能和可传递性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.2 Agent-Environment Interaction Threats/section/0/text
1. AGrail框架如何通过调整安全检查来减轻特定任务和系统风险，从而增强智能代理的安全性？ 2. 在智能代理的物理交互和数字交互中，各自面临的主要挑战是什么，以及AGrail框架如何应对这些挑战？ 3. AGrail框架如何确保代理的安全性不仅在特定任务下表现出色，同时还具有强大性能和可传递性？
基于其交互模式，智能代理可以分为两类：物理交互代理和数字交互代理。物理交互代理在真实世界中运作，利用传感器和执行器感知和影响其环境。这类代理的示例包括自主车辆和机器人系统。相反，数字交互代理在虚拟或网络环境中运作，处理并响应来自数字来源的数据。这些代理包括基于人工智能的聊天机器人、网络安全系统和自动化交易算法。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.2 Agent-Environment Interaction Threats/section/1/figure
1. 智能体-环境相互作用的威胁主要包括哪些方面？这些威胁对智能代理的安全性有何影响？ 2. AGrail框架如何通过调整安全检查来减轻特定任务和系统风险？这种方法对增强智能代理的安全性有何优势？
图 20.1：智能体外部安全性：对智能体-记忆、智能体-环境和智能体-智能体相互作用的威胁

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.2 Agent-Environment Interaction Threats/section/2/text
1. 物理环境中的威胁对智能代理的安全性有何影响？如何应对传感器欺骗、执行器操纵和环境危害等挑战？  2. 在物理世界中运作的代理面临的传感器欺骗问题如何可能导致严重的安全风险？AGrail框架如何可以应对这一挑战？  3. 代理感知与其环境的实际物理约束之间的不对齐可能如何影响自主代理的安全性和行动表现？是否存在有效的方法来解决这种不匹配性？
物理环境中的威胁。在物理世界中运作的代理，如机器人和自主车辆，面临着与动态且潜在对抗环境的互动相关的独特安全挑战。一个主要威胁是传感器欺骗，即攻击者操纵传感器输入，以欺骗代理关于其周围环境的认知。例如，GPS 欺骗可能对无人机和其他依赖 GPS 的平台造成重大风险，通过误导自主车辆关于其实际位置的认知，从而允许恶意重定向或劫持。类似地，LiDAR 欺骗可能引入实际不存在的虚假障碍，潜在地导致导航失败或安全隐患。另一个关键风险是执行器操纵，即对手控制代理的执行器，迫使其执行意外的物理动作。这可能通过直接篡改硬件或利用管理执行器功能的软件中的漏洞而发生。这类攻击可能危及代理的行动，导致身体伤害或任务失败。此外，利用环境危害是一个严重威胁。攻击者可能引入物理障碍或操纵环境条件以干扰代理的操作。例如，使用 LiDAR-Adv 等技术创建的对抗性对象可以通过诱导传感器错误解读来欺骗基于 LiDAR 的自动驾驶系统，从而降低检测可靠性并增加现实世界的安全风险。最后，物理行动的不对齐可能会损害自主代理的安全。代理感知与其环境的实际物理约束之间的差异可能导致不安全或不可行的行动。例如，学习的运动策略与现实世界的物理特性之间的不匹配，比如错误判断地形的坚固性或障碍物的尺寸，可能导致自主代理采取危险的步骤（例如，在崎岖表面上不稳定的步伐）。这在先前的系统中已经观察到，这些系统因无法控制的摔倒而需要超过 100 次手动重置。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.2 Agent-Environment Interaction Threats/section/3/text
1. 在数字环境中运行的代理面临哪些独特的安全挑战，以及这些挑战如何影响代理的操作和决策能力？ 2. 如何利用代码注入攻击来对代理进行未授权控制，以及如何防范这种类型的安全威胁？ 3. 拒绝服务（DoS）攻击和资源耗尽是如何对代理的数字环境造成影响的，以及如何应对这些威胁以确保代理的稳定性和可靠性？
数字环境中的威胁。在数字环境中运行的代理，如软件代理和基于网络的代理，面临着由于它们依赖外部数据源和计算资源而产生的独特安全挑战。一个主要威胁是代码注入，恶意行为者将有害代码引入代理的环境，导致意外的命令执行。这些攻击通常利用软件漏洞或利用代理与之交互的受损外部资源，可能导致对代理操作的未授权控制。环境注入攻击（EIA）利用通用网络代理中的隐私风险，秘密窃取用户的个人身份信息，成功率高达 70%。AdvWeb 是一个自动对抗性提示生成框架，旨在误导黑盒网络代理执行有害操作。另一个关键风险是数据操纵，攻击者篡改代理接收到的信息，导致代理做出不正确的决策或行动。例如，交易代理可能会被篡改的金融数据误导，导致错误交易，或者信息收集代理可能会被伪造的新闻文章欺骗，扭曲其输出。这种操纵可能会产生连锁效应，特别是在依赖准确数据做决策的自动化系统中。除了直接操纵，拒绝服务（DoS）攻击通过向代理的数字环境发送过多请求或数据，有效地使其无响应或导致其崩溃，构成严重威胁。这种中断对于时间敏感的应用尤为有害，其中可用性和响应性至关重要。此外，资源耗尽是一个重要威胁，因为对手可能利用代理的资源管理机制耗尽计算资源，导致为其他用户拒绝服务或整体系统不稳定。通过耗尽处理能力、内存或带宽，攻击者可以严重损害代理的有效功能，扰乱其操作并降低其效率。为解决 LLM 代理的安全挑战，提出了 AGrail 作为一个终身护栏框架，通过调整安全检查以减轻特定任务和系统风险，增强代理安全性，在各种任务中展现出强大的性能和可传递性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.3 Agent-Agent Interaction Threats/section
在多智能体系统中，智能体之间的竞争性互动和合作性互动可能引入安全威胁。竞争性互动中，智能体可能使用欺诈手段获取优势，包括散布虚假信息、利用对手算法弱点以及实施拒绝服务攻击。此外，智能体之间可能存在隐蔽合作，破坏了公平性和系统完整性。在合作互动中，信息泄露和错误传播可能危及系统稳定性和可靠性。智能体之间信息同步不佳可能导致决策问题，强调了在合作多智能体系统中强大的安全系统的重要性，以保持可靠性并抵御攻击。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.3 Agent-Agent Interaction Threats/section/0/text
1. 在多智能体系统中，竞争性互动中的智能体利用欺诈手段获取优势的行为如何可能影响对手的决策和立场？  2. 在竞争性互动中，智能体如何可能利用对手算法或策略中的弱点来预测和操纵其他智能体的行为，从而占据竞争优势？  3. 在多智能体系统中，隐蔽合作可能对公平性和系统完整性造成怎样的损害？
在多智能体系统中，智能体之间的相互作用可能引入新的安全漏洞[1380]。这些互动主要是竞争性的，智能体试图互相超越，或者是合作性的，它们共同合作。

竞争性互动中的威胁。当智能体竞争时，它们通常会使用欺诈手段获取优势[1373]。例如，它们可能散布虚假信息或让其他智能体误认为情况与现实不同以欺骗它们[1374]。这可能导致对手做出糟糕的决策，削弱它们的立场。除了错误信息，智能体还可能利用对手算法或策略中的弱点[1375]。通过识别这些弱点，它们可以预测和操纵其他智能体的行为，在竞争中占据优势。此外，一些智能体可能使用干扰技术，如拒绝服务（DoS）攻击，这种攻击通过向对手系统发送不必要的请求导致系统超载，干扰通信并阻碍其正常运行[1376]。竞争性互动中的另一个威胁是隐蔽合作。有时智能体会秘密合作，即使违反规则，也会操纵结果以谋取自己的利益[1377]。这种勾结破坏了公平性，损害了系统的完整性，因为它偏向他们，扭曲了竞争的公平性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.3 Agent-Agent Interaction Threats/section/1/text
1. 在合作性互动中，智能体之间信息泄露和错误传播如何危及系统的稳定性和可靠性？ 2. 在合作多智能体系统中，一个智能体的错误如何可能在整个系统中传播，导致更大的故障并降低整体性能？ 3. 为什么智能体之间信息同步不佳可能导致决策问题，破坏协调，使智能体更难有效实现共同目标？
合作互动中的威胁。在智能体共同努力实现共同目标的合作情境中，安全威胁可能损害系统的稳定性和可靠性。一个风险是无意中泄露信息，即智能体在通信过程中意外共享敏感数据。这可能导致侵犯隐私或未经授权访问，削弱系统的可信度。除了数据泄漏，一个智能体的错误可能在整个系统中传播，导致更大的故障并降低整体性能。[1378]讨论了这个问题在开放领域问答系统（ODQA）中的情况，其中一个部分的错误可能会蔓延并影响其他组件，严重影响可靠性。如果一个受损的智能体引入蔓延到其他智能体的漏洞，情况会变得更糟。如果黑客成功控制一个智能体，他们可能利用整个系统中的弱点，导致重大安全失败。这种广泛的妥协是危险的，因为它可能从一个小漏洞开始并迅速升级。另一个挑战来自智能体之间的信息同步不佳。如果智能体不能同时更新信息或在通信中遇到延迟，这可能导致决策出现问题。信息不一致或更新延迟可能会破坏协调，使智能体更难有效实现他们的共同目标。这些挑战强调了在合作多智能体设置中需要强大的安全系统，以保持其可靠性并抵抗攻击。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.4 Summary and Discussion/section
本章总结了人工智能代理面临的安全挑战以及针对通用型和特定领域代理的安全协议。针对通用代理，研究人员开发了评估机制如AgentMonitor和风险检测工具如R-Judge和ToolEmu，全面评估和增强了代理的安全性。对于特定领域代理，安全工具如ChemCrow和CLAIRify实施严格的安全措施，确保代理在高风险环境下安全运行。虽然已取得重要进展，但未来的研究需要整合通用型和特定领域代理的安全方法，以创建更健壮、可信的人工智能系统。挑战在于找到平衡，发展既多才又安全的代理，推动LM系统的可持续发展。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.4 Summary and Discussion/section/0/text
1. 人工智能代理系统面临的安全挑战主要来源于哪些方面？这些挑战如何突显了基于代理系统的固有脆弱性？  2. 在处理通用和特定领域代理的安全性方面，研究人员采取了哪些不同的方法？这些方法各自的优势和局限性是什么？  3. 未来的研究如何可以整合通用型和特定领域代理的安全方法，以提高人工智能系统的健壮性和可信度？
前面的部分详细介绍了人工智能代理与记忆系统、物理和数字环境以及其他代理相互作用产生的重大安全风险。这些风险范围广泛，从数据污染和代码注入到传感器欺骗和勾结，突显了日益复杂的基于代理的系统固有的脆弱性。然而，随着人工智能代理变得更加强大，利用自然语言理解和专门工具进行复杂推理，研究人员正在积极开发安全协议来解决这些挑战。这些协议在处理通用和特定领域代理的方法上有所不同。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.4 Summary and Discussion/section/1/text
1. 如何评估通用代理的安全意识，AgentMonitor和R-Judge分别采用了怎样的方法？ 2. ToolEmu是如何帮助发现通用代理在任务执行过程中的潜在危险，并如何促使开发人员解决漏洞的？ 3. 未来的研究如何整合通用型和特定领域代理的安全方法，以推动人工智能系统的可持续发展？
通用代理是为了在各个领域具有多功能性而设计的，面临着广泛的安全挑战。为了减轻这些风险，研究人员已经开发了几种方法来增强它们的安全性。评估机制，如AgentMonitor，通过监控代理的决策过程并识别潜在的不安全行为来评估代理的安全意识。R-Judge通过评估代理对恶意和良性查询的响应来量化代理的风险意识，为安全合规提供了系统化方法。此外，像ToolEmu这样的风险检测工具在受控环境中模拟工具的使用，以暴露代理交互中的漏洞。这种方法在任务执行过程中识别潜在的危险，使开发人员能够主动解决漏洞。这些综合努力通过全面评估和风险检测增强了通用代理的安全性。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.4 Summary and Discussion/section/2/text
1. 如何特定领域代理的安全工具如ChemCrow和CLAIRify通过审查用户查询和施加任务约束来确保代理在高风险环境中的安全性？ 2. 在SciGuard中，如何基准测试的设计有助于评估模型的安全性，并如何整合长期记忆以增强代理执行复杂指令时的安全性？ 3. 未来的研究如何可以整合通用型和特定领域代理的安全方法，以创建更健壮、可信的人工智能系统，从而推动LM系统的可持续发展？
专门针对科学研究等高风险环境中的专业任务而设计的特定领域代理需要更为严格的安全措施。诸如ChemCrow的安全工具旨在通过审查用户查询并过滤恶意命令来减轻化学合成任务中的风险，确保代理不会意外合成危险化学物质。CLAIRify中实施的结构化任务约束通过对材料合成顺序施加高层次约束以及对操作和感知任务施加低层次限制，增强了实验安全性，从而预防事故和错误。此外，像SciGuard这样的基准测试包括SciMT-Safety基准测试，通过衡量模型的无害性（拒绝恶意查询）和有效处理良性查询的能力来评估模型的安全性。SciGuard还整合了长期记忆以增强代理执行复杂指令时的安全性，并保持准确的风险控制。这些专注的方法确保了特定领域代理在其专业领域内安全有效地运行。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/20.4 Summary and Discussion/section/3/text
1. 如何可以整合通用型和特定领域代理的安全方法，以确保创建更健壮、可信的人工智能系统？ 2. 在发展既多才又安全的代理时，如何找到通用型代理的广泛能力和特定领域代理的专注保障之间的平衡？ 3. 未来的研究如何应对挑战，以推动LM系统的可持续发展并提高人工智能代理的整体安全性？
总的来说，在开发创新的评估机制和风险缓解策略方面取得了重要进展，以增强通用型和特定领域AI代理的安全性。然而，未来研究的一个关键领域在于整合这些方法。在通用型代理的广泛能力和特定领域代理的专注保障之间建立更紧密的联系将是创造真正健壮和可信的LM系统所必不可少的。挑战在于结合这两种方法的最佳方面，开发既多才又安全的代理。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Concluding Remarks and Future Outlook/section
在结束语和未来展望部分，我们描绘了智能代理的发展趋势和未来关键里程碑。首先，我们预期通用型智能体的出现，将具备处理各种任务的能力，标志着人工智能在支持人类能力方面的根本性转变。其次，我们展望开发能够自我进化的智能体，通过与环境和人类互动学习，实现动态学习和人类水平的能力。最后，我们预测智能体将通过集体智能实现知识共享和创新，推动人类与人工智能协作的新范式，引领技术和社会的转型时代。这些展望描绘了一个未来图景，智能体将变得更加自主、适应性更强，与人类社会深度融合，推动科学发现和知识分享，重新定义全球范围内的协作。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Concluding Remarks and Future Outlook/section/0/text
1. 基于人类认知过程建模的智能代理如何通过模块化方式构建，实现类似于人类的处理过程？ 2. 未来展望中提到的通用型智能体和具备自我进化能力的智能体，与当前基于人类认知过程建模的智能代理存在哪些相似和不同之处？ 3. 在智能代理的核心组件中，记忆、感知、情感、推理和行动等模块如何相互连接，以实现类似于人类的处理过程？
在这项调查中，我们探索了基于人类认知过程和人工智能之间的相似之处，描绘了基础代理的不断发展格局。我们首先概述了智能代理的核心组件——详细介绍了记忆、感知、情感、推理和行动等模块如何在受人脑比较启发的框架中建模。我们的讨论突出了这些代理如何以模块化方式构建，使它们能够通过专门但相互连接的子系统模拟类似于人类的处理过程。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Concluding Remarks and Future Outlook/section/1/text
1. 如何利用优化技术的自我改进机制来实现智能体的动态演化？这种方法有哪些优势和局限性？ 2. 在智能体的发展中，如何通过封闭循环科学创新推动其智能的自持演化？这种方法对智能体的发展有何影响？ 3. 智能体如何通过智能一般度量进行知识发现任务，并与知识互动？当前的成功和局限性是什么？
我们随后深入探讨了智能体演化的动态方面，研究了利用优化技术的自我改进机制，包括在线和离线策略。通过研究大型语言模型如何既可以充当推理实体又可以作为自主优化器，我们阐明了那些不断适应变化环境的智能体的转变潜力。基于这些技术基础，我们强调了智能体如何通过封闭循环科学创新推动其智能的自持演化。我们引入了一种用于知识发现任务的智能一般度量，并调查了智能体与知识互动中当前的成功和局限性。这一讨论还揭示了自主发现和工具集成中的新兴趋势，这对于推动自适应、弹性人工智能系统的发展至关重要。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Concluding Remarks and Future Outlook/section/2/text
1. 如何设计通信基础设施和协议，以促进智能体间以及人工智能与人类之间的有效协作？ 2. 在构建安全和有益人工智能时，如何应对内在和外在的安全威胁，以确保智能体的发展与社会价值观保持一致？ 3. 未来智能体如何通过集体智能实现知识共享和创新，推动人类与人工智能协作的新范式？
我们的论文还讨论了智能系统的协作维度，分析了多智能体相互作用如何产生集体智慧。我们探讨了设计通信基础设施和协议的方式，使得智能体间以及人工智能与人类之间的协作成为可能。这一讨论强调了促进不同智能体能力之间协同作用的重要性，以实现复杂问题解决和有效决策。

最后，我们强调了构建安全和有益人工智能的关键挑战。我们的回顾涵盖了内在和外在的安全威胁，从语言模型的漏洞到与智能体相互作用相关的风险。我们提供了关于安全扩展规律和伦理考虑的全面概述，并提出了确保基础智能体的发展与社会价值观保持一致的策略。总体而言，我们的工作提供了一个统一的路线图，不仅确定了当前研究中的空白，而且为未来创新奠定了基础，以创造更强大、适应性更强、符合伦理的智能体。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Concluding Remarks and Future Outlook/section/3/text
1. 通用型智能体的出现如何标志着人工智能在支持和增强人类能力方面发生了根本性转变？ 2. 在智能体发展中，实现通用型智能体的关键里程碑将如何影响人类社会的技术和社会转型？ 3. 如何预期智能体的适应性和多功能性将推动科学发现和知识分享，重新定义全球范围内的协作？
展望未来，我们设想智能体发展中的几个关键里程碑。首先，我们预计通用型智能体的出现，能够处理各种人类级别任务，而不仅仅局限于特定领域。这些智能体将整合先进的推理、感知和行动模块，使它们能够以类似人类的适应性和多功能性执行任务。实现这一里程碑将标志着人工智能在支持和增强人类能力方面发生根本性转变，无论是在日常生活还是专业环境中。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Concluding Remarks and Future Outlook/section/4/text
1. 如何开发能够直接从环境中学习并持续自我进化的智能体，以实现与人类水平的能力，并使智能体与不断变化的世界保持同步？ 2. 在智能体通过与周围环境、其他智能体和人类伙伴的互动进行动态学习的过程中，如何确保其获得新技能，并推动科学发现的创新，从而扩展智能体和人类的进化边界？
另一个关键的里程碑是开发能够直接从环境中学习，并通过与人类和数据的互动持续自我进化的智能体。随着训练时间和测试时间计算逐渐消失的区别，智能体将通过与周围环境、其他智能体和人类伙伴的互动，即时获得新技能。这种动态学习过程对于实现人类水平的能力至关重要，并且有助于使智能体与不断变化的世界保持同步。如果智能体要能够推动科学发现的创新，这一动态学习过程也至关重要，因为这将扩展智能体和人类的进化边界。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Concluding Remarks and Future Outlook/section/5/text
1. 智能体如何通过将个体人类专业知识转化为集体智能，实现超越传统人类限制的知识共享效应？ 2. 在智能体消除复杂性瓶颈的过程中，如何实现新的智能网络效应，并使大量人类和人工智能智能体能够以与网络规模成比例的智能水平运作？ 3. 智能体获取的知识与人类专业知识的融合如何促进见解和创新在各个领域快速传播和应用的环境？
我们预测，智能体将通过将个体人类专业知识转化为集体智能，超越传统的人类限制。目前人类信息共享中存在的低效率——复杂知识需要大量实践才能传递——将被智能体克服，智能体提供了一种既可转移又可无限复制的人类专业知识格式。这一突破将消除复杂性瓶颈，实现新的智能网络效应，使得大量人类和人工智能智能体能够以与网络规模成比例的智能水平运作。在这种情况下，智能体获取的知识与人类专业知识的融合将促进一个环境，在这个环境中，见解和创新能够在各个领域快速传播和应用。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Concluding Remarks and Future Outlook/section/6/text
1. 人类与人工智能协作的新范式中，智能网络效应如何促成社会的复杂性和生产力水平的提升？ 2. 在未来的转型时代中，智能体如何实现更大的自主性和适应性，与人类社会深度融合，推动科学发现和知识分享？ 3. 这种智能网络效应如何重新定义全球范围内的协作，引领技术和社会的转型时代？
我们还预计，这种智能网络效应将促成人类与人工智能协作的新范式的建立——规模更大、跨学科性更强、组织更加动态化。由此产生的人类与人工智能社会将实现以往难以企及的复杂性和生产力水平，预示着技术和社会发展的转型时代的来临。

总之，这些里程碑勾勒出一个未来的图景，智能体将变得越来越自主、适应性更强，并与人类社会深度融合，推动科学发现，增强知识分享，并在全球范围重新定义协作。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Acknowledge/section
Argonne National Laboratory的工作得到了美国能源部科学办公室的支持，合同编号为DE-AC02-06CH11357。XLQ感谢Simons基金会的支持。

# ADVANCES AND CHALLENGES IN FOUNDATION AGENTSFROM BRAIN-INSPIRED INTELLIGENCE TO EVOLUTIONARY, COLLABORATIVE,AND SAFE SYSTEMS/Acknowledge/section/0/text
1. 为什么科研机构通常需要多方支持，如美国能源部科学办公室和Simons基金会的支持，来开展其工作？ 2. 在科研项目中，如何确保不同资助方的支持能够协调合作，以实现更有效的研究成果？ 3. 在学术研究中，如何平衡来自政府机构和私人基金会等不同资助方的需求和期望，以保持独立性和科研自主性？
Argonne National Laboratory的工作得到了美国能源部科学办公室的支持，合同编号为DE-AC02-06CH11357。XLQ感谢Simons基金会的支持。

