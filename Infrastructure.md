# Infrastructure as Code (IaC) Notes

## Definition

Infrastructure as Code (IaC) is the practice of managing and provisioning computing infrastructure using machine-readable configuration files rather than manual processes.

Think: **"Treat infrastructure like software code."**

---

## How IaC Works

* Write configuration files describing infrastructure requirements.
* Use tools to deploy infrastructure automatically.
* Changes to infrastructure are version-controlled and repeatable.

**Example:** Writing a YAML file to define a server, then using it to deploy infrastructure.

---

## Benefits

* **Consistency:** Same environment every time.
* **Speed:** Quick infrastructure deployment.
* **Automation:** Reduces manual errors.
* **Version Control:** Track infrastructure changes like code.

---

## IaC Tools

* **Terraform** – Cloud-agnostic IaC tool.
* **AWS CloudFormation** – AWS-specific IaC tool.
* **Ansible** – Configuration management and automation.
* **Puppet / Chef** – Configuration automation tools.

---

## Types of IaC

1. **Declarative IaC:** Define desired state, IaC tool figures out how to achieve it.

   * Example: Terraform, CloudFormation.
2. **Imperative IaC:** Specify exact commands to achieve the desired state.

   * Example: Ansible.

---

## Real-Life Example

Netflix uses Terraform to manage cloud resources, ensuring consistency across environments.

---

**Summary:**
IaC = **Automating infrastructure creation and management using code for consistency, speed, and scalability.**


<img width="1250" height="698" alt="image" src="https://github.com/user-attachments/assets/08cff9ae-92ac-4459-a5c1-0dd1cc351785" />

<img width="1203" height="598" alt="image" src="https://github.com/user-attachments/assets/d9009447-ed41-4f50-a170-1f77b1a5f3bf" />
