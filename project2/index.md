# Pesquisas em Turbinas Eólicas

[Início](/) • [IDS IoT com KANs](/project1/) • [Turbinas Eólicas](/project2/)

Este projeto explora modelos e simulações para análise do desempenho de turbinas eólicas.

Constantes físicas usadas:
- Densidade do ar: ρ = 1.20 kg/m³  
- Raio do rotor: R = 41 m  
- Área varrida: A = 5.281 m²

 [Artigo / referência](https://arxiv.org/abs/2307.14675)  
[Códigos e simulações](https://github.com/alfonsogijon/WindTurbines_PINNs)
### Nossa Abordagem: Identificação de Parâmetros com KANs e Destilação Simbólica

Com base nos modelos físicos anteriores, desenvolvemos uma nova arquitetura utilizando **Kolmogorov-Arnold Networks (KANs)** para a identificação de parâmetros operacionais a partir de dados industriais SCADA. 

O modelo realiza uma destilação simbólica, transformando a rede neural em equações matemáticas explícitas (closed-form expressions) com alta precisão ($R^2 > 0.999$) e total explicabilidade física.

* **Artigo Aceito (BRACIS 2026):** *Wind Turbine Parameter Identification through Kolmogorov-Arnold Networks and Symbolic Distillation*
* **Autores:** Natalia Emelianova, Ronaldo C. Prati (UFABC)
* **Códigos do nosso modelo:** `[Link para os seus notebooks, ex: ./notebooks/]`

#### Citação (BibTeX)
```bibtex
@inproceedings{emelianova2026wind,
  title={Wind Turbine Parameter Identification through Kolmogorov-Arnold Networks and Symbolic Distillation},
  author={Emelianova, Natalia and Prati, Ronaldo C.},
  booktitle={Proceedings of the 36th Brazilian Conference on Intelligent Systems (BRACIS 2026)},
  series={Lecture Notes in Computer Science},
  year={2026},
  publisher={Springer}
}
