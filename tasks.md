# Workshop: Automation Basics

## Step 1 – Create a VM with Terraform
**Goal:** Create a `main.tf` file that defines a VM resource.  

**Steps:**  
1. Open a new file called `main.tf`.  
2. Define a cloud provider (AWS, Azure, or another).  
3. Add a resource block for a virtual machine.  
4. Use variables for the VM name and size.  
5. Initialize Terraform and check the plan to see what will be created.  

**End Result:** A `main.tf` file that defines a VM resource.  
Bonus: try to run `terraform plan` to print the output before actually applying

---

## Step 2 – Say Hello with Ansible
**Goal:** Write a tiny Ansible playbook that prints a message.  

**Steps:**  
1. Create a new `.yml` playbook file.  
2. Define `localhost` as the target host.  
3. Add a single task to print `"Hello from Ansible!"`.  
4. Run the playbook and see the message in the terminal.  

**End Result:** A working Ansible playbook that demonstrates task execution.  
Bonus: Add another task to **create a folder** on your machine.  

---

## Step 3 – Run Docker Hello World
**Goal:** Run a Docker container that prints “Hello World.”  

**Steps:**  
1. Ensure Docker is installed on your machine.  
2. Pull and run the official `hello-world` image.  
3. Observe the output message in the terminal.  

**End Result:** A successful Docker container run with a “Hello World” output.  
Bonus: Change the command slightly to print a **custom message** instead of “Hello World.”
