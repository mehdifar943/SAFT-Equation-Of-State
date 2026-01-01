FaraSAFT - Advanced SAFT Thermodynamics Software

https://img.shields.io/badge/Windows-Executable-blue
https://img.shields.io/badge/Version-1.0.0-green
https://img.shields.io/badge/SAFT-Thermodynamics-purple
https://img.shields.io/badge/License-MIT-yellow
https://img.shields.io/badge/No%2520Java%2520Required-Success-brightgreen
🚀 One-Click Installation

FaraSAFT is a standalone Windows executable for advanced thermodynamic calculations using Statistical Associating Fluid Theory (SAFT). No Java installation required!
📥 Quick Download & Installation

    Download FaraSAFT.exe from Releases

    Double-click to run the installer

    Follow the installation wizard

    Launch from Start Menu or Desktop shortcut

That's it! The software is ready to use with all dependencies included.
👨‍🔬 About the Developer

Dr. Mehdi Fattahi
Ph.D. in Physical Chemistry
Tehran, Iran
📧 farashiani943@gmail.com
🔗 GitHub Profile
✨ Key Features
🔬 Three Advanced SAFT Models

    PC-SAFT - Fast calculations for standard fluids

    SAFT-γ-Mie - Group contribution approach

    SAFT-VR-Mie - Highest accuracy for complex fluids

📊 Comprehensive Calculations

    Chemical Potential (μ)

    Helmholtz Free Energy (A)

    Heat Capacities (Cp, Cv)

    Entropy (S)

    Compressibility Factor (Z)

    PVT properties

⚙️ Advanced Capabilities

    Parameter Optimization - Fit to experimental data

    Multiple Algorithms - Nelder-Mead, Simulated Annealing, Newton-Raphson

    Parallel Processing - Speed up calculations

    Association Modeling - Configurable sites

    Mixing Rules - Arithmetic, Geometric, Berthelot means

📖 Complete User Guide
1. Getting Started
text

1. Select SAFT Model (PC-SAFT, SAFT-γ-Mie, or SAFT-VR-Mie)
2. Choose Number of Components (1-4)
3. Select Calculation Type:
   - Thermodynamic Properties: Calculate at specified conditions
   - Optimization: Fit parameters to experimental data
4. Input Data: Manual entry or CSV import

2. Experimental Data Format
text

Pure Component: Density, Temperature, Pressure
Binary Mixture: MoleFraction1, Density, Temperature, Pressure
Ternary Mixture: MoleFraction1, MoleFraction2, Density, Temperature, Pressure

3. PC-SAFT Module Parameters
Parameter	Description	Units
Segment Number (m)	Number of segments	-
Sigma (σ)	Segment diameter	Å
Epsilon/k (ε/k)	Energy parameter	K
4. Association Models

    (1a ; 1d) - 2B model (Water: np=0, nd=2, na=2)

    (2a ; 2d) - 4C model

    (p) - Single bipolar site

    (3p) - Three bipolar sites

Example Configuration:

    Water with (1a ; 1d): np=0, nd=2, na=2

    Water with (2a ; 2d): np=0, nd=1, nd=1, na=1, na=1

5. Calculation Methods

    Newton-Raphson - Fast iterative method

    Nelder-Mead - Direct search (no derivatives)

    Simulated Annealing - Global optimization

    No - Fix value (don't calculate)

6. RMSD Accuracy Metrics

    Total RMSD: Overall accuracy

    Pressure RMSD: Pressure calculation accuracy

    Density RMSD: Density prediction accuracy

    Temperature RMSD: Temperature correlation accuracy

    Mole Fraction RMSD: Mixture composition accuracy

7. Mixing Rules

Dispersive Energy:

    Arithmetic Mean: εij = 0.5 × (1 - kadj,ij) × (εii + εjj)

    Geometric Mean: εij = (1 - kadj,ij) × √(εii × εjj)

    Berthelot Mean: εij = (1 - kadj,ij) × √(εii × εjj) × [√(σiiσjj)/σij]³

Association Energy:

    Arithmetic Mean: Eab,ij = 0.5 × (1 - eadj,ij) × (Eab,ii + Eab,jj)

    Geometric Mean: Eab,ij = (1 - eadj,ij) × √(Eab,ii × Eab,jj)

    Berthelot Mean: Eab,ij = (1 - eadj,ij) × √(Eab,ii × Eab,jj) × [√(σiiσjj)/σij]³

Note: For all rules: σij = 0.5 × (σii + σjj)
8. SAFT-γ-Mie Module

    Group-contribution approach

    Define segment groups (CH3, CH2, OH, etc.)

    Specify molecular composition

    Same mixing rules as PC-SAFT

9. SAFT-VR-Mie Module

    Variable range Mie potential

    Parameters: λr (repulsion), λa (attraction)

    Enhanced accuracy for associating fluids

    Advanced mixing rules

10. Parameter Optimization

Steps:

    Select algorithm (Nelder-Mead or Simulated Annealing)

    Set maximum iterations (1000-5000)

    Enable parallel calculation

    Select parameters to optimize

    Set lower/upper limits

    Start optimization

Parameter Table:

    Parameter Name

    Current Value

    Variable (checkbox)

    Initial Value

    Lower Limit

    Upper Limit

📁 File Structure
text


❓ Frequently Asked Questions
Q: Do I need to install Java?

A: No! FaraSAFT.exe includes everything bundled.
Q: Can I import my experimental data?

A: Yes! Use CSV format with the specified column order.
Q: Which SAFT model should I use?

A:

    PC-SAFT: Simple fluids, fast calculations

    SAFT-γ-Mie: Complex molecules, group contributions

    SAFT-VR-Mie: Highest accuracy, research applications

Q: How long do calculations take?

A:

    PC-SAFT: Seconds to minutes

    SAFT-γ-Mie: Minutes

    SAFT-VR-Mie: Minutes to hours for complex systems

🔄 Update & Maintenance
Automatic Updates

FaraSAFT checks for updates on startup (optional).
Manual Update

    Download latest version from GitHub Releases

    Run new installer (preserves settings)

    Restart application

Uninstallation

    Control Panel → Programs → Uninstall

    Or: Run Uninstall.exe from installation folder

    Optional: Remove user data from %APPDATA%\FaraSAFT\


Academic License

Free for academic and research use. Commercial use requires license.
🔒 Security & Privacy
Data Security

    No internet connectivity required

    All calculations performed locally

    No data collection or telemetry

    Optional update checks


Academic Use Terms

    Free for academic research

    Citation required in publications

    No redistribution for commercial purposes

    Contact author for commercial licensing

🌟 Contributing
For Users

    Report bugs via GitHub Issues

    Suggest new features

    Share example calculations

    Improve documentation

📱 Contact & Links
Primary Contact

Dr. Mehdi Fattahi
📧 farashiani943@gmail.com
🐙 GitHub: mehdifar943
Project Links

    Repository: https://github.com/mehdifar943/SAFT-Equation-Of-State

    Releases: https://github.com/mehdifar943/SAFT-Equation-Of-State/releases

    Issues: https://github.com/mehdifar943/SAFT-Equation-Of-State/issues

    Wiki: https://github.com/mehdifar943/SAFT-Equation-Of-State/wiki

Related Resources

    SAFT Theory: https://en.wikipedia.org/wiki/Statistical_Associating_Fluid_Theory

    Thermodynamics: Standard textbooks and references

    Research Papers: Cited in documentation

🆕 What's New in v1.0.0
Major Features

✅ Three complete SAFT models
✅ Standalone Windows executable
✅ No Java installation required
✅ Parallel processing support
✅ Comprehensive documentation
✅ Association modeling
✅ Multiple mixing rules
Upcoming Features

🔜 Web interface
🔜 Cloud computation
🔜 Mobile companion app
🔜 Extended parameter database
🔜 Additional SAFT variants
🔜 Machine learning integration
Changelog

    v1.0.0 (Initial Release): Complete SAFT implementation

    Future updates: Performance improvements, new features

⭐ Support This Project
Last Updated: 2025
Version: 1.0.0

© 2025 Dr. Mehdi Fattahi. All rights reserved.
