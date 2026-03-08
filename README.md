# 🔧 Threaded Insert Press - Open Source

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![3D Printing](https://img.shields.io/badge/3D%20Printing-DIY-blue.svg)](https://www.thingiverse.com/)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://github.com/HexLions)

A precision threaded insert press built from 70% 3D printed parts with minimal hardware components. Perfect for installing heat-set inserts in 3D printed parts with professional accuracy and consistency.

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_174854.jpg" width="600">
</p>

## ✨ Features

- 🖨️ **70% 3D Printable** - Most components can be printed on any FDM printer
- 🔩 **Minimal Hardware** - Uses common, easy-to-find components
- ⚖️ **Weight-Assisted** - Gravity-powered for consistent pressure
- 🎯 **High Precision** - V-slot linear motion ensures straight insertion
- 🔥 **Soldering Iron Compatible** - Works with standard soldering irons
- 📏 **Adjustable Height** - 400mm vertical travel for various part sizes
- 💰 **Cost-Effective** - Build for ~$30-40 in materials
- 🔧 **Easy Assembly** - Simple step-by-step construction
- 🎨 **Customizable** - Two grip designs for different soldering iron types
- ♻️ **Reusable** - Designed for thousands of inserts

## 🎯 Perfect For

- Installing heat-set inserts (M2, M3, M4, M5)
- 3D printing projects requiring threaded holes
- Small production runs
- Maker spaces and workshops
- DIY enthusiasts
- Professional prototyping
- Consistent, repeatable results

## 🛠️ Hardware Requirements

### Bill of Materials (BOM)

#### Aluminum Extrusion
- **1x** 2040 V-Slot Extrusion 400mm

#### Fasteners
- **15x** M5 × 30mm Button Head screws
- **13x** M5 Nuts
- **10x** M5 Washers

#### Motion Components
- **5x** 608RS Bearings (skateboard bearings)

#### Belt
- **1x** GT2 Timing Belt (~450mm length)

#### Tool (Not Included)
- **1x** Soldering Iron (25-60W recommended)
  - Compatible with standard grip diameter: 15-20mm
  - Temperature controlled preferred

### Required Tools for Assembly

- M5 Allen wrench (hex key)
- M5 nut wrench or adjustable wrench
- Scissors or belt cutter
- Optional: Calipers for belt length measurement

## 📚 3D Printed Parts

### Parts List

All STL files are included in the repository. Print settings below are recommendations:

| Part Name | Quantity | Infill | Supports | Notes |
|-----------|----------|--------|----------|-------|
| Base.stl | 1 | 30% | No | Base mounting plate |
| Front Carriage.stl | 1 | 40% | Yes | Main carriage |
| Rear Carriage.stl | 1 | 40% | Yes | Weight carriage |
| Soldering Arm.stl | 1 | 30% | No | Connects iron to carriage |
| Soldering Iron Grip Standard.stl | 1 | 30% | No | Standard grip |
| Soldering Iron Grip.stl | 1 | 30% | No | Alternative grip |
| Decentration Post.stl | 1 | 30% | No | Belt tensioner |
| Bearings In.stl | 5 | 20% | No | Bearing inner race |
| Bearings Out.stl | 5 | 20% | No | Bearing outer race |
| Bearings H.stl | 2 | 20% | No | Horizontal bearings |
| Spacer.stl | 2 | 20% | No | Bearing spacers |
| Pulley Plate.stl | 1 | 30% | No | Top bearing mount |
| Cover.stl | 1 | 20% | No | Rear carriage cover |
| Weight Arm.stl | 1 | 30% | No | Belt tensioning arm |

### Print Settings

**Recommended Settings:**
- **Layer Height:** 0.2mm (0.3mm for faster prints)
- **Wall Count:** 3-4 walls minimum
- **Infill Pattern:** Grid or Gyroid
- **Material:** PLA, PETG, or ABS
- **Nozzle:** 0.4mm standard

**Quality Parts (Front/Rear Carriage):**
- **Layer Height:** 0.2mm
- **Infill:** 40%
- **Walls:** 4
- **Top/Bottom Layers:** 5

## 🚀 Assembly Instructions

### Overview

Total assembly time: **1-2 hours**

The press assembles in three main sections:
1. Base and vertical rail
2. Front carriage (soldering iron mount)
3. Rear carriage (weight system)

---

### Section 1: Base Assembly

#### Step 1 - Prepare Base Components

**Required:**
- 1x Base.stl
- 1x 2040 V-Slot Extrusion 400mm
- 2x M5 × 30mm Button Head screws
- 2x M5 Nuts

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_170647.jpg" width="400">
</p>

**Instructions:**
1. Insert M5 nuts into the slots on Base.stl
2. Position 2040 V-Slot extrusion vertically
3. Align mounting holes

#### Step 2 - Attach Base to Extrusion

**Instructions:**
1. Insert screws through Base.stl
2. Thread into T-slot nuts in the extrusion
3. Tighten until snug (don't overtighten)

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_170750.jpg" width="400">
</p>

**✓ Checkpoint:** Base should be firmly attached with extrusion standing vertically.

---

### Section 2: Front Carriage Assembly

#### Step 3 - Gather Front Carriage Components

**Required:**
- 7x M5 × 30mm Button Head screws
- 7x M5 Nuts
- 3x 608RS Bearings
- 3x Bearings Out.stl
- 3x Bearings In.stl
- 3x Spacer.stl
- 1x Decentration Post.stl
- 1x Front Carriage.stl
- 1x Soldering Arm.stl
- 1x Soldering Iron Grip (Standard or alternative)

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_171735.jpg" width="400">
</p>

**⚠️ Important:** Test-fit your soldering iron in both grip designs before proceeding!

#### Step 4 - Assemble Bearing Units (Make 3)

**For each bearing unit:**

1. Slide Bearings In.stl onto M5 screw
2. Press 608RS bearing into Bearings Out.stl
   - Should be snug fit
   - Press evenly to avoid binding

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_171802.jpg" width="300">
</p>

#### Step 5 - Combine Bearing Components

**Instructions:**
1. Push Bearings Out.stl (with bearing) onto screw
2. Inner and outer bearing holders should sandwich the 608RS
3. Repeat for all 3 bearing assemblies

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_171828.jpg" width="300">
</p>

#### Step 6 - Add Spacers

**Instructions:**
1. Install Spacer.stl on top of 2 bearing assemblies
2. Leave one bearing assembly without spacer
3. Spacers prevent bearing binding during movement

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_171846.jpg" width="300">
</p>

#### Step 7 - Install Decentration Post

**Instructions:**
1. Thread Decentration Post.stl onto the last (non-spacer) screw
2. This component tensions the belt
3. Should rotate freely

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_172001.jpg" width="300">
</p>

#### Step 8 - Mount to Front Carriage

**Critical Step - Pay Attention to Orientation!**

**Instructions:**
1. Locate "FRONT" marking on Front Carriage.stl
2. **Correct Orientation:**
   - Bearings face INWARD (toward extrusion)
   - If bearings are facing up, "FRONT" should be upside down
3. Insert all screws through carriage
4. Tighten nuts on opposite side

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_172054.jpg" width="300">
</p>

**✓ Checkpoint:** All 3 bearings should face the same direction, aligned for V-slot.

#### Step 9 - Prepare Soldering Iron Grip

**Instructions:**
1. Insert 2x M5 screws into Soldering Iron Grip.stl
2. Don't tighten yet
3. Test-fit your soldering iron

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_172326.jpg" width="300">
</p>

#### Step 10 - Attach Soldering Arm

**Instructions:**
1. Place 2x M5 nuts in Soldering Arm.stl
2. Thread screws from grip into arm
3. Tighten to create rigid connection

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_172356.jpg" width="300">
</p>

#### Step 11 - Join Carriage and Arm

**Instructions:**
1. Align Soldering Arm with Front Carriage
2. Use remaining M5 screws and nuts
3. Ensure 90° angle between parts

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_172634.jpg" width="300">
</p>

#### Step 12 - Install Belt (Front End)

**Instructions:**
1. Cut GT2 belt to approximately 450mm
2. Thread one end through Base.stl belt clamp
3. **Belt orientation:** Teeth facing INWARD
4. Route belt over Soldering Arm
5. Secure with screw

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_172710.jpg" width="300">
</p>

**✓ Checkpoint:** Front carriage complete! Set aside carefully.

---

### Section 3: Rear Carriage Assembly

#### Step 13 - Gather Rear Components

**Required:**
- 10x M5 Washers
- 3x M5 Nuts
- 3x M5 × 30mm Button Head screws (remaining)
- 3x 608RS Bearings (from bearing assemblies)
- 1x Rear Carriage.stl
- 1x Cover.stl
- 1x Weight Arm.stl

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_173255.jpg" width="500">
</p>

**Instructions:**
1. Assemble bearings identically to Front Carriage (Steps 4-7)
2. Mount to Rear Carriage.stl

#### Step 14 - Attach Belt (Rear End)

**Instructions:**
1. Measure remaining belt length (should be ~450mm total)
2. Cut if necessary
3. Thread through Weight Arm.stl slot
4. **Belt orientation:** Teeth facing INWARD
5. Clamp with Weight Arm against Rear Carriage
6. Secure with M5 nut

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_173542.jpg" width="300">
</p>

**💡 Tip:** Leave belt slightly loose for now - final tensioning in Step 20.

#### Step 15 - Add Washers for Weight

**Instructions:**
1. Stack washers on the 3 vertical screws
2. **Number of washers depends on your soldering iron weight:**
   - Light iron (25W): 8-10 washers
   - Medium iron (40W): 6-8 washers
   - Heavy iron (60W): 4-6 washers
3. Goal: Balance iron weight for smooth, controlled descent

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_173618.jpg" width="300">
</p>

**💡 Tip:** Start with more washers, test, and remove if needed.

#### Step 16 - Install Cover

**Instructions:**
1. Place Cover.stl over Rear Carriage
2. Align holes with screw posts
3. Cover protects belt mechanism

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_173831.jpg" width="300">
</p>

#### Step 17 - Secure with Nuts

**Instructions:**
1. Thread 2x M5 nuts onto screws
2. Tighten to secure cover
3. Don't overtighten - parts should not deform

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_173933.jpg" width="300">
</p>

#### Step 18 - Rear Assembly Complete

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_174014.jpg" width="300">
</p>

**✓ Checkpoint:** Rear carriage should have belt attached and weights installed.

---

### Section 4: Final Assembly

#### Step 19 - Install Top Bearing Plate

**Required:**
- 2x Bearings H.stl
- 2x 608RS bearings (final 2)
- 1x Pulley Plate.stl
- 2x M5 × 30mm screws
- 2x M5 nuts

**Instructions:**
1. Press bearings into Bearings H.stl
2. Mount Pulley Plate.stl to top of 2040 extrusion
3. Secure with screws into T-slots
4. Install horizontal bearings
5. Thread belt through bearings
6. Slide both carriages onto extrusion

<p align="center">
  <img src="https://github.com/HexLions/Threaded-Insert-Press-Open-source/blob/main/IMG/IMG_20230927_174048.jpg" width="300">
</p>

**✓ Checkpoint:** Both carriages should slide smoothly on V-slot.

#### Step 20 - Belt Tensioning and Final Adjustments

**Instructions:**

1. **Tension Belt:**
   - Rotate Decentration Post.stl to take up slack
   - Belt should be taut but not extremely tight
   - Both carriages should move smoothly together

2. **Test Movement:**
   - Lift front carriage - rear should descend
   - Lower front carriage - rear should rise
   - No binding or sticking

3. **Adjust if Needed:**
   - If belt sags: Tighten decentration post
   - If movement is rough: Loosen belt slightly
   - If carriages separate: Adjust belt alignment

4. **Final Check:**
   - All bearings rolling smoothly
   - No wobble in vertical axis
   - Belt tracking centered

**✓ Final Checkpoint:** Press should operate smoothly with balanced weight.

---

## 🎯 Usage Guide

### Installing Threaded Inserts

#### Preparation

1. **Heat Soldering Iron:**
   - Set to 200-230°C for PLA
   - Set to 240-260°C for PETG/ABS
   - Allow 5 minutes to stabilize

2. **Prepare 3D Printed Part:**
   - Drill or print pilot hole slightly smaller than insert outer diameter
   - Clean any stringing or debris
   - Place part on stable, heat-resistant surface

3. **Install Soldering Iron:**
   - Slide iron into grip
   - Ensure tip points straight down
   - Tighten grip screws firmly

#### Installation Process

1. **Position Insert:**
   - Place threaded insert on pilot hole
   - Ensure insert is perpendicular to surface
   - Hold part steady

2. **Lower Press:**
   - Gently guide front carriage down
   - Soldering iron tip should contact insert top
   - Let weight of press do the work

3. **Monitor Insertion:**
   - Insert should melt into plastic smoothly
   - Stop when insert is flush or slightly below surface
   - Don't force - add heat if needed

4. **Cool Down:**
   - Lift press
   - Allow insert to cool 10-15 seconds
   - Don't disturb part during cooling

5. **Test:**
   - Try threading a screw
   - Should thread smoothly with no resistance

### Tips for Best Results

**Do's:**
- ✅ Use consistent downward pressure
- ✅ Keep iron perpendicular to surface
- ✅ Let insert cool completely before testing
- ✅ Practice on scrap parts first
- ✅ Clean iron tip regularly

**Don'ts:**
- ❌ Rush the heating process
- ❌ Apply excessive force
- ❌ Move part while insert is hot
- ❌ Overheat (causes plastic deformation)
- ❌ Use undersized pilot holes

### Troubleshooting

#### Insert Won't Go In
- **Cause:** Pilot hole too small
- **Solution:** Increase hole size by 0.1-0.2mm

#### Insert Goes In Crooked
- **Cause:** Uneven pressure or surface
- **Solution:** Ensure part is level, apply even pressure

#### Plastic Deforms Around Insert
- **Cause:** Temperature too high or too slow
- **Solution:** Reduce temperature 10-20°C, work faster

#### Insert Spins in Hole
- **Cause:** Hole too large or not hot enough
- **Solution:** Use smaller hole or increase temperature

## ⚙️ Maintenance

### Regular Maintenance

**After Every 50 Inserts:**
- Clean soldering iron tip
- Check belt tension
- Inspect bearings for smooth operation

**Monthly:**
- Lubricate bearings with light machine oil
- Check all screws for tightness
- Clean V-slot rails with dry cloth

**As Needed:**
- Replace worn bearings (rough/noisy operation)
- Adjust belt tension (stretches over time)
- Replace belt if damaged or frayed

### Common Issues

#### Carriage Binding

**Symptoms:** Rough movement, sticking
**Causes:**
- Debris in V-slot
- Over-tightened bearings
- Misaligned bearings

**Solutions:**
1. Clean V-slot thoroughly
2. Check bearing tightness (should spin freely)
3. Verify bearing alignment

#### Belt Slipping

**Symptoms:** Carriages don't move together
**Causes:**
- Belt too loose
- Belt teeth damaged
- Decentration post loose

**Solutions:**
1. Tighten via decentration post
2. Inspect belt for damage
3. Replace belt if necessary

## 📊 Performance Specifications

### Capabilities

- **Maximum Part Height:** 350mm
- **Insert Sizes:** M2, M3, M4, M5 (with appropriate tips)
- **Precision:** ±0.5mm alignment
- **Cycle Time:** ~10-15 seconds per insert
- **Daily Capacity:** 200+ inserts
- **Operating Temperature:** 150-300°C (iron dependent)

### Build Stats

- **Print Time:** 15-20 hours total
- **Print Cost:** $8-12 (PLA filament)
- **Hardware Cost:** $25-35
- **Total Cost:** $35-50
- **Assembly Time:** 1-2 hours
- **Skill Level:** Intermediate

## 🔄 Customization & Modifications

### Grip Modifications

**Two grip designs included:**
- **Soldering Iron Grip Standard.stl** - For 15-18mm diameter irons
- **Soldering Iron Grip.stl** - For 18-20mm diameter irons

**Custom grip:**
1. Measure your iron's grip diameter
2. Modify STL in CAD software
3. Adjust inner diameter to your iron + 0.5mm clearance

### Height Adjustment

**To change vertical travel:**
1. Replace 2040 extrusion with different length:
   - 300mm for compact build
   - 500mm for larger parts
2. Adjust belt length proportionally

### Weight System

**Customize pressure:**
- **More washers:** Slower descent, gentler insertion
- **Fewer washers:** Faster descent, more force
- **Add custom weights:** 3D print weight holders

## 🤝 Contributing

Contributions welcome! Here's how you can help:

### Ways to Contribute

1. **Design Improvements**
   - Submit modified STL files
   - Create alternative grip designs
   - Optimize for different printers

2. **Documentation**
   - Add photos/videos of your build
   - Translate to other languages
   - Share tips and tricks

3. **Testing**
   - Test with different insert sizes
   - Try various materials (Nylon, ASA, etc.)
   - Report compatibility issues

4. **Feature Requests**
   - Suggest new features
   - Request specialized adapters
   - Propose alternate designs

### Submission Process

```bash
git checkout -b feature/YourFeature
git commit -m 'Add YourFeature'
git push origin feature/YourFeature
```

Then open a Pull Request!

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

**You are free to:**
- ✅ Use for personal or commercial projects
- ✅ Modify and redistribute
- ✅ Sell prints or kits
- ✅ Create derivatives

**Attribution appreciated but not required!**

## 👤 Author

**HexLions**

*Just a typical nerd who likes making things*

- GitHub: [@HexLions](https://github.com/HexLions)
- Project Link: [https://github.com/HexLions/Threaded-Insert-Press-Open-source](https://github.com/HexLions/Threaded-Insert-Press-Open-source)

## 🙏 Acknowledgments

- V-slot extrusion system for smooth linear motion
- 608 bearing standard for ubiquitous availability
- GT2 belt system for reliable power transmission
- All makers who inspired this design
- Community feedback for improvements

## 💬 Support & Community

- **Issues:** Found a problem? [Report it](https://github.com/HexLions/Threaded-Insert-Press-Open-source/issues)
- **Discussions:** Questions? [Ask here](https://github.com/HexLions/Threaded-Insert-Press-Open-source/discussions)
- **Pull Requests:** Improvements welcome!

## 📚 Additional Resources

### Recommended Reading
- [Heat-Set Inserts Guide](https://www.cnckitchen.com/blog/heat-set-inserts) - CNC Kitchen
- [Best Practices for Inserts](https://www.youtube.com/watch?v=cyof7fYFcuc) - YouTube Tutorial
- [Insert Selection Guide](https://www.mcmaster.com) - McMaster-Carr

### Where to Buy Components
- **Extrusion:** [OpenBuilds](https://openbuildspartstore.com/), Amazon
- **Bearings:** Local hardware store, Amazon, AliExpress
- **Belt:** [Amazon GT2 Belt](https://www.amazon.com/s?k=gt2+belt)
- **Fasteners:** McMaster-Carr, local hardware store

## ⭐ Star History

If you find this project useful, please consider giving it a star! ⭐

It helps others discover this tool and motivates continued development.

---

**Made with ❤️ for the Maker Community**

*Happy Building!* 🔧
