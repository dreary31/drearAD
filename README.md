"# drearAD" 
//1.	Дайте определение понятия репозитория проекта. Опишите классы уровней репозиториев.
//  репозиторий – хранилище информации, связанной с проектом разработки программного продукта в течение всего его жизненного цикла.
//  Классы уровней репозиториев:
//  1.Модельный.Достаточно хорошо может быть описан универсальным языком UML. Данный язык является абстрактным, не привязанным к конкретной модели. Язык дает возможность
//  описать зависимости элементов, иерархию, взаимосвязи, свойства и т. п.
//  2. Программного интерфейса. Разумно описывать с помощью языка определения интерфейсов IDL, обеспечивающего независимость спецификации интерфейсов от их реализации.
//  Уровень играет не только роль промежуточного слоя – его средства также поддерживают распределенное программирование.
//  3. Окружения. Предназначен для хранения информации, разделяемой компонентами и подкомпонентами систем программирования в процессе их работы.
Уровень 1	Репозиторий - обеспечивает логическое деление на группы проектов. Пользователь может выбирать репозитории из меню “Репозиторий/выбрать репозиторий”.
Уровень 2	Проекты - содержат всю информацию в рамках отдельных разработок.
Уровень 3	Конфигурации. Конфигурации являются удобным инструментом для управления версиями выпускаемых моделей или ПО и тому подобных задач.
Уровень 4	Стадии. Служат для управления жизненным циклом проекта.
Уровень 5	Системы. Система является самым нижним уровнем в иерархии проекта и содержит информацию непосредственно о модели: диаграммы в нотации UML, и другие объекты

//2.Расскажите об инструментарии анализа качества программных продуктов в среде разработки
//  При разработке программных продуктов используется в той или иной мере компьютерная поддержка процессов разработки и сопровождения ПП.
//  Это достигается путем представления хотя бы некоторых программных документов ПП (прежде всего, программ)
//  на компьютерных носителях данных (например, на дискетах) и предоставлению в распоряжение разработчика ПП специальных
//  ПП или включенных в состав компьютера специальных устройств, созданных для какой-либо обработки таких документов.
//  В качестве такого специального ПП можно указать компилятор с какого-либо языка программирования. Компилятор избавляет
//  разработчика ПП от необходимости писать программы на языке компьютера, который для разработчика ПП был бы крайне неудобен, -
//  вместо этого он составляет программы на удобном ему языке программирования, которые соответствующий компилятор автоматически переводит на язык компьютера
//  . В качестве специального устройства, поддерживающего процесс разработки ПП, можно указать, например, эмулятор какого-либо языка. Эмулятор позволяет выполнять
//  (интерпретировать) программы на языке, отличном от языка компьютера, поддерживающего разработку ПП, например, на языке компьютера, для которого эта программа предназначена.

//3.	Дайте определение понятия структура проекта. Назовите основные задачи структуризации.
//      Структура проекта – это совокупность взаимосвязанных элементов и процессов проекта, представленных с различной степенью детализации.
//      Основные задачи структуризации проекта:
//–     разбивка проекта на поддающиеся управлению блоки;
//–     распределение ответственности за различные элементы проекта и увязка работ со структурой организации (ресурсами);
//–     точная оценка необходимых затрат – средств, времени и материальных ресурсов;
//–     создание единой базы для планирования, составления смет и контроля за затратами;
//–     увязка работ по проекту с системой ведения бухгалтерских счетов в компании;
//–     переход от общих, не всегда конкретно выражаемых, целей к
//      определенным знаниям, выполняемым подразделениями компании;
//–     определение комплексов работ/подрядов.

//4.	Дайте определение свойств качественного программного обеспечения: мобильность, полезность, машино - независимость.Поясните их назначение.
//Мобильность - способность программного обеспечения работать на различных аппаратных платформах или под управлением различных операционных систем.
//Полезность – способность программного обеспечения быть удобным для практического применения.
//Машино-независимость – способность программного обеспечения выполняться на вычислительной машине тиной конфигурации, чем та, для которой они непосредственно предназначены.

// 5.	Дайте определение понятия структура проекта.Опишите виды и классификацию проектов.

// 6.	Дайте определение свойств качественного программного обеспечения: точность, доступность, модифицируемость.Поясните их назначение.
//Точность — способность программного обеспечения обеспечивать правильные или приемлемые для пользователя результаты и внешние эффекты.
//Доступность – способность программного обеспечения быть открытыми для доступа для всех пользователей или определенного пользователя.
//Модифицируемость – способность программного обеспечения к внесению изменений.

// 7.	Сформулируйте определение интеграции программных модулей.Опишите виды и цели интеграции программных модулей.

// 8.	Перечислите и охарактеризуйте виды тестирования производительности.
//нагрузочное(load)
//стресс(stress)
//    тестирование стабильности(endurance or soak or stability)
//конфигурационное(configuration)
//9.	Дайте определение понятия интеграции. Опишите современные технологии и инструменты интеграции.

//10.	Расскажите о графическом интерфейсе пользователя.Особенности тестирования, требования.

// 11.	Сформулируйте цель и задачи автоматизация бизнес-процессов.Опишите процессы хаотичной автоматизации, автоматизации по участкам, автоматизация по направлениям и комплексной автоматизации деятельности организации.
// 
//12.	Перечислите и поясните принципы отладки программного обеспечения.

// 13.	Опишите процесс выбора и настройки работы системы контроля версий (типов импортируемых файлов, путей, фильтров и др.параметров импорта в репозиторий).

//14.Перечислите и опишите методы оценки качества.

//15.	Опишите процесс разработка модульной структуры проекта (диаграммы модулей).

//16.Дайте определение понятия «Качество продукции», перечислите показатели качества.

//17.	Опишите принцип работы протоколов транспортного уровня. 

//18.	Дайте определение свойств качественного программного обеспечения: надежность, структурированность, эффективность.Поясните их назначение.

//19.	Дайте определение системы управления версиями. Сформулируйте основные принципы организации работы команды в системе контроля версий. 

//20.	Перечислите и охарактеризуйте функциональные виды тестирования.

//21.	Дайте определение понятия проект. Охарактеризуйте состав и структуру коллектива разработчиков, их функции.

//22.	Перечислите и охарактеризуйте связанные с изменениями  виды тестирования.

//23.	Сформулируйте понятие и принципы работы с инструментальными средствами разработки ПО.

//24.	Дайте определение понятий «Отладка», «Локализация Ошибки». Какие виды ошибок существуют? Охарактеризуйте их.

//25.	Опишите инструментальные средства создания Windows-приложений.

//26.	Опишите процесс разработки тестовых модулей проекта для тестирования отдельных модулей.

//27.	Опишите процесс разработка приложений WPF в среде программирования Microsoft Visual Studio.

//28.	Перечислите и охарактеризуйте нефункциональные виды тестирования.

//29.	Расскажите про инструменты разработки программных средств. Перечислите и охарактеризуйте группы инструментов ПС.

//30.	Сформулируйте определение понятия тестирование. Опишите методы и средства организации тестирования.

//31.	Перечислите и охарактеризуйте основные классы инструментальных сред разработки и сопровождения ПС.

//32.	Расскажите о методах проведения тестирования пользовательского интерфейса

//33.	Опишите методы организации коллективной разработки ПО.

//34.	Перечислите и охарактеризуйте методы отладки программного обеспечения.

//35.	Дайте определение понятию отладки программного средства.

//36.	Опишите методы и способы идентификации сбоев и ошибок.


//37.	Дайте определение понятия и опишите особенности разработки программного модуля.

//38.	Опишите инструментальные средства поддержки процесса документирования.

//39.	Опишите процесс тестирования интерфейса пользователя средствами инструментальной среды разработки.

//40.	Дайте определение понятия обработка исключительных ситуаций. Опишите инструменты среды разработки для обработки исключительных ситуаций.

//41.	Опишите методические аспекты проектирования ПО. Общие принципы проектирования систем. 

//42.	Сформулируйте основные этапы документирования результатов тестирования.

//43.	Перечислите стандарты качества программных средств.  

//44.	Опишите процесс выявление ошибок системных компонентов.

//45.	Дайте определение понятия «Качество программного обеспечения». Перечислите критерии оценки качества ПО.

//46.	Перечислите основные средства проектирования интерфейса пользователя и опишите принцип из работы.

//47.	Дайте определение свойств качественного программного обеспечения: понятность, осмысленность, завершенность.Поясните их назначение.

//48.	Дайте определение понятий ручное и автоматизированное тестирование. Расскажите об их преимуществах и недостатках.

//﻿using System;
//using System.Collections.Generic;
//using System.Linq;
//using System.Text;
//using System.Threading.Tasks;
//using Bakery.DB;

//namespace Bakery.ClassHelper
//{
//    public class EFClass
//    {
//        public static DB.BakeryGribovPolypanEntities Context { get; } = new DB.BakeryGribovPolypanEntities();

//    }
//}






////using System;
//using System.Collections.Generic;
//using System.Linq;
//using System.Text;
//using System.Threading.Tasks;
//using System.Windows;
//using System.Windows.Controls;
//using System.Windows.Data;
//using System.Windows.Documents;
//using System.Windows.Input;
//using System.Windows.Media;
//using System.Windows.Media.Imaging;
//using System.Windows.Shapes;
//using static Bakery.ClassHelper.EFClass;
//using Bakery.Windows;

//using Bakery.DB;
//using Microsoft.Win32;
//using System.IO;

//namespace Bakery.Windows
//{
//    public partial class AddEditProductWindow : Window
//    {

//        private string pathPhoto = null;

//        private bool isEdit = false;

//        private Product editProduct;


//        public AddEditProductWindow()
//        {
//            InitializeComponent();

//            CMBTypeProduct.ItemsSource = Context.ProductType.ToList();
//            CMBTypeProduct.SelectedIndex = 0;
//            CMBTypeProduct.DisplayMemberPath = "TypeName";
//            tb1.Text = "Добавление товара";
//            BtnAddEdit.Content = "Добавить";
//        }

//        public AddEditProductWindow(Product product)
//        {
//            InitializeComponent();

//            editProduct = product;

//            CMBTypeProduct.ItemsSource = Context.ProductType.ToList();
//            CMBTypeProduct.SelectedIndex = 0;
//            CMBTypeProduct.DisplayMemberPath = "TypeName";

//            TbNameProduct.Text = product.Title.ToString();
//            TbDisc.Text = product.Description.ToString();
//            TbCost.Text = product.Cost.ToString();
//            check.IsChecked = product.Active;
//            CMBTypeProduct.SelectedItem = Context.ProductType.Where(i => i.id == product.ProductTypeid).FirstOrDefault();
//            if (product.ImagePath != null)
//            {

//                using (MemoryStream stream = new MemoryStream(product.ImagePath))
//                {
//                    BitmapImage bitmapImage = new BitmapImage();
//                    bitmapImage.BeginInit();
//                    bitmapImage.CacheOption = BitmapCacheOption.OnLoad;
//                    bitmapImage.CreateOptions = BitmapCreateOptions.PreservePixelFormat;
//                    bitmapImage.StreamSource = stream;
//                    bitmapImage.EndInit();
//                    ImgProduct.Source = bitmapImage;

//                }
//            }
//            isEdit = true;



//        }

//        private void BtnAddEdit_Click(object sender, RoutedEventArgs e)
//        {

//            if (isEdit)
//            {


//                editProduct.Title = TbNameProduct.Text;
//                editProduct.Description = TbDisc.Text;
//                editProduct.Cost = Convert.ToDecimal(TbCost.Text);
//                editProduct.ProductTypeid = (CMBTypeProduct.SelectedItem as ProductType).id;
//                editProduct.Active = check.IsChecked;
//                if (pathPhoto != null)
//                {
//                    editProduct.ImagePath = File.ReadAllBytes(pathPhoto);
//                }
//                Context.SaveChanges();

//            }
//            else
//            {
//                Product product = new Product();
//                product.Title = TbNameProduct.Text;
//                product.Description = TbDisc.Text;
//                product.Cost = Convert.ToDecimal(TbCost.Text);
//                product.ProductTypeid = (CMBTypeProduct.SelectedItem as ProductType).id;
//                product.Active = check.IsChecked;
//                if (pathPhoto != null)
//                {
//                    product.ImagePath = File.ReadAllBytes(pathPhoto);
//                }

//                Context.Product.Add(product);

//                Context.SaveChanges();
//            }
//            ProductListWindow productlistWindow = new ProductListWindow();

//            this.Close();

//        }

//        private void BtnChooseImage_Click(object sender, RoutedEventArgs e)
//        {
//            OpenFileDialog openFileDialog = new OpenFileDialog();
//            if (openFileDialog.ShowDialog() == true)
//            {
//                ImgProduct.Source = new BitmapImage(new Uri(openFileDialog.FileName));
//                pathPhoto = openFileDialog.FileName;
//            }
//        }


//    }
//}




























////<Window x:Class="Bakery.Windows.ProductListWindow"
//xmlns = "http://schemas.microsoft.com/winfx/2006/xaml/presentation"
//        xmlns: x = "http://schemas.microsoft.com/winfx/2006/xaml"
//        xmlns: d = "http://schemas.microsoft.com/expression/blend/2008"
//        xmlns: mc = "http://schemas.openxmlformats.org/markup-compatibility/2006"
//        xmlns: local = "clr-namespace:Bakery.Windows"
//        mc: Ignorable = "d"
//        Title = "ProductListWindow" Height = "800" Width = "1200" >
    
//        < Grid Background = "LightSalmon" >
     
//             < Grid.RowDefinitions >
     
//                 < RowDefinition Height = "40" />
      
//                  < RowDefinition Height = "40" />
       
//                   < RowDefinition Height = "*" />
        
//                    < RowDefinition Height = "40" />
         
//                 </ Grid.RowDefinitions >
         
//                 < WrapPanel Grid.Row = "1" >
          
//                      < TextBlock Text = "Поиск:"
//                       FontSize = "18"
//                       Margin = "20 0 10 0" >
//            </ TextBlock >
//            < TextBox x: Name = "TbSearch"
//                     FontSize = "18"
//                     Width = "200"
//                     VerticalContentAlignment = "Center"
//                     TextChanged = "TbSearch_TextChanged" >

//            </ TextBox >
//            < TextBlock Text = "Сортировка:"
//                       FontSize = "18"
//                       Margin = "20 0 10 0" />

//            < ComboBox x: Name = "CmbSort"
//                      FontSize = "18"
//                      Width = "200" SelectionChanged = "CmbSort_SelectionChanged"
//                        />
  
//              < TextBlock Text = "Все товары:"
//                       FontSize = "18"
//                       Margin = "20 0 0 0"
//                       />
//            < CheckBox x: Name = "allcheck" VerticalAlignment = "Center" Checked = "allcheck_Checked_2" Unchecked = "Allcheck_UnChecked" ></ CheckBox >
        
//                    < TextBlock Text = "Фильтр:"
//                       FontSize = "18"
//                       Margin = "20 0 10 0" />
//            < ComboBox x: Name = "CmbFilter"
//                      FontSize = "18"
//                      Width = "200" SelectionChanged = "CmbFilter_SelectionChanged"
//                        />
  


//          </ WrapPanel >
  
//          < TextBlock Text = "Список товаров"
//                       FontSize = "25"
//                       TextAlignment = "Center"
//                       Foreground = "Black" />

//        < ListView Grid.Row = "2"
//                  x: Name = "LvProduct"
//                  Margin = "5"
//                  d: ItemsSource = "{d:SampleData ItemCount=5}"
//                  ScrollViewer.HorizontalScrollBarVisibility = "Disabled" Background = "LightSalmon" >
  
//              < ListView.ItemsPanel >
  
//                  < ItemsPanelTemplate >
  
//                      < WrapPanel />
  
//                  </ ItemsPanelTemplate >
  
//              </ ListView.ItemsPanel >
  

//              < ListView.ItemTemplate >
  
//                  < DataTemplate >
  
//                      < Border Width = "150"
//                            Height = "290"
//                            BorderThickness = "1"
//                            BorderBrush = "Red"
//                            Margin = "8"
//                            >
//                        < StackPanel >
//                            < Image Height = "150"
//                                   Width = "120"
//                                   Margin = "0 8 0 0" >
//                                < Image.Source >
//                                    < Binding Path = "ImagePath" >
 
//                                         < Binding.TargetNullValue >
 
//                                             < ImageSource >/ Res / shum.png </ ImageSource >
 
//                                         </ Binding.TargetNullValue >
 
//                                     </ Binding >
 
//                                 </ Image.Source >
 

//                             </ Image >
 

//                             < TextBlock Text = "{Binding Title}"
//                                       FontSize = "14"
//                                       Margin = "10 0 0 0" />
//                            < TextBlock Text = "{Binding ProductType.TypeName}"
//                                       FontSize = "14"
//                                       Margin = "10 0 0 0" />
//                            < WrapPanel Margin = "10 0 0 0" >
 
//                                 < TextBlock Text = "Цена:"
//                                       FontSize = "14"
//                                       />
//                                < TextBlock Text = "{Binding Cost}"
//                                       FontSize = "14"
//                                       />
//                                < TextBlock Text = "₽"
//                                       FontSize = "14"
//                                       />
//                            </ WrapPanel >
//                            < WrapPanel Margin = "10 0 0 0" >
 
//                                 < TextBlock Text = "Количество:"
//                                       FontSize = "14"
//                                       />
//                                < TextBlock Text = "{Binding Quantity}"
//                                       FontSize = "14"
//                                       />
//                            </ WrapPanel >


//                            < WrapPanel HorizontalAlignment = "Center" >
 
//                                 < Button x: Name = "BtnEditProduct"


//                                    Height = "30"
//                                    Width = "30"
//                                    Margin = "0 10 30 0"
//                                    Background = "{x:Null}"
//                                    BorderThickness = "0"
//                                    Click = "BtnEditProduct_Click" >
//                                    < Image Source = "/res/edit.png" x: Name = "editimage" ></ Image >
    
//                                    </ Button >
    

//                                    < Button x: Name = "BtnAddToCartProduct"
//                                    Height = "30"
//                                    Width = "30"
//                                    Margin = "30 10 0 0"
//                                    Background = "{x:Null}"
//                                    BorderThickness = "0"
//                                        Click = "BtnAddToCartProduct_Click" >
//                                    < Image Source = "/res/cart.png" x: Name = "cartimage" ></ Image >
    

//                                    </ Button >
    
//                                </ WrapPanel >
    
//                            </ StackPanel >
    
//                        </ Border >
    

//                    </ DataTemplate >
    
//                </ ListView.ItemTemplate >
    

//            </ ListView >
    
//            < Image x: Name = "ImgCart"
//               Grid.Row = "1"
//               HorizontalAlignment = "Right"
//               Width = "30"
//               Height = "30"
//               Source = "/Res/cart.png"
//               Margin = "30 0" MouseLeftButtonUp = "ImgCart_MouseLeftButtonUp" />
  

//          < Button x: Name = "BtnAddProduct"
//                Content = "Добавить"
//                Grid.Row = "3"
//                Width = "70"
//                HorizontalAlignment = "Right"
//                Click = "BtnAddProduct_Click"
//                Foreground = "Black" Background = "Orange" BorderBrush = "Red" />
    
//            < Button x: Name = "Btnexit"
//                Content = "Назад"
//                Grid.Row = "3"
//                Width = "70"
//                HorizontalAlignment = "Left"
//                Foreground = "Black" Background = "Orange" BorderBrush = "Red" Click = "Btnexit_Click" />
      
//          </ Grid >
//      </ Window >






















////using System;
//using System.Collections.Generic;
//using System.Linq;
//using System.Text;
//using System.Threading.Tasks;
//using System.Windows;
//using System.Windows.Controls;
//using System.Windows.Data;
//using System.Windows.Documents;
//using System.Windows.Input;
//using System.Windows.Media;
//using System.Windows.Media.Imaging;
//using System.Windows.Shapes;
//using Bakery.ClassHelper;
//using static Bakery.ClassHelper.EFClass;
//using Bakery.Windows;
//using Bakery.DB;
//using System.Xml;
//using System.Security.Cryptography.X509Certificates;

//namespace Bakery.Windows
//{
//    /// <summary>
//    /// Логика взаимодействия для ProductListWindow.xaml
//    /// </summary>
//    public partial class ProductListWindow : Window
//    {
//        List<string> listSort = new List<string>()
//        {
//            "По умолчанию",
//            "По имени (по возрастанию)",
//            "По имени (по убыванию)",
//            "По типу (по возрастанию)",
//            "По типу (по убыванию)",
//            "По цене (по возрастанию)",
//            "По цене (по убыванию)",

//        };
//        List<string> listFilter = new List<string>()
//        {
//            "По умолчанию",
//            "Напитки",
//            "Выпечка",
//            "Торты"
//        };
//        public ProductListWindow()
//        {
//            InitializeComponent();
//            CmbSort.ItemsSource = listSort;
//            CmbSort.SelectedIndex = 0;
//            CmbFilter.ItemsSource = listFilter;
//            CmbFilter.SelectedIndex = 0;
//            GetListProduct();
//            if (userlog.UserDataClass.user.roleid == 3)
//            {
//                BtnAddProduct.Visibility = Visibility.Hidden;
//            }
//        }
//        private void GetListProduct()
//        {
//            List<Product> products = new List<Product>();
//            products = Context.Product.ToList();

//            // поиск, сортировка, фильтрация

//            bool a = (bool)allcheck.IsChecked;
//            if (a == false)
//            {
//                string x = "true";
//                products = products.Where(i => i.Active.ToString().ToLower().Contains(x.ToLower())).ToList();
//            }



//            // поиск
//            products = products.Where(i => i.Title.ToLower().Contains(TbSearch.Text.ToLower())).ToList();
//            // сортировка
//            var selectedIndexCmb = CmbSort.SelectedIndex;
//            switch (selectedIndexCmb)
//            {
//                case 0:
//                    products = products.OrderBy(i => i.ProductTypeid).ToList();
//                    break;

//                case 1:
//                    products = products.OrderBy(i => i.Title.ToLower()).ToList();
//                    break;

//                case 2:
//                    products = products.OrderByDescending(i => i.Title.ToLower()).ToList();
//                    break;
//                case 3:
//                    products = products.OrderBy(i => i.ProductType.TypeName.ToLower()).ToList();
//                    break;
//                case 4:
//                    products = products.OrderByDescending(i => i.ProductType.TypeName.ToLower()).ToList();
//                    break;
//                case 5:
//                    products = products.OrderBy(i => i.Cost).ToList();
//                    break;
//                case 6:
//                    products = products.OrderByDescending(i => i.Cost).ToList();
//                    break;
//                default:
//                    break;

//            }
//            // фильтрация
//            var selectedIndexCmb2 = CmbFilter.SelectedIndex;
//            switch (selectedIndexCmb2)
//            {
//                case 1:
//                    products = products.Where(i => i.ProductType.TypeName.ToLower().Contains("Напитки".ToLower())).ToList();
//                    break;
//                case 2:
//                    products = products.Where(i => i.ProductType.TypeName.ToLower().Contains("Выпечка".ToLower())).ToList();
//                    break;
//                case 3:
//                    products = products.Where(i => i.ProductType.TypeName.ToLower().Contains("Торты".ToLower())).ToList();
//                    break;
//                default:
//                    break;

//            }



//            // вывод итгового списка
//            LvProduct.ItemsSource = products;

//        }

//        private void Allcheck_Checked(object sender, RoutedEventArgs e)
//        {
//            throw new NotImplementedException();
//        }

//        private void BtnAddProduct_Click(object sender, RoutedEventArgs e)
//        {
//            AddEditProductWindow addEditProductWindow = new AddEditProductWindow();
//            addEditProductWindow.ShowDialog();

//        }
//        private void BtnEditProduct_Click(object sender, RoutedEventArgs e)
//        {
//            if (userlog.UserDataClass.user.roleid == 3)
//            {

//            }
//            else
//            {
//                var button = sender as Button;
//                if (button == null)
//                {
//                    return;
//                }
//                var product = button.DataContext as Product;

//                AddEditProductWindow editProductWindow = new AddEditProductWindow(product);
//                editProductWindow.ShowDialog();

//                GetListProduct();
//            }
//        }

//        private void TbSearch_TextChanged(object sender, TextChangedEventArgs e)
//        {
//            GetListProduct();
//        }
//        private void CmbSort_SelectionChanged(object sender, SelectionChangedEventArgs e)
//        {
//            GetListProduct();
//        }

//        private void Allcheck_UnChecked(object sender, RoutedEventArgs e)
//        {
//            GetListProduct();
//        }

//        private void allcheck_Checked_2(object sender, RoutedEventArgs e)
//        {
//            GetListProduct();
//        }
//        public int m = 0;

//        private void CmbFilter_SelectionChanged(object sender, SelectionChangedEventArgs e)
//        {
//            GetListProduct();

//        }
//        //корзина
//        private void BtnAddToCartProduct_Click(object sender, RoutedEventArgs e)
//        {
//            var button = sender as Button;
//            if (button == null)
//            {
//                return;
//            }

//            var product = button.DataContext as Product;
//            bool m = (bool)product.Active;
//            if (m == true)
//            {
//                CartProductClass.products.Add(product);
//                product.Quantity = product.Quantity - 1;
//                int z = Convert.ToInt32(product.Quantity);
//                if (z == 0)
//                {
//                    product.Active = false;
//                }
//            }
//            GetListProduct();
//        }

//        private void ImgCart_MouseLeftButtonUp(object sender, MouseButtonEventArgs e)
//        {
//            CartWindow cartProductWindow = new CartWindow();
//            cartProductWindow.Show();
//            this.Close();

//        }

//        private void Btnexit_Click(object sender, RoutedEventArgs e)
//        {
//            MainWindow mainWindow = new MainWindow();
//            mainWindow.Show();
//            this.Close();
//        }
//    }
//}
