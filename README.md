# TOUCH
попытка использовать touchID
сначала была бага 
но после добавлени] в build.gradle 
implementation 'com.android.support:recyclerview-v7:26.1.0'
все заработало

RecyclerView – это компонент пользовательского интерфейса, который позволяет нам создавать прокручиваемый список. Он был представлен в Android Lollipop, и это своего рода ListView2.

Если у нас есть возможность, то мы должны использовать его вместо ListView, потому что он заставляет нас использовать более эффективный способ реализации списка и разделяет зоны ответственности между классами. Чтобы реализовать RecyclerView, мы должны создать следующие компоненты:

RecyclerView, который мы должны добавить в layout нашего экрана;
layout для каждой строки списка;
адаптер, который содержит данные и связывает их со списком.
