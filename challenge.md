# Challenge: Install It Yourself

1. htop shows live CPU and memory usage and the running processes.
   Command: sudo apt install -y htop ; htop

2. Ubuntu offers apache2 version ___
   Command: apt show apache2 | head -4

3. Installed packages: ___
   Command: apt list --installed | wc -l

4. Output: Hello from Alpine
   Command: sudo docker run --rm alpine echo "Hello from Alpine"

5. Key file: /etc/apt/keyrings/docker.asc
   Sources file: /etc/apt/sources.list.d/docker.sources

6. htop removed; running it now says "command not found".
   Commands: sudo apt remove -y htop ; hash -r ; htop
