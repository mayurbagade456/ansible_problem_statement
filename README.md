### ♨♨ There are 3 Tasks Specially:

**Task 1:** ANSIBLE PROVISIONING  
(Using the control node, install `amazon.aws` collection and use `boto3` Python module to provision 3 EC2 instances)

**Task 2:** PASSWORDLESS AUTHENTICATION  
(Using `.pem` file or password, establish passwordless authentication across all nodes)

**Task 3:** CONFIGURATION MANAGEMENT  
(Make a Playbook or Role to shutdown the systems which are Ubuntu)

---

### 👻👻 Things To Know:

**🔁 Ansible Idempotency:**  
When you run a task twice, Ansible will detect if it's already done and **skip it automatically**. You must differentiate tasks with **meaningful names or tags**.

**🧠 Ansible Conditioning:**  
Unlike traditional programming languages, Ansible uses YAML and applies conditions using the `when:` keyword.

---

### 🗝️ To Create Vault Pass File (Base64 encoded, 2048 bytes):

```bash
openssl rand -base64 2048 > vault.pass

```

---

📸 Output Screenshots

✅ Terminal: Playbook stop.yaml (only shuts down Ubuntu instances)



![ubuntus only shutdown](https://github.com/user-attachments/assets/ddd5a630-a271-47a7-a71e-2c543dbbc115)


--

✅ AWS Console: Shows 2 instances (Ubuntu/Debian) stopped successfully

![aws folder](https://github.com/user-attachments/assets/6fc8d0c5-d779-45ce-a0aa-0e22a8a36069)

