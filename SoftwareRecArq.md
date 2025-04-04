# Programas de Recuperação de Arquivos: Pagos vs Grátis


## Programas Testados:

### Pagos:
- **Disk Drill**
- **EaseUS Data Recovery**
- **Stellar Data Recovery**

### Grátis:
- **Recuva**
- **Photo Rec**

## Metodologia dos Testes:
Foram utilizados três dispositivos de armazenamento diferentes: um HDD Sata, um SSD Sata e um pen drive. Uma pasta com 15 arquivos de diversos tipos (fotos CR3, JPG, MP3, MP4, TXT, e um executável) e tamanhos sendo copiadas para cada dispositivo.

Dois cenários de teste foram realizados:
1. **Recuperação Imediata**: Os arquivos foram apagados, o computador foi utilizado brevemente, e então os programas de restauração foram testados imediatamente.
2. **Recuperação Após Sobrescrita**: Após apagar os arquivos e utilizar o computador brevemente, um arquivo executável grande (850MB)foi copiado para dentro de cada dispositivo, sobrescrevendo potencialmente os arquivos apagados. Em seguida, os programas de restauração foram testados.

## Resultados dos Testes:

| Programa                 | HD (Apagado) | HD (Sobrescrito) | SSD (Apagado) | SSD (Sobrescrito) | Pen Drive (Apagado) | Pen Drive (Sobrescrito) |
|--------------------------|--------------|------------------|---------------|-------------------|---------------------|-------------------------|
| **Disk Drill**            | 15/15        | 15/15            | 0/15          | 0/15              | 15/15               | 3/15                    |
| **EaseUS Data Recovery**  | 15/15        | 15/15            | 0/15          | 0/15              | 15/15               | 0/15                    |
| **Stellar Data Recovery** | 15/15        | 15/15            | 0/15          | 0/15              | 15/15               | 2/15                    |
| **Recuva (Grátis)**       | 15/15        | 15/15            | 0/15          | 0/15              | 15/15               | 11/15                    |
| **Photo Rec (Grátis)**   | 15/15        | 15/15            | 0/15          | 0/15              | 15/15               | 11/15                    |

## Considerações Finais e Ranking:

- **HD**: Todos os programas tiveram 100% de sucesso em ambos os testes no HD.
- **SSD**: Nenhum dos programas conseguiu recuperar arquivos no SSD em ambos os testes. Isso ocorre devido ao recurso de coleta de lixo do Windows em SSDs, que apaga os arquivos marcados como inválidos para liberar espaço. A recuperação em SSDs exige muita agilidade.
- **Pen Drive**: Todos os programas recuperaram 100% dos arquivos no teste de recuperação imediata. No teste após sobrescrita, os programas gratuitos (Recuva e Photo Hack) tiveram melhor desempenho, recuperando 11 dos 15 arquivos, enquanto os pagos tiveram resultados inferiores.

## Outras Considerações sobre os Programas:

| Critério                   | Disk Drill | EaseUS | Stellar | Recuva (Grátis) | Photo Rec (Grátis) |
|----------------------------|------------|--------|---------|-----------------|---------------------|
| **Interface Intuitiva**     | Sim        | Sim    | Sim     | Sim             | Não                 |
| **Pesquisa de Arquivos**    | Sim        | Sim    | Sim     | Não             | Não                 |
| **Scan Rápido**             | Sim        | Sim    | Sim     | Sim             | Não                 |
| **Pré-visualização**        | Sim        | Sim    | Sim     | Não             | Não                 |
| **Compatibilidade SO**      | Windows, macOS | Windows, macOS | Windows, macOS | Windows, macOS | Windows, macOS, Linux |
| **Compatibilidade de Dispositivos** | HDD, SSD, CDs e DVDs e Dispositivos USB. | HDD, SSD, CDs e DVDs e Dispositivos USB. | HDD, SSD, CDs e DVDs e Dispositivos USB e Sistemas RAID | HDD, SSD, CDs e DVDs e Dispositivos USB. | HDD, SSD, CDs e DVDs e Dispositivos USB. |

## Ranking de Eficiência na Recuperação:
1. **Recuva (Grátis)** e **Photo Rec (Grátis)** (Empate)
2. **Disk Drill**
3. **Stellar**
4. **EaseUS**


#### Software utilizados


<a href="https://recuva.softonic.com.br/"> <img src="https://images.icon-icons.com/195/PNG/256/Recuva_23555.png" alt="Descrição da imagem" width="40" height="40" /><a/> <a href="https://www.cgsecurity.org/wiki/TestDisk_Download"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9d/PhotoRec_Logo.svg/1200px-PhotoRec_Logo.svg.png" alt="Descrição da imagem" width="40" height="40" /><a/> <a href="https://www.stellarinfo.com/pt/"><img src="https://images.sftcdn.net/images/t_app-icon-m/p/437f8346-96d6-11e6-917b-00163ed833e7/996603651/stellar-data-recovery-Logo.png" alt="Descrição da imagem" width="40" height="40" /><a/> <a href="https://br.easeus.com/data-recovery-software/data-recovery-wizard-free.html"> <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/EaseUS_Data_Recovery_Wizard_Logo.png" alt="Descrição da imagem" width="40" height="40" /><a/> <a href="https://www.cleverfiles.com/pt/data-recovery-software.html"><img src="https://windowsactivators.org/wp-content/uploads/2022/08/Disk-Drill-Professional.jpg" alt="Descrição da imagem" width="40" height="40" /><a/>
