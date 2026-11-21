# Food Cost
Aplicación estática en español para control de costos, insumos, recetas, ventas e inventario.

## Supabase
La URL y la clave publishable están en `supabase-config.js`. Son datos de cliente y no sustituyen las políticas RLS. No publicar claves `service_role` ni `secret`.
El esquema de almacenamiento privado está en `supabase/schema.sql` y ya se aplicó al proyecto Supabase FoodCost.

## Publicación
Render sirve el sitio estático desde la raíz del repositorio. Se usa `index.html` como entrada y `supabase-config.js` como configuración.