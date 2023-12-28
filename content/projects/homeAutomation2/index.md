---
title: "Home Automation Part 2"
date: 2023-12-27T20:02:26-05:00
draft: false
series: ["Home Automation"]
series_order: 2
---

Welcome back to the second part of our exploration into home automation using a lamp, relay, Seeed Studio Xiao microcontroller, and WiFi capabilities. In this installment, we'll dive deeper into the world of smart control by integrating Apple Shortcuts and an API tester, unlocking the potential to control your home environment with the power of your voice.

**Part 2: Elevating Control with Apple Shortcuts and API Tester**

**Harnessing Apple Shortcuts:**

Apple Shortcuts is a powerful tool that allows you to automate tasks on your iOS device, from simple actions to complex workflows.

**Creating Siri Shortcuts:**

1. **Shortcuts App:** Open the Shortcuts app on your iOS device.
    
2. **Create a New Shortcut:** Create a new shortcut and add actions that send HTTP requests to the Seeed Studio Xiao microcontroller.
    
3. **Voice Activation:** Assign a voice command to the shortcut. For example, "Turn on the light."
    

**Using API Tester:**

An API tester is a tool that lets you send and receive HTTP requests and responses. In this case, it acts as a bridge between your voice command and the Seeed Studio Xiao microcontroller.

**Setting Up API Testing:**

1. **Choose an API Tester:** There are various options available, such as Postman or Insomnia.
    
2. **Define Endpoints:** Configure the API tester to send HTTP requests to the Seeed Studio Xiao's IP address and specific endpoint that triggers the relay.
    

**Integration and Automation:**

1. **Activate Siri Shortcut:** Using your voice, trigger the Siri Shortcut you created earlier. For example, say, "Hey Siri, turn on the light."
    
2. **HTTP Request:** The Siri Shortcut sends an HTTP request to the Seeed Studio Xiao microcontroller through the API tester.
    
3. **Relay Control:** The Seeed Studio Xiao receives the HTTP request, processes it, and controls the relay, turning on the lamp.
    

**Benefits of Siri Integration:**

1. **Voice Control:** Utilize the power of your voice to control your home environment. Easily turn on/off the lamp without touching any device.
    
2. **Seamless Interaction:** Apple Shortcuts and API testing create a seamless interaction between your voice commands and the physical lamp.
    
3. **Customization:** You can create multiple Siri Shortcuts for different commands, enhancing the level of control and personalization.
    

**Conclusion**

By seamlessly integrating Apple Shortcuts and API testing into your smart home setup, you've taken home automation to the next level. Your voice commands now have the power to control your lamp through the Seeed Studio Xiao microcontroller. This amalgamation of technologies demonstrates the synergy between hardware, software, and voice interaction, transforming your living space into a hub of efficient, intuitive, and voice-activated control. As you continue to explore the possibilities of smart home technology, the journey promises endless innovation and convenience, all at your command.