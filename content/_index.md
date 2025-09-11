---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: |
        AAAI'26 Tutorial
      <!-- image:
        filename: welcome.jpg -->
      text: |
        <br>
        
        Tutorial: Auto-Formalization in Large Language Models era: From Mathematical Proofs to Verifying LLM Reasoning will be hold in AAAI'26. ✨ We sincerely invite all of you who are interested to participate! ✨

  - block: people
    content:
      # title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Researchers
          - Grad Students
          - Administration
          - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: collection
    content:
      title: "Recent Publications"
      subtitle: "Latest research by our team"
      filters:
        author: "11"
      count: 5  # 控制显示的文章数量
      order: desc
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title: Work
      text: |
        You can check out our related [work](./people/)

  - block: markdown
    content:
      title: |
        Abstract
      <!-- image:
        filename: welcome.jpg -->
      text: |
        <div class="full-width-text">
        
        The rapid advances in Large Language Models (LLMs) are transforming research across many fields, yet ensuring the reliability and verifiability of their outputs remains a fundamental challenge, particularly in tasks involving complex reasoning and knowledge integration. In mathematics, formal theorem proving offers a rigorous framework for verifying reasoning by translating natural language into strict formal systems. Leveraging this synergy between LLMs and formal proof verification has emerged as a promising research direction. However, manual formalization is notoriously labor-intensive, driving significant interest in autoformalization—the automatic translation from natural language into formal languages. This tutorial provides a comprehensive introduction to the landscape of autoformalization in the context of LLMs, discussing its core methodologies, diverse applications, and key challenges. Attendees will gain insights into how autoformalization can enhance the reliability of LLM-generated outputs and catalyze advancements in higher mathematics, realistic reasoning tasks, and AI-assisted verification. Ultimately, this line of research promises more robust, rigorous, and trustworthy AI systems.
        </div>

  - block: hero
    content:
      title: |
        Schedule
      <!-- image:
        filename: welcome.jpg -->
      text: |
        - **Introduction (10 min):** What is Autoformalization? *(Motivation and Overview)*
        - **Part 1: Foundations of Autoformalization (20 min)**
          - **Autoformalization Pipeline and Key Components**
            - Data Preprocessing
              - Enhancing Data Quality
              - Expanding Data Coverage
            - Methods and Approaches
              - Rule-Based Methods
              - LLM-Based Methods
            - Postprocessing Techniques
            - Evaluation Metrics and Benchmarks
          - Technical Q&A and Clarifying Questions
        - **Part II: Autoformalization Applications (30 min)**
        - **Autoformalization in Mathematics**
          - Across Mathematical Domains
            - Geometry and Topology
            - Algebra and Number Theory
            - Emerging Mathematical Domains
          - By Problem Difficulty
            - High School Level
            - Undergraduate Level
            - Graduate and Research-Level
        - **Autoformalization for LLM Reasoning Verification**
          - Formal Verification Approaches
            - Proof Assistant–Based Verification
            - Logic Rule–Based Verification
          - Practical Challenges in Integrating LLMs with Formal Systems
        - Technical Q&A and Clarifying Questions (5 min)
        - **Part III: Challenges and Future Directions (20 min)**
          - Data Scarcity and Quality Issues
          - Scaling Autoformalization Methods
          - Reliability of Formal Verification for LLM Outputs
          - Open Problems and Research Directions

        - **Conclusion and Summary (5 min)**

        - **Panel Discussion (15 min)**
          - Moderated expert discussion on challenges, future opportunities, and differing perspectives in autoformalization and LLM verification.
          - Interactive audience Q&A session.
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

---
