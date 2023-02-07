# sylius-commerce-config
Sylius config files for NextJs Commerce

## Adapt your Sylius Config

In your Sylius project 

1. copy the `serialization` folder in your config folder
2. copy the `api_resources` folder in your config folder
3. replace the `index` file in your public folder
4. Stop your Sylius
5. Run this command to clean your cache

```bash
php bin/console cache:clear
```
6. Restart your Sylius
```bash
symfony serve
```
