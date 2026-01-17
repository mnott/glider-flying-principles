# Link Catalog - Current State

## README.md Links

All lesson files are referenced in README.md with:
- Descriptive links in "Complete Topic List"
- Checklist items in "Progress Tracking"
- Navigation structure description

### Current Link Pattern in README:
```markdown
### 1. [Earth and Atmosphere](./lessons/01-earth-and-atmosphere.md)
### 2. [Flow Laws and Speeds](./lessons/02-flow-laws-and-speeds.md)
### 3. [Aerodynamic Forces](./lessons/03-aerodynamic-forces.md)
### 4. [Induced Drag and Wing Geometry](./lessons/04-induced-drag-and-wing-geometry.md)
### 5. [Stalls and Spins](./lessons/05-stalls-and-spins.md)
### 6. [Control Surfaces](./lessons/06-control-surfaces.md)
### 7. [Aircraft Stability](./lessons/07-aircraft-stability.md)
### 8. [Propeller Concepts](./lessons/08-propeller-concepts.md)
```

## Cross-References in Lesson Files

### File 04 Bottom Navigation:
```markdown
**⬅ Previous Lesson:** [Aerodynamic Forces](./03-aerodynamic-forces.md)
**[⬆ Back to Course Overview](../README.md)**
**➡ Next Lesson:** [Stalls and Spins](./05-stalls-and-spins.md)
```

### File 04 Related Topics Section:
```markdown
- **[Aerodynamic Forces](./03-aerodynamic-forces.md)** - Foundation: lift generation creates induced drag
- **[Stalls and Spins](./05-stalls-and-spins.md)** - Wingtip vortices and tip stall behavior
- **[Control Surfaces](./06-control-surfaces.md)** - Adverse yaw from aileron-induced drag
- **[Aircraft Stability](./07-aircraft-stability.md)** - Wing sweep and dihedral for stability
```

### File 05 Bottom Navigation:
```markdown
**⬅ Previous Lesson:** [Induced Drag and Wing Geometry](./04-induced-drag-and-wing-geometry.md)
**[⬆ Back to Course Overview](../README.md)**
**➡ Next Lesson:** [Control Surfaces](./06-control-surfaces.md)
```

### File 05 Related Topics Section:
```markdown
- **[Aerodynamic Forces](./03-aerodynamic-forces.md)** - Foundation: critical angle of attack and Cz,max
- **[Induced Drag and Wing Geometry](./04-induced-drag-and-wing-geometry.md)** - Wing washout prevents tip stall
- **[Control Surfaces](./06-control-surfaces.md)** - Uncoordinated controls can trigger spins
- **[Aircraft Stability](./07-aircraft-stability.md)** - CG position affects stall behavior
```

## Impact of Adding New File(s)

If we add new lesson(s) between 04 and current 05, we need to update:

1. **README.md** - Insert new lessons and renumber subsequent ones
2. **File 04** - Update "Next Lesson" link
3. **New file(s)** - Create with proper navigation
4. **Current 05 → becomes 06 or 07** - Update:
   - Filename
   - H1 title number
   - Previous/Next navigation
   - PDF page reference stays the same (51-54)
5. **All subsequent files** - Renumber and update navigation
6. **Cross-references** - Update any mentions of lesson numbers in "Related Topics"

## Link Update Strategy

Sequential approach:
1. Determine final numbering scheme
2. Rename all affected files
3. Update H1 titles in renamed files
4. Update navigation links in all files
5. Update README.md
6. Spotcheck all links work
