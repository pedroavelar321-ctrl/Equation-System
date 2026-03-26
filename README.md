# Equation-System
Sistema de Resolución de Ecuaciones

## Descripción
Equation-System es una herramienta para resolver sistemas de ecuaciones lineales y no lineales de manera rápida y eficiente.

## Características
- Resolución de sistemas de ecuaciones lineales
- Interfaz intuitiva y fácil de usar
- Visualización de resultados

## Requisitos
- Python 3.7 o superior
- Librerías adicionales (ver `requirements.txt`)

## Instalación
1. Clona el repositorio:
```bash
git clone https://github.com/usuario/Equation-System.git
```

2. Navega al directorio del proyecto:
```bash
cd Equation-System
```

3. Instala las dependencias:
```bash
pip install -r requirements.txt
```

## Uso
```bash
python main.py
```

## Ejemplos
### Resolver un sistema lineal
```
2x + 3y = 8
4x - y = 5
```

## Estructura del Proyecto
```
Equation-System/
├── main.py              # Archivo principal
├── solver.py            # Módulo de resolución
├── utils.py             # Utilidades
├── requirements.txt     # Dependencias
├── tests/               # Pruebas unitarias
└── README.md            # Este archivo
```

## Métodos Soportados
- **Regla de Cramer**: para sistemas determinados


## Documentación API
Para más información sobre las funciones disponibles, consulta el archivo `docs/API.md`

## Contribuir
Las contribuciones son bienvenidas. Por favor:
1. Fork el proyecto
2. Crea una rama para tu nueva característica (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## Licencia
Este proyecto está bajo la licencia GNU v3. Ver el archivo `LICENSE` para más detalles.

## Autor
Equipo de Desarrollo

## Contacto
Para preguntas o sugerencias, abre un issue en el repositorio o contáctanos en: pedroavelar321@gmail.com

## Changelog
### Versión 1.0.0
- Lanzamiento inicial
- Soporte para sistemas lineales
