# smartinventory-backend
Backend escalable para el sistema Smart Inventory.  
Incluye autenticación, productos, sucursales, movimientos, IA predictiva y arquitectura limpia basada en módulos.

## Tecnologías
- NestJS
- PostgreSQL
- TypeORM
- JWT
- OpenAI API
- AWS

##  Funcionalidades principales
- Autenticación con JWT
- CRUD de productos
- CRUD de sucursales
- Registro de movimientos
- IA de predicción de agotamiento
- Insight diario generado por IA

##  Ejecución
```bash
npm install
npm run start:dev

##  Estructura
src/
modules/
products/
branches/
movements/
ia/
auth/
