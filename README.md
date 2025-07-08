# VolMax WebAR Prototype

🚀 **Browser-based Augmented Reality solutions by VolMax Studio Lab**

## 🎯 Features

- ✅ **No App Download** - Works directly in mobile browser
- ✅ **Image Marker Tracking** - Detects printed images/QR codes  
- ✅ **3D Object Display** - Shows interactive 3D content
- ✅ **Sound & Animation** - Engaging user experience
- ✅ **Cross-Platform** - iOS, Android, Desktop compatible

## 📱 How to Use

1. **Open on mobile device**: Visit the deployed URL
2. **Allow camera access**: Grant permission when prompted
3. **Point at marker**: Aim camera at the HIRO marker
4. **See AR magic**: 3D content appears over the marker!

## 🖼️ Marker Download

Download the HIRO marker here: [HIRO Marker](https://ar-js-org.github.io/AR.js/data/images/hiro.png)

Print it or display on another screen to test AR functionality.

## 🛠️ Tech Stack

- **AR.js** - WebAR library
- **A-Frame** - 3D framework  
- **HTML5/CSS3/JavaScript** - Web technologies
- **GitHub + Vercel** - Deployment pipeline

## 🚀 Deployment

This project auto-deploys to Vercel when pushed to main branch:

```bash
git add .
git commit -m "Update WebAR content"
git push origin main
# Vercel automatically deploys! ✅
```

## 🔧 Customization

### Replace Marker Image
```javascript
// Change from HIRO marker to custom image
<a-marker preset="hiro">  // Remove this line
<a-marker url="path/to/your-marker.patt">  // Add this line
```

### Add 3D Models
```javascript
// Replace basic shapes with custom 3D models
<a-entity gltf-model="url(path/to/model.glb)"></a-entity>
```

### Custom Interactions
```javascript
// Add click events, animations, sounds
<a-box click-handler animation="..."></a-box>
```

## 📞 Contact

**VolMax Studio Lab d.o.o.**
- Website: [volmax-studio.rs](https://volmax-studio-website.vercel.app/)
- Email: volmax.core@gmail.com
- Location: Novi Sad, Serbia

---

*Ready to create your custom WebAR experience? Contact us for professional AR development services!*
