# mab-product-card

## Ejemplo

```tsx
import {
  ProductCard,
  ProductImage,
  ProductTitle,
  ProductButtons,
} from 'mab-product-card';

<ProductCard
  product={product}
  initialValues={{
    count: 4,
    maxCount: 10,
  }}
>
  {({ count, maxCount, increaseBy, isMaxCountReached, reset }) => (
    <>
      <ProductImage />
      <ProductTitle />
      <ProductButtons />
    </>
  )}
</ProductCard>
```
