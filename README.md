# NHL-Product-Card

Este es un paquete de pruebas de despliegue en NPM. Proveniente del curso de React PRO, (Fernando Herrera a traves de Udemy)

### Nahuel Montes de Oca

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'nhl-product-card'
```

```
<ProductCard 
    product={ product }
    initialValues={{
        count: 6,
        maxCount: 10,
    }}
>
    {
        ({ reset, count, isMaxCountReached, maxCount, increaseBy  }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```

