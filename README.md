# Carbon-Footprint
AI Model Training Platform with Reduced Carbon Footprint
**Overview**
It is a cloud-based platform that allows users to train AI models efficiently while minimizing their carbon footprint. The platform integrates real-time energy data, optimizes cloud region selection for low-carbon impact, and promotes sustainable AI development practices.

**Problem Statement**
Training large AI models like GPT-3 requires vast computational resources, contributing significantly to carbon emissions. For instance, training such models can generate a carbon footprint equivalent to driving 700,000 kilometers by car. Our platform aims to tackle this environmental challenge.

**Solution**
We offer a comprehensive solution by combining efficient energy usage insights, automation, and optimized resource allocation. Key features include:

**Real-Time Energy Data:** Utilizes the ElectricityMaps API to gather information on energy sources and carbon intensity for different regions.
**Smart Region Selection:** Automatically chooses cloud regions with low carbon intensity or allows manual selection.
**Efficient CPU Training:** Switches from GPU-based training to energy-efficient distributed CPU training using Intel's optimized processors.
**Carbon Footprint Estimation:** Provides an estimate of potential carbon emissions using Google’s Carbon Footprint Tool API.
**Post-Training Reports:** Generates a detailed carbon emissions report post-training to help users fully understand their environmental impact.
# Technical Stack
**DevOps:** Docker, Kubernetes
**AI Tools:** Hugging Face, Intel OneAPI
**Cloud Services:** Google Cloud, ElectricityMaps API
**Hardware:** Intel® Xeon® CPUs
# Benefits
**Reduced Carbon Emissions:** Optimize AI model training by selecting low-carbon regions and using energy-efficient hardware.
**Cost-Efficiency:** Cut down energy consumption and costs by switching to distributed CPU training.
**Sustainability:** Promote responsible AI development aligned with the UN's Sustainable Development Goals (SDG 13: Climate Action).
# How It Works
**Energy Data Collection:** Real-time data on energy sources and carbon intensity is collected via the ElectricityMaps API.
**Automated Region Selection:** The platform automatically selects cloud regions with lower carbon emissions.
**Efficient Training:** AI models are trained using Intel® Xeon® CPUs in distributed clusters to ensure high performance with lower energy usage.
**Post-Training Insights:** Users receive detailed carbon emission reports to assess the environmental impact of their training sessions.
