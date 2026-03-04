# visualize — Blender Addons

A collection of **Blender Python addons** built to eliminate repetitive tasks and improve workflow efficiency for 3D artists and designers.

These tools were developed during active freelance work in 3D interior design — solving real problems that came up on real projects.

---

## 🔌 Addons

### 1. [MultiCam Auto Render Pro](./MultiCam_Auto_Render_Pro)

Automatically renders your scene from every camera in sequence — no manual switching, no repeated clicking.

**The problem it solves:** When presenting 3D interior designs to clients, you often need renders from 8–12 camera angles. Doing this manually means switching cameras, setting filenames, and hitting render repeatedly. This addon does it all in one click.

**Key features:**
- Renders from every camera in the scene sequentially
- User-defined output directory and base filename
- Real-time progress display in the Blender UI (e.g. "Rendering: Camera_03 (42%)")
- Cancel rendering at any point mid-process
- Auto-creates output directory if it doesn't exist

---

### 2. [Camera Object Approach](./Camera_Object_Approach)

Animates the active camera toward any selected object with automatic depth-of-field, in one click.

**The problem it solves:** Setting up camera fly-through animations with DOF manually requires keyframing position and focus distance separately. This addon handles both automatically.

**Key features:**
- Animates camera position from current location to selected object
- Automatically sets and animates depth-of-field distance
- Default animation length of 250 frames
- Works with any scene camera and any object type

---

## 🛠️ Installation (both addons)

1. Download the `.py` file for the addon you want
2. Open Blender → `Edit > Preferences > Add-ons`
3. Click `Install` and select the downloaded file
4. Enable the addon by ticking the checkbox next to its name

---

## 🧰 Built With

- Python 3
- Blender Python API (`bpy`)
- Blender 2.80+

---

## 👤 About

Built by [Maher](https://mahersdesigns.com) — a 3D designer and developer who got tired of doing the same things manually and wrote code to fix it.
