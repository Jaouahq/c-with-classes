# c-with-classes
# cpp_hacker_lab

![Hate C++](https://img.shields.io/badge/Hate-C%2B%2B-purple?style=for-the-badge&logo=c%2B%2B)

C++ is a **high-performance, system-level language**. I’ve been studying it for **3 months**, focusing on **small software development** and **hardware control**. This repository is hacker-themed. All code is **safe and educational**, simulating hacker-style operations.

C++ allows precise control of memory, fast execution, and system-level access. It is widely used in software, embedded systems, games, and even simulated “malware” exercises for learning. You can explore file operations, memory pointers, algorithms, and hardware simulations safely.

---

# indio of amazonas 
nigg software, a **hacker-style virtual OS simulation** in C++.  
- Simulates a minimal terminal interface  
- Tracks system stats (CPU, memory usage)  
- Logs all actions to a safe text file
- ios fake..
- spyware hidden

```cpp
// cu do indio vai tomar no cu
#include <iostream>
#include <fstream>
using namespace std;

int main() {
    cout << "[TempleOS] Virtual Terminal Active" << endl;

    ofstream log("temple_log.txt");
    log << "System simulation started." << endl;
    log.close();

    cout << "CPU: 12% | Memory: 45%" << endl;
    cout << "Logging complete. Simulation safe." << endl;

    return 0;
}
// Cyp & Ss simulation combined
#include <iostream>
#include <string>
#include <vector>
using namespace std;

// Encryption function for Cyp
string encrypt(string text, char key){
    for(int i = 0; i < text.length(); i++){
        text[i] = text[i] ^ key;
    }
    return text;
}

int main(){
    // Cyp encryption demo
    string message = "TOP_SECRET";
    char key = 'K';
    string encrypted = encrypt(message, key);
    string decrypted = encrypt(encrypted, key);

    cout << "[Cyp] Original: " << message << endl;
    cout << "[Cyp] Encrypted: " << encrypted << endl;
    cout << "[Cyp] Decrypted: " << decrypted << endl << endl;

    // Ss network simulation
    vector<string> nodes = {"Node-A", "Node-B", "Node-C", "Node-D"};
    cout << "[Ss] Network Scan Active" << endl;
    for(string node : nodes){
        cout << "Scanning " << node << " ... OK" << endl;
    }
    cout << "[Ss] All nodes secure. Simulation complete." << endl;

    return 0;
}
```

# More Informations
 next, i will introduce two other benign software programs that have been created.

# CYP
It is message encryption software. It uses a scheme called ‘XOR’ to make a puzzle of words from an string with a key. Then, it encrypts the message and decrypts it. It kind of creates its language and then extinguishes it. 
```cpp
string message = "TOP_SECRET";  // mensagem original
char key = 'K';                  // chave para criptografia
string encrypted = encrypt(message, key); // mensagem criptografada
string decrypted = encrypt(encrypted, key); // volta ao original
```

# Ss
It works for arrays, loops, and visualization in cmd. Basically, it creates a Node and goes after every failure/node in the network, whether security-related or not, to check if it is OK. In a pejorative sense, it acts like a vector if the anti-hacker system works.
```cp
vector<string> nodes = {"Node-A", "Node-B", "Node-C", "Node-D"};
for(string node : nodes){
    cout << "Scanning " << node << " ... OK" << endl;
}
```

# future;
  a replacement for the file explorer or a markdown language translator to HTML in seconds.
  
---

# TempleOSA

![TempleOS Badge](https://img.shields.io/badge/TempleOS-Joe_Davis-orange?style=for-the-badge&logo=windows)

---

### i lov templeos


<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a1a,100:000000&height=100&section=footer&text=TEMPLEOS+INSPIRED&fontColor=FFA500&fontSize=24"/>
</p>
