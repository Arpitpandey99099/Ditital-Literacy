import matplotlib.pyplot as plt

# Data for infographic
categories = {
    "Development": [
        "Python (VS Code / PyCharm)",
        "Circuit Simulator (Proteus / Tinkercad)",
        "Compiler & Debugger"
    ],
    "Collaboration": [
        "Git & GitHub",
        "Google Docs",
        "Slack / Discord"
    ],
    "Security": [
        "Strong Passwords",
        "Two-Factor Authentication (2FA)",
        "Regular Backups",
        "Antivirus Software"
    ]
}

# Create figure
plt.figure(figsize=(10, 8))
plt.axis('off')

# Title
plt.text(0.5, 0.95, "Student Tech Stack Infographic",
         fontsize=18, ha='center', weight='bold')

# Positioning
y_pos = 0.8

# Loop through categories
for category, tools in categories.items():
    plt.text(0.1, y_pos, category,
             fontsize=14, weight='bold')
    y_pos -= 0.05

    for tool in tools:
        plt.text(0.15, y_pos, f"• {tool}",
                 fontsize=12)
        y_pos -= 0.04

    y_pos -= 0.05  # space between sections

# Save infographic
plt.savefig("tech_stack_infographic.png", bbox_inches='tight')

# Show output
plt.show()
