# PI-Product-Card

Este es un paquete de pruebas de despliegue en NPM.

### Pablo Ibarra

## Ejemplo
```
import { ProductImage, ProductTitle, ProductButtons } from 'pi-product-card';
```


```
<ProductCard
  product={ product }
  initialValues={{
    count: 4,
    // maxCount: 10
  }}
>
  {
    ({ reset, count, increaseBy, isMaxCountReached, maxCount }) => (
      <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
      </>
    )
  }
</ProductCard>
```
