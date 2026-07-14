# Performance-Testing-Plan-by-Jmeter-for-demoblaze-WebApp


🚀 𝗘𝗻𝗱-𝘁𝗼-𝗘𝗻𝗱 𝗣𝗲𝗿𝗳𝗼𝗿𝗺𝗮𝗻𝗰𝗲 𝗧𝗲𝘀𝘁𝗶𝗻𝗴 𝘂𝘀𝗶𝗻𝗴 𝗝𝗠𝗲𝘁𝗲𝗿 𝗳𝗼𝗿 𝗪𝗲𝗯 𝗔𝗽𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻

I recently worked on a practical performance testing project using Apache JMeter, where I tested a real user Flow on an e-commerce website " demoblaze "

✅ Base URL: https://www.demoblaze.com/

✅ 𝑻𝒆𝒔𝒕 𝑷𝒍𝒂𝒏 / 𝑼𝒔𝒆𝒓 𝑭𝒍𝒐𝒘

👀 Open Home Page
📝 Sign Up
🔐 Login
🗂️ View Category
📦 View Product
➕🛒 Add to Cart
👀🛒 View Cart
💳 Checkout and Payment
🚪  Logout

✅ 𝑱𝑴𝒆𝒕𝒆𝒓 𝑻𝒆𝒔𝒕𝒊𝒏𝒈 𝑻𝒆𝒄𝒉𝒏𝒊𝒒𝒖𝒆𝒔

📄 CSV Data Set Config – for dynamic, parameterized test data
🔗 Correlation – handled dynamic values (Product IDs, tokens)  using Regular Expression Extractor
✅ Assertions – to validate correct server responses
⏱️ Timers – to simulate realistic user think time
📊 Listeners – to collect and analyze performance metrics
⏱️ using Test Fragments for reusable group of samplers
🔗 Recorded the full user journey using HTTP(S) Test Script Recorder

✅ 𝑼𝒔𝒆𝒓 𝑩𝒆𝒉𝒂𝒗𝒊𝒐𝒓 𝑺𝒊𝒎𝒖𝒍𝒂𝒕𝒊𝒐𝒏
Module Controller - 
Uniform Random Timer – adds realistic delays between requests
Loop Controller – repeats requests to simulate load

✅ 𝑹𝒆𝒑𝒐𝒓𝒕𝒊𝒏𝒈 & 𝑨𝒏𝒂𝒍𝒚𝒔𝒊𝒔

View Results Tree – validated individual request responses
Summary Report – reviewed response time and error rate
Aggregate Report – analyzed performance trends
Generated a detailed HTML report by this cmd Command Line " jmeter -n -t "C:\demoblaze.jmx" -l "C:\results.jtl" -e -o "C:\HTMLReport"

✅ 𝑽𝒂𝒍𝒊𝒅𝒂𝒕𝒊𝒐𝒏 & 𝑭𝒊𝒏𝒅𝒊𝒏𝒈𝒔

Validated results against acceptance criteria (response time, error rate, throughput)
Identified failing requests

