# generamba-catalog

It's a shared catalog of templates for [Generamba](https://github.com/strongself/Generamba) code generator.

## Usage

1. Add templates to `Rambafile` .

```yaml:Rambafile
### Templates
catalogs:
- 'https://github.com/0x0c/generamba-catalog'
templates:
- {name: 0x0c_viper}
```

2. Run `generamba template install` .

3. Run `generamba gen [Module name] [Tempalate name]` .

## Templates

- [0x0c_viper](https://github.com/0x0c/generamba-catalog/blob/main/0x0c_viper/0x0c_viper.rambaspec)

## Acknowledgement

This repo was inspired by https://github.com/uhooi/generamba-catalog
