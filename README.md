# odoo_hotel_management
Gestión de establecimientos turísticos, basado en Roomdoo pero con una integración completa en el entorno de Odoo.
Hotel/
├── __init__.py
├── __manifest__.py

├── models/
│   ├── __init__.py
│   ├── reserva.py           # /Modulos_Funcionales/reservas
│   ├── facturacion.py       # /Modulos_Funcionales/facturación
│   ├── limpieza.py          # /Modulos_Funcionales/limpieza
│   ├── ingresos.py          # /Modulos_Funcionales/ingresos (revenue management)
│   ├── informes.py          # /Modulos_Funcionales/informes
│   ├── gestion_canales.py   # /Modulos_Funcionales/gestión_canales
│   ├── inventario.py        # /Modulos_Funcionales/gestión_inventario
│   ├── configuracion.py     # /Configuración (ajustes personalizados)
│   ├── seguridad.py         # /Seguridad (implementaciones básicas)
│   ├── integracion_pos.py   # /Integraciones/POS
│   ├── integracion_iot.py   # /Integraciones/IoT
│   ├── integracion_vr.py    # /Integraciones/VR
│   └── integracion_otros.py # /Integraciones/otros

├── controllers/
│   ├── __init__.py
│   ├── api_controller.py    # /Comunicaciones/APIs (endpoints REST, seguridad)

├── views/
│   ├── reserva_views.xml
│   ├── facturacion_views.xml
│   ├── limpieza_views.xml
│   ├── ingresos_views.xml
│   ├── informes_views.xml
│   ├── gestion_canales_views.xml
│   ├── inventario_views.xml
│   ├── configuracion_views.xml
│   ├── seguridad_views.xml
│   ├── integracion_pos_views.xml
│   ├── integracion_iot_views.xml
│   ├── integracion_vr_views.xml
│   ├── integracion_otros_views.xml
│   └── menu.xml             # menú general para navegar módulos

├── security/
│   ├── ir.model.access.csv  # permisos de acceso
│   ├── pms_security.xml     # reglas de seguridad y grupos de usuarios

├── data/
│   ├── pms_data.xml         # datos básicos iniciales, tipos, estados, etc.
│   ├── api_docs.xml         # documentación API si la expones internamente
│   └── email_templates.xml  # plantillas de emails para reservas, facturas...

├── reports/
│   ├── reserva_report.xml
│   ├── facturacion_report.xml
│   └── informes_report.xml

├── static/
│   └── description/
│       └── icon.png         # icono del módulo

├── docs/
│   ├── manual_usuario.md    # /Documentación/manual de usuario
│   ├── api_documentacion.md # /Documentación/API
│   └── guias_integracion.md # /Documentación/Integraciones

└── tests/
    ├── __init__.py
    ├── test_reserva.py
    ├── test_facturacion.py
    ├── test_limpieza.py
    ├── test_ingresos.py
    ├── test_informes.py
    ├── test_gestion_canales.py
    ├── test_inventario.py
    ├── test_configuracion.py
    ├── test_seguridad.py
    ├── test_integracion_pos.py
    ├── test_integracion_iot.py
    ├── test_reserva.py
    ├── test_facturacion.py
    └── test_seguridad.py



