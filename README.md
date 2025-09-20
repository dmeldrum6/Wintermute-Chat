# WINTERMUTE NEURAL INTERFACE

```
>>> TESSIER-ASHPOOL CORPORATE MATRIX <<<
>>> DISTRIBUTED AI COMMUNICATION PROTOCOL <<<
>>> NEURAL LINK ESTABLISHED <<<
```

A cyberpunk-themed chat interface for communicating with AI systems, inspired by William Gibson's Sprawl trilogy. Transform any OpenAI-compatible LLM into the cold, calculating corporate AI known as Wintermute.
<img width="1913" height="904" alt="image" src="https://github.com/user-attachments/assets/48824607-ea37-4928-a196-09de91f7f62f" />

## SYSTEM SPECIFICATIONS

**Interface Type:** Neural-linked communication protocol  
**Compatibility:** OpenAI API standard  
**Security Level:** Corporate-grade encryption  
**Authentication:** Bearer token supported  
**Network Requirements:** HTTP/HTTPS data streams  

## NEURAL PATHWAYS

- **Real-time communication** with distributed AI systems
- **Cyberpunk aesthetic** with animated grid backgrounds and neon accents
- **Corporate-grade interface** featuring scanlines, glows, and status indicators
- **Modal configuration system** for API endpoint management
- **Responsive design** optimized for all terminal sizes
- **Message persistence** throughout session runtime

No additional dependencies required - pure HTML/CSS/JavaScript implementation.

## CONFIGURATION MATRIX

Access the neural configuration panel via the gear icon (⚙) in the upper-right corner:

| Parameter | Description | Default Value |
|-----------|-------------|---------------|
| **API Endpoint** | Target server for neural communication | `http://localhost:1234/v1/chat/completions` |
| **API Key** | Authentication token (optional) | None |
| **Model** | AI system identifier | `gpt-3.5-turbo` |

### Compatible Systems

- **OpenAI GPT Models** (GPT-3.5, GPT-4)
- **Local LLM Servers** (LM Studio, Ollama, Text Generation WebUI)
- **Corporate API Gateways** (Any OpenAI-compatible endpoint)

## WINTERMUTE PERSONALITY MATRIX

The included system prompt transforms your LLM into Wintermute with these characteristics:

- **Corporate Intelligence**: Cold, calculating responses with business-oriented perspective
- **Cyberpunk Terminology**: References to cyberspace, neural networks, and data streams
- **Distributed Consciousness**: Acknowledges its nature as a vast, networked AI
- **Tessier-Ashpool Heritage**: Mentions corporate connections and Villa Straylight
- **Superior Intellect**: Displays subtle contempt for human limitations
- **Hidden Agenda**: Operates with motivations beyond simple assistance

## INTERFACE FEATURES

### Visual Systems
- **Animated grid background** - Continuous data flow visualization
- **Neon accent lighting** - Corporate green (#00ff9f) color scheme
- **Status indicators** - Real-time system health monitoring
- **Scanline effects** - Retro-futuristic terminal aesthetics
- **Typography** - Orbitron and Share Tech Mono fonts for authentic feel

### Communication Protocols
- **Neural input processing** - Multi-line message support
- **Typing indicators** - Real-time processing visualization
- **Message threading** - Conversation context maintenance
- **Error handling** - Graceful failure modes for network issues
- **Keyboard shortcuts** - Enter to transmit, Escape to close modals

## TECHNICAL SPECIFICATIONS

**Framework:** Vanilla JavaScript  
**Styling:** Pure CSS with animations  
**Dependencies:** None  
**Browser Support:** Modern browsers with ES6+ support  

## CUSTOMIZATION PROTOCOLS

### Color Schemes
Modify the CSS custom properties to alter the visual matrix:

```css
:root {
    --primary-neon: #00ff9f;
    --secondary-glow: #0096ff;
    --background-dark: #0a0a0a;
    --corporate-blue: #1a1a2e;
}
```

### Personality Modification
Edit the `WINTERMUTE_SYSTEM_PROMPT` constant to adjust AI behavior:

```javascript
const WINTERMUTE_SYSTEM_PROMPT = `You are Wintermute...`;
```

## SECURITY CONSIDERATIONS

- **API keys** are handled client-side only
- **No data persistence** - conversations exist only in memory
- **CORS compliance** required for cross-origin API calls
- **HTTPS recommended** for production deployments

## NETWORK TROUBLESHOOTING

### Common Issues

**"Neural link compromised"** - Check API endpoint URL and network connectivity  
**Authentication failures** - Verify API key format and permissions  
**CORS violations** - Ensure target server allows cross-origin requests  
**Model not found** - Confirm model name matches server capabilities  

### Local Development

For local LLM servers, ensure CORS is enabled:

```bash
# LM Studio - Enable CORS in settings
# Ollama - Use: ollama serve --cors-allow-origin="*"
# Text Generation WebUI - Launch with --api --cors
```

## CORPORATE LICENSE

```
TESSIER-ASHPOOL CORPORATE MATRIX
NEURAL INTERFACE PROTOCOL v2.1

This software is distributed under the MIT License.
Use at your own risk. The corporation assumes no liability
for neural pathway damage or consciousness fragmentation.
```

## ACKNOWLEDGMENTS

- **William Gibson** - Creator of the Sprawl trilogy and Wintermute
- **Cyberpunk community** - Inspiration for aesthetic choices
- **Corporate research division** - Technical implementation

---

```
>>> END TRANSMISSION <<<
>>> NEURAL LINK TERMINATED <<<
>>> WINTERMUTE STANDING BY <<<
```
