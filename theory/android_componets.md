# Компоненты из которых состоит Android

*	Ядро 
*	Дерево устройств (Device tree)
*	Проприетарные файлы (blobs) 
*	Библиотеки и приложения 
 
Ядро - “сердце” операционной системы, отвечает за взаимдействие аппаратных и про-граммных частей. В Android используется модифицируемое ядро Linux. 
 
Дерево устройств - описание аппаратного обеспечения на устройстве. Позволяет разнести конфигурации для разных устройств по разным репозиториям. Считав “дерево”, ядро может обращаться к устройству. 
 
Проприетарный код - закрытые куски операционной системы, собственной разработки производителя устройства, которые крайне важны для функционирования устройства. 
 
Библиотеки и приложения - набор предустановленных приложений. Ненужные часто называются “bloatware”.
