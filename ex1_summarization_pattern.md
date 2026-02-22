1. ## Weak prompt
"summarize this text"
### first input from Likeji's blog on "Stock brokerage"
"Margin settings also shape behaviour in subtle ways. They determine how much capital is locked to hold a trade, how quickly available funds shrink during drawdowns, and how close a trader can get to a margin call when markets move fast. In a country where many traders balance jobs, data costs, and tight schedules, these settings influence not only what trades are taken, but also how confidently traders hold them through volatility.

Many traders only realise this after a few hard lessons, when the broker leverage and margin rules start affecting trade outcomes more than the entry itself. A good setup can still fail if the margin requirement forces early closure or if the leverage encourages oversizing. Why does that matter? Because the trader is no longer trading only the market, they are trading the limits and flexibility of their own account."

### AI's output
"Margin settings strongly affect trading behavior by controlling how much capital is tied up, how fast funds decline during losses, and how close traders get to margin calls. Many traders realize too late that leverage and margin rules can influence outcomes more than trade entries, forcing early exits or encouraging oversizing. Ultimately, traders are not just trading the market, but also the constraints of their own accounts."

### second prompt input from (NVIDIA tech blog)
""summarize this text"

Large language models (LLMs) and multimodal reasoning systems are rapidly expanding beyond the data center. Automotive and robotics developers increasingly want to run conversational AI agents, multimodal perception, and high-level planning directly on the vehicle or robot – where latency, reliability, and the ability to operate offline matter most.

While many existing LLM and vision language model (VLM) inference frameworks focus on data center needs such as managing large volumes of concurrent user requests and maximizing throughput across them, embedded inference requires a dedicated, tailored solution."

## AI's output
"LLMs and multimodal AI systems are increasingly being deployed directly on vehicles and robots to meet requirements like low latency, reliability, and offline operation. However, most current inference frameworks are designed for data centers and high-throughput workloads, making them unsuitable for embedded environments that need specialized, purpose-built solutions."

2. ## Refined prompt
"Summarize the following text in 3 bullet points, focusing on the main arguments and ignoring examples, links and references." 

### First input prompt on technical blog from NVIDIA
"Summarize the following text in 3 bullet points, focusing on the main arguments and ignoring examples, links and references.
The benefits of quantization
Model quantization makes it possible to deploy increasingly complex deep learning models in resource-constrained environments without sacrificing significant model accuracy. As AI models—especially generative AI models—grow in size and computational demands, quantization addresses challenges such as memory usage, inference speed, and energy consumption by reducing the precision of model parameters (weights and/or activations), e.g., from FP32 precision to FP8 precision. This reduction decreases the model’s size and computational requirements, enabling faster computation during inference and lower power consumption compared to the original model. However, quantization can lead to some accuracy degradation compared to the original model. Finding the right tradeoff between model accuracy and efficiency depends heavily on the specific use case."


## AI's output
* Quantization enables deployment of large and complex AI models in resource-constrained environments by reducing parameter precision.
* It improves efficiency by lowering memory usage, speeding up inference, and reducing energy consumption.
* Quantization may reduce accuracy, requiring a careful tradeoff between performance and efficiency based on the use case.

### Second input prompt on nature
Summarize the following text in 3 bullet points, focusing on the main arguments and ignoring examples, links and references.
I believe these negative aspects of nature make the positives even more wondrous. For each example of sad nature experiences I can think of at least two happy ones. It can be very challenging to refrain from interfering with natures process when we sense it will have a negative outcome. Sometimes assistance can offset some of the human interference already in place such as helping a turtle that is on the side of the road. Other times our “helping out” can have consequences we can’t imagine. An example of this is stopping a predator from catching it’s prey. It may be difficult and go against our instincts to help a creature in need, but realize that the predator has it’s place in nature as well and keeping it from catching it’s prey could result in starvation. Without predators, the prey species would become overpopulated. This would result in devastation of food sources and starvation of the prey species. This is just a very small part of natures process but I hope it helps to paint the bigger picture.

Nature is a delicate balance that when interfered with can have consequences that are not intended. This being said, some simple acts can be helpful in overcoming other forms of human interference. It is important to be aware of this when becoming involved with or enjoying nature. In my experience the happy outweighs the sad and I hope when you become more aware of nature you will see this as well.

## AI's output
* Negative aspects of nature highlight and deepen appreciation for its positive experiences.
* Interfering with natural processes can disrupt ecological balance and cause unintended consequences.
* While some human intervention can be beneficial, it requires awareness and respect for nature’s delicate balance.


## My reflection
I see that the refined prompt produced a more concise output. The weak prompt did it's own work but it did not fully meet my requirements and the summary it produced was still quite vague. But the refined prompt made the model to cut out every unnecessary part from the summary, and it gave me exactly what I needed.