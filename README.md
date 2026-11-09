# // aspectvpn

### Production-grade secure networking SDK for modern mobile app teams.

AspectVPN collapses the friction of embedding secure tunnels, API proxies, and compliance-grade routing into iOS and React Native applications. Instead of fighting heavyweight enterprise VPN tools built for network admins, developers can initialize a secure tunnel natively with a clean, single-line API.

🚀 **[Visit the Landing Page & Join the Developer Beta](https://aspectvpn.app)**

---

## 🛠️ The Architecture Wedge

Most mobile teams wanting to ship secure infrastructure face a broken choice: spend weeks wiring up raw infrastructure layers from scratch, or adopt broad, incumbent enterprise packages that bloat the application bundle. 

AspectVPN narrows the aim to serve native mobile builders with a tight, platform-native core:
- **Ultra-Lightweight Sizing:** A total compilation footprint of under `< 2.4MB`.
- **WireGuard Core:** Built directly on top of the modern, ultra-fast WireGuard protocol.
- **Native Implementation:** Deeply integrated into native Swift (iOS) and Java/Kotlin (Android) layers with a lightweight React Native bridge.
- **Zero-Logs Compliance:** Fully prepared for enterprise-level data privacy routing specifications.

---

## 📦 Intended API Usage Preview

Engineers buy with their eyes. This is a preview of the clean, lightweight drop-in initialization syntax currently under development for the core package:

```typescript
import AspectVPN from '@aspectvpn/react-native';

const appConfig = {
  appId: "dev_0x9f32",
  environment: "production",
  enforceMtls: true
};

// Establish high-performance secure tunnel natively
await AspectVPN.connect(appConfig);
```

---

## 🗺️ Current Launch Roadmap

- [x] Secure core namespace registries across development ecosystems.
- [x] Launch the `aspectvpn.app` landing portal and interactive waitlist engine.
- [ ] Deploy the open-source React Native SDK framework scaffolding.
- [ ] Release the closed developer alpha testing cohort.
- [ ] Launch the unified B2B usage analytics and compliance dashboard portal.

---

## 💬 Join the Loop

We are actively building in public and gathering feedback from mobile infrastructure engineers, systems developers, and startup tech leads.

- **Developer Beta Updates:** Secure your pipeline access keys at [aspectvpn.app](https://aspectvpn.app).
- **Contact & Support:** Connect with the core architecture crew via **dev@aspectvpn.app**.
- **Secure Handling:** Inbound communications are securely forwarded directly to an isolated Proton backend array.
