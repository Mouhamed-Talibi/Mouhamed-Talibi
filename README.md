{
    "hero": {
        "name": "Mouhamed Talibi",
        "nationality": "Morocco",
        "profession": "PHP and Laravel Developer",
        "description": "Passionate Backend Developer with a strong focus on building scalable and efficient systems. I specialize in PHP and Laravel framework development, creating robust APIs and database architectures. Always eager to learn new technologies and enhance my skills in backend development. I believe in turning complex challenges into elegant, maintainable solutions."
    },
    
    "techStack": {
        "backend": [
            {"name": "PHP", "icon": "https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"},
            {"name": "Laravel", "icon": "https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"},
            {"name": "REST API", "icon": "https://img.shields.io/badge/API-FF6C37?style=for-the-badge&logo=postman&logoColor=white"},
            {"name": "MySQL", "icon": "https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"}
        ],
        "frontend": [
            {"name": "HTML5", "icon": "https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"},
            {"name": "CSS3", "icon": "https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"},
            {"name": "Bootstrap", "icon": "https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"}
        ],
        "tools": [
            {"name": "Cmder", "icon": "https://img.shields.io/badge/Cmder-4D4D4D?style=for-the-badge&logo=windows-terminal&logoColor=white"},
            {"name": "VS Code", "icon": "https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"},
            {"name": "XAMPP", "icon": "https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&logo=apache&logoColor=white"},
            {"name": "Git", "icon": "https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"}
        ]
    },
    
    "projects": [
        {
            "name": "Picksouk",
            "type": "E-commerce Platform",
            "url": "https://picksouk.com/",
            "description": "A Moroccan e-commerce platform built with Laravel that provides a seamless online shopping experience. The platform features product catalog management, secure payment integration, user authentication, order processing, and admin dashboard for inventory management. Designed with a focus on performance and user experience for the Moroccan market.",
            "technologies": ["Laravel", "PHP", "MySQL", "Bootstrap", "JavaScript", "Payment APIs"],
            "features": [
                "User authentication & authorization",
                "Product catalog with categories",
                "Shopping cart & checkout system",
                "Order tracking & management",
                "Admin dashboard",
                "Payment gateway integration"
            ],
            "status": "Live"
        }
    ],
    
    "contact": {
        "php_code": "<?php\n\n$contact_info = [\n    'email' => 'talibi.mohamed.mt@gmail.com',\n    'linkedin' => 'https://www.linkedin.com/in/mouhamedtalibi/',\n    'github' => 'https://github.com/Mouhamed-Talibi',\n    'instagram' => 'https://www.instagram.com/dev.talibi_/',\n    'whatsapp' => '0775461072'\n];\n\n// Display contact information\nforeach ($contact_info as $platform => $value) {\n    echo ucfirst($platform) . \": \" . $value . \"\\n\";\n}\n\n?>",
        "formatted": {
            "email": "talibi.mohamed.mt@gmail.com",
            "linkedin": "https://www.linkedin.com/in/mouhamedtalibi/",
            "github": "https://github.com/Mouhamed-Talibi",
            "instagram": "https://www.instagram.com/dev.talibi_/",
            "whatsapp": "0775461072"
        }
    },
    
    "philosophy": [
        "Do it yourself because no one will do it for you.",
        "If it works, optimize it—if it's perfect, it's probably outdated."
    ],
    
    "learningGoals": [
        "Deepening Laravel Expertise: Exploring advanced Eloquent, APIs, and microservices",
        "Scalable Architectures: Learning event-driven design and cloud deployment (AWS/Docker)",
        "Collaboration: Contributing to impactful open-source projects"
    ]
}
