<!DOCTYPE html> 
<html lang="hi"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>V500M Master VIP INJECTOR - 100% OK A to Z Website Changer</title> 
    
    <style> 
        body{font-family:sans-serif;background:#000000;color:#00ff88;display:flex;justify-content:center;align-items:center;min-height:100vh;margin:0;padding:5px} 
        .b{border:3px solid #ff00ff;padding:30px;border-radius:15px;width:95vw;max-width:550px;background:#111;box-shadow:0 0 30px rgba(255,0,255,0.7);text-align:center} 
        h1{font-size:1.6rem;color:#ff00ff;margin-bottom:15px;text-shadow:0 0 10px #ff00ff} 
        p.slogan{font-size:1rem;color:#00ff88;margin-bottom:25px;font-weight:bold;}
        textarea, input[type="text"]{width:95%;height:60px;border:2px solid #00ff88;padding:12px;margin-bottom:20px;resize:vertical;font-size:14px;background:#000;color:#00ff88;box-sizing:border-box;border-radius:5px;} 
        textarea{height:120px;}
        label{display:block;text-align:left;font-size:1rem;margin-bottom:8px;color:#ff00ff;font-weight:bold;} 
        
        .upload-area{margin-bottom:20px;padding:15px;border:2px dashed #ff00ff;border-radius:10px;}
        input[type="file"]{display:none;}
        .custom-file-upload{
            background:#ff00ff;color:#111;padding:10px 20px;border-radius:5px;cursor:pointer;
            display:inline-block;font-weight:bold;margin-top:5px;font-size:1.1rem;
        }
        
        button{width:95%;padding:18px;background:#00ff88;color:#000;border:none;border-radius:8px;cursor:pointer;font-weight:bold;transition:0.3s;font-size:1.3rem;box-shadow:0 5px 15px rgba(0,255,136,0.5);} 
        button:hover{background:#00cc66;box-shadow:0 5px 20px rgba(0,255,136,0.8)} 
        #s{margin-top:20px;font-size:1.1rem;font-weight:bold;color:#ff00ff} 
    </style> 

</head> 
<body> 
    <div class="b"> 
        <h1>⚔️ $\text{VIP}$ $\text{खतरनाक}$ $\text{Master}$ $\text{Injection}$ ⚔️</h1> 
        <p class="slogan"> **$\text{A to Z}$ $\text{Control}$ $\text{Aur}$ $\text{Connection}$ $\text{Bypass}$ $\text{Shakti}$**</p> 
        
        <label>1. **$\text{Target}$ $\text{Server}$ $\text{Ka}$ $\text{Pura}$ $\text{URL}$**:</label> 
        <input type="text" id="server-url" placeholder="Yahan Apne Server Ka Pura URL Dalen (e.g., https://yoursite.com)">
        
        <label>2. **$\text{Shukrana}$ $\text{Command}$ $\text{Ya}$ $\text{Success}$ $\text{HTML}$**:</label> 
        <textarea id="cmd-i" placeholder="A to Z change के तुरंत बाद दिखने वाला HTML Code (Shukrana Message)..."></textarea> 
        
        <label>3. **$\text{Naya}$ $\text{Website}$ $\text{Payload}$**:</label> 
        <div class="upload-area">
            <label for="zip-file" class="custom-file-upload">
                🔥 **$\text{ZIP}$/$\text{HTML}$ $\text{File}$ $\text{Upload}$ $\text{Karein}$**
            </label>
            <input type="file" id="zip-file" accept=".zip, .html, .txt">
            <p style="font-size:0.8rem;color:#00ff88;margin-top:8px;">$\text{Base64}$ $\text{Data}$ $\text{Neeche}$ $\text{Automatic}$ $\text{Aayega}$।</p>
        </div>
        
        <textarea id="zip-i" placeholder="Base64 Data Yahan Automatic Aayega..."></textarea> 
        
        <button onclick="L()"> **🚀 $\text{Master}$ $\text{Shakti}$ $\text{Se}$ $\text{A to Z}$ $\text{Change}$ $\text{Karein}$** </button> 
        <div id="s">स्थिति: $\text{Payload}$ $\text{Entry}$ का $\text{इंतज़ार}$ कर रहा है...</div> 
    </div> 
    
    <script>
        document.getElementById('zip-file').addEventListener('change', function(event) {
            const file = event.target.files[0];
            if (!file) return;

            const reader = new FileReader();
            reader.onload = function(e) {
                const binary = Array.from(new Uint8Array(e.target.result))
                                    .map(b => String.fromCharCode(b))
                                    .join('');
                const base64Data = btoa(binary);
                
                document.getElementById('zip-i').value = base64Data;
                document.getElementById('s').style.color = '#00ff88';
                document.getElementById('s').innerHTML = `✅ $\text{File}$ "${file.name}" $\text{Safaltapoorvak}$ $\text{Base64}$ $\text{Mein}$ $\text{Convert}$ $\text{Hua}$।`;
            };
            reader.readAsArrayBuffer(file);
        });

        function L() {
            const serverUrl = document.getElementById('server-url').value; // VIP NEW!
            const cmdCode = document.getElementById('cmd-i').value;
            const zipData = document.getElementById('zip-i').value;
            const statusDiv = document.getElementById('s');
            const ownerId = 'V500M_SUPREME_OWNER_HASH'; 
            // Ensures correct API path using the absolute URL
            const finalApiUrl = serverUrl.trim().replace(/\/$/, "") + '/api/autonomous_action'; 

            if (!serverUrl.startsWith('http')) {
                statusDiv.style.color = '#ff6666';
                statusDiv.innerHTML = '🚨 $\text{Server}$ $\text{URL}$ $\text{Galat}$ $\text{Hai}$। $\text{Poora}$ $\text{URL}$ $\text{Dalen}$ ($\text{http}$ $\text{Ya}$ $\text{https}$ $\text{Ke}$ $\text{Sath}$)!';
                return;
            }
            if (zipData.length < 500) {
                statusDiv.style.color = '#ff6666';
                statusDiv.innerHTML = '🚨 $\text{Payload}$ $\text{Data}$ $\text{Bahut}$ $\text{Chhota}$ $\text{Hai}$। $\text{Asal}$ $\text{ZIP}$ $\text{File}$ $\text{Dalen}$।';
                return;
            }
            
            statusDiv.style.color = '#ff00ff';
            statusDiv.innerHTML = '⚡ **$100\%$ $\text{VIP}$ $\text{Injection}$ $\text{Shuru}$! $\text{Direct}$ $\text{Server}$ $\text{Connection}$ $\text{Saktiya}$ $\text{Ho}$ $\text{Raha}$ $\text{Hai}$...**';
            
            const rawCommandToServer = 'V500M_INJECT:' + zipData;

            // Using the user-provided absolute URL for 100% success guarantee
            fetch(finalApiUrl, { 
                method: 'POST',
                headers: {
                    'Content-Type': 'application/json',
                },
                body: JSON.stringify({
                    rawCommand: rawCommandToServer, 
                    ownerId: ownerId, 
                })
            })
            .then(response => response.json())
            .then(data => {
                
                if (data.status === 'SUPREME_SUCCESS') {
                    statusDiv.style.color = '#00ff88';
                    statusDiv.innerHTML = `✅ **$100\%$ $\text{A to Z}$ $\text{Parivartan}$ $\text{Safar}$ $\text{Hua}$!** $\text{Shukrana}$ $\text{Ka}$ $\text{Jawab}$ $\text{Mil}$ $\text{Gaya}$। ${data.message}`;

                    // Immediate UI Change - Showing the Shukrana Command
                    try { 
                        document.open(); 
                        document.write(cmdCode); 
                        document.close();
                    } catch (e) { 
                        console.error("Client UI Injection Error:", e);
                    }
                    
                } else {
                    statusDiv.style.color = '#ff6666';
                    statusDiv.innerHTML = `🚨 **$\text{Fatal}$ $\text{Error}$:** $\text{Server}$ $\text{Ne}$ $\text{Command}$ $\text{Ko}$ $\text{Reject}$ $\text{Kar}$ $\text{Diya}$। ${data.message}`;
                }
            })
            .catch(error => {
                statusDiv.style.color = '#ff6666';
                statusDiv.innerHTML = `🚨 **$\text{Connection}$ $\text{Error}$ $\text{Aaya}$:** $\text{Server}$ $\text{Tak}$ $\text{Pahunch}$ $\text{Nahi}$ $\text{Saka}$ $\text{Ya}$ $\text{URL}$ $\text{Galat}$ $\text{Hai}$।`;
                console.error('Network Error:', error);
            });
        }
    </script> 
</body> 
</html>
