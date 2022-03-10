# hse_hw2_chip

Для работы была выбрана клеточная линия - IMR-90 и гистоновая метка - H3K4me2:

## Обязательная часть

Сначала сделаем fastqc для 2х реплик + контроль:

`ENCFF103PXQ.fastq`

Тут явно подрезание чтений не повредит

До:
<p float="left">
  <img src="/picture/stat_103_seq.png " width="400" />
  <img src="/picture/quality_103_seq.png" width="400" />
</p>

После:

<p float="left">
  <img src="/picture/stat_103_trim.png " width="400" />
  <img src="/picture/quality_103_trim.png" width="400" />
</p>

`ENCFF925DDM.fastq`

И в этом случае тоже, вот результат.
До:
<p float="left">
  <img src="/picture/stat_649_seq.png " width="400" />
  <img src="/picture/quality_649_seq.png" width="400" />
</p>

После:

<p float="left">
  <img src="/picture/stat_649_trim.png " width="400" />
  <img src="/picture/quality_649_trim.png" width="400" />
</p>

`control`

Здесь тоже сдало гораздо лучше

До:
<p float="left">
  <img src="/picture/stat_control.png " width="400" />
  <img src="/picture/quality_control.png" width="400" />
</p>

После:

<p float="left">
  <img src="/picture/stat_control_trim.png " width="400" />
  <img src="/picture/quality_control_trim.png" width="400" />
</p>

### Выравниваем на 14ю хромосому

<p float="left">
  <img src="/picture/table.png " width="800" />
</p>

Выровнялось не так много, потому что мы выравнивали на 1 хромосому, а не на весь геном.


### Результаты

<p float="left">
  <img src="/picture/venn1.png " width="400" />
  <img src="/picture/venn2.png" width="400" />
</p>

