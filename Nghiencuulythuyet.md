#Nghiên cứu về cơ sở lý thuyết
##I.	Tổng quan về mạng máy tính
###1.	Khái niệm về mạng máy tính
•	Mạng máy tính là mạng của hai hay nhiều máy tính được nối lại với nhau bằng một đường truyền vật lý theo một kiến trúc nào đó. 
Hay phức tạp hơn đó là hệ thống gồm nhiều mạng đơn giản nối lại với nhau 
Một hệ thống mạng tổng quát  được cấu thành từ 3 thành phần:
 + Đường biên mạng ( Network Edge): Gồm các máy tính (Host) và các chương trình ứng dụng mạng (Network Application) 
+ Đường trục mạng ( Network Core): Gồm các bộ chọn đường (router) đóng vài trò là một mạng trung tâm nối kết các mạng lại với nhau.
 +  Mạng truy cập, đường truyền vật lý (Access Network , physical media): Gồm các đường truyền tải thông tin.
•	Mạng máy tính ra đời xuất phát từ nhu cầu muốn chia sẻ và dùng chung dữ liệu. Nếu không có mạng máy tính thì dữ liệu muốn chia sẻ trên các máy tính độc lập với nhau phải thông qua việc in ấn, sao chép qua usb, cd-rom… điều này gây bất tiện rất lớn đối với người dùng. Để giải quyết khó khăn đó, kết nối những máy tính độc lập lại thành mạng máy tính thì chúng ta sẽ có những ưu điểm sau: 
+  Nhiều người có thể dùng chung một phần mềm tiện ích. 
+  Một nhóm người cùng thực hiện một công việc(ví dụ: làm chung một đồ án, một bài báo cáo nào đó…) thì họ sẽ dùng chung dữ liệu, dùng chung tập tin của công việc đó,trao đổi thông tin với nhau dễ dàng hơn. 
+ Dữ liệu được quản lý tập trung nên an toàn hơn, trao đổi với nhau nhanh chóng, thuận lợn hơn. 
+ Có  thể  dùng  chung  các  thiết  bị  ngoại  vi  đắt  tiền  (máy  in,  máy  vẽ,  máy photocopy,…) 
+ Người dùng trao đổi với nhau qua hộp thư điện tử dễ dàng (Email) và có thể sử dụng như là một công cụ để thông báo tin tức, nội dung của một buổi hợp, thời khóa biểu… 
 An toàn cho dữ liệu và phần mềm vì phần mềm mạng sẽ khóa các tệp khi có những người dùng không đủ quyền truy xuất các tập tin và thư mục đó.
###2.	  Phân loại mạng máy tính
**2.1	 Phân loại theo quy mô khoảng cách của mạng**
Trong cách phân loại này người ta chú ý đến đại lượng Đường kính mạng chỉ khoảng cách của hai máy tính xa nhất trong mạng. Dựa vào đại lượng này người ta có thể phân mạng thành các loại sau:
+   Mạng LAN: Mạng cục bộ LAN (Local Area Network) : là mạng được thiết kế trong phạm vi nhỏ khoảng cách giữa các nút mạng nhỏ hơn 10km. LAN thường được sử dụng trong phạm vi nội bộ cơ quan, xí nghiệp… Lan là một loại mạng quảng bá, sử dụng chung một đường truyền chia sẻ, có sự canh tranh đường truyền. Các LAN được kết nối với nhau thành một WAN (mạng diện rộng).
+	Mạng MAN: Mạng đô thị MAN (Metropolitan Area Network) : là mạng được thiết kế trong phạm vi đô thị, trong một tỉnh thành có bán kính khoảng 100km trở lại. Mạng diện rộng WAN (Wide Area Network) : phạm vi của mạng vượt qua biên giới quốc gia và thậm chí là cả châu lục
+	Mạng GAN: Mạng toàn cầu Gan (Global Area Network) : là mạng được thiết lập trên phạm vi toàn cầu, khắp các châu lục trên trái đất. Thông thường kết nối thông qua mạng viễn thông và vệ tinh.
+	Mạng WLAN (Wireless Local Area Network): là một loại mạng không dây sử dụng công nghệ không dây để kết nối các thiết bị trong một khu vực nhỏ như một văn phòng, một tòa nhà, một nhà hàng hoặc một khu vực công cộng như sân bay hay khách sạn. Mạng WLAN cho phép truyền tải dữ liệu giữa các thiết bị mà không cần sử dụng cáp vật lý.
**2.2  Phân loại theo kỹ thuật truyền tin**
+ Mạng quảng bá (Broadcast Network): Trong hệ thống mạng quảng bá chỉ tồn tại một kênh truyền được chia sẻ cho tất cả máy tính. Khi một máy tính gửi khung dữ liệu, tất cả các máy tính còn lại sẽ nhận được khung dữ liệu đó. Tại một thời điểm chỉ cho phép một máy tính sử dụng đường truyền.
+ Mạng điểm tới điểm (Point-to-Point Network): Trong hệ thống mạng này, các máy tính được nối lại với nhau thành từng cặp. Khung dữ liệu sẽ được gởi đi sẽ được truyền trực tiếp từ máy gởi đến máy nhận hoặc được chuyển tiếp qua nhiều máy trung gian trước khi đến máy tính nhận
**2.3	  Phân loại theo Topology**
-	Mạng hình bus :Tất cả các máy tính được nối lại bằng một dây dẫn (cáp đồng trục).Khi một máy tính truyền tin, tín hiệu sẽ lan truyền đến tất cả các máy tính còn lại.
-	Mạng hình sao: Các máy tính được nối trực tiếp vào một Bộ tập trung nối kết, gọi là  Hub. Dữ liệu được chuyển qua Hub trước khi đến các máy  nhận.
-	Mạng hình vòng: Một thẻ bài (token: một gói tin nhỏ) lần lượt truyền qua các máy tính. Truyền tin theo nguyên tắc: 
          +  Chờ cho đến khi token đến nó và nó sẽ lấy token ra khỏi vòng tròn.
        +  Gửi gói tin của nó đi một vòng qua các máy tính trên đường tròn. 
         + Chờ cho đến khi gói tin quay về  
        + Đưa token trở lại vòng tròn để nút bên cạnh nhận token.
-	Mạng dạng kết hợp (Hybrid Network): là một hệ thống mạng kết hợp nhiều công nghệ và phương pháp truyền tải dữ liệu khác nhau để đáp ứng các yêu cầu và mục tiêu của mạng. Mạng dạng kết hợp sử dụng sự kết hợp của các loại mạng khác nhau như mạng cáp đồng trục, mạng cáp quang, mạng không dây và mạng điện thoại di động để tạo ra một hệ thống mạng toàn diện và linh hoạt
**2.4	 Phân loại theo chức năng**
-	Mô hình Client – Server: Một  hay  nhiều  máy  tính  được  thiết  lập  để  cung  cấp  các  dịch  vụ  như  file server, mail-server, web-server, ftp… Các máy tính này được thiết lập để cung cấp các dịch vụ được gọi là server, còn các máy tính truy cập và sử dụng dịch vụ gọi client
-	Mạng ngang hàng (Peer-to-Peer): Mạng ngang hàng (p2p) là mạng mà trong đó hai hay nhiều máy tính chia sẻ tập tin và truy cập các thiết bị như máy in mà không cần đến máy chủ hay phần mềm máy chủ.
 Nói một cách đơn giản, mạng p2p được tạo ra bởi hai hay nhiều máy tính được kết nối với nhau và chia sẻ tài nguyên mà không phải thông qua một máy chủ dành riêng. Mạng p2p có thể là kết nối tại chỗ – hai máy tính nối với nhau qua cổng USB để truyền tập tin. P2p cũng có thể là cơ sở hạ tầng thường trực kết nối 5-6 máy tính với nhau trong một văn phòng nhỏ bằng cáp đồng.
 Hay nó cũng có thể là một mạng có quy mô lớn hơn nhiều, dùng các giao thức và ứng dụng đặc biệt để thiết lập những mối quan hệ trực tiếp giữa người dùng trên internet.
###3.	Mô hình OSI
**3.1	 Giới thiệu mô hình OSI**
•	Lý do hình thành: Sự gia tăng mạnh mẽ về số lượng và kích thước mạng dẫn đến hiện tượng bất tương thích giữa các mạng.
•	Ưu điểm của mô hình OSI:
     -	Giảm độ phức tạp
    -	Chuẩn hóa các giao tiếp
    -	Đảm bảo liên kết hoạt động
    -	Đơn giản việc dạy và học


![example](mohinhOSI1.jpg)








**3.2	 Chức năng của mỗi tầng trong mô hình OSI**


![example](mohinhOSI2.jpg)
	



Mô hình tham chiếu OSI được chia thành bảy lớp với các chức năng sau: 
*1. Tầng vật lý – Physical player:* 
- Điều khiển việc truyền tải thật sự các bit trên đường truyền vật lý. 
- Định nghĩa các tín hiệu điện, trạng thái đường truyền, phương pháp mã hóa dữ liệu, các loại đầu nối được sử dụng. 
*2. Tầng liên kết dữ liệu – Data link layer:* 
-  Đảm bảo truyền tải các khung dữ liệu (frame) giữa hai máy tính có đường truyền vật lý nối trực tiếp với nhau. 
- Cài đặt cơ chế phát hiện và xử lý lỗi dữ liệu nhận.
 *3. Tầng mạng – Network layer:*
- Đảm bảo việc truyền tải các gói tin (packet) có thể truyền từ máy tính này đến  máy  tính  kia  cho  dù  không  có  đường  truyền  vật  lý  trực  tiếp  giữa chúng.
- Nó  nhận  nhiệm vụ  tìm  đường  đi  tối  ưu  cho dữ  liệu  đến  các  đích  khác nhau trong liên mạng, lưu và chuyển tiếp (các gói tin) dữ liệu từ mạng này sang mạng khác. 
*4. Tầng vận chuyển – Transport layer:* 
- Đảm bảo truyền tải dữ liệu giữa các quá trình. Dữ liệu gởi đi được đảm bảo không có lỗi, theo đúng trình tự, không bị mất, trùng lắp.
- Đối với các gói tin có kích thước lớn, tầng này sẽ phân chia chúng thành các  phần  nhỏ  (đoạn) trước  khi  gởi  đi,  cũng  như tập  hợp  lại  chúng  khi nhận được.
 *5. Tầng giao dịch – Session layer:* 
- Cho phép các ứng dụng thiết lập, sử dụng và xóa các kênh giao tiếp giữa chúng (được gọi là giao dịch). 
- Nó cung cấp cơ chế cho việc nhận biết tên và các chức năng về bảo mật thông tin khi truyền qua mạng. 
*6. Tầng trình bày – Presentation layer:*
-  Đảm bảo các máy tính có kiểu định dạng dữ liệu khác nhau vẫn có thể trao đổi thông tin cho nhau. Thông thường các mày tính sẽ thống nhất với nhau  về  một  kiểu  định  dạng  dữ  liệu  trung  gian  để  trao  đổi  thông  tin giữa các máy tính. 
- Dữ liệu cần gởi đi sẽ được tầng trình bày chuyển sang định dạng trung gian trước khi nó được truyền lên mạng. Ngược lại, khi nhận dữ liệu từ mạng,  tầng  trình  bày  sẽ  chuyển  dữ  liệu  sang  định  dạng  riêng  của nó. 
*7. Tầng ứng dụng – application layer:* 
- Tầng trên cùng, cung cấp các ứng dụng truy xuất đến các dịch vụ mạng. Bao gồm các ứng dụng của người dùng. 
- Người dùng mạng giao tiếp trực tiếp với tầng này • Ví  dụ:  Navigator,  Internet  Explorer  ),  các  Mail  User  Agent  (Outlook Express, Netscape Messenger, ...) hay các chương trình làm server cung cấp các dịch vụ mạng như các Web Server (Netscape Enterprise, Internet Information Service, Apache, ...), Các FTP Server, các Mail server (Send mail, MDeamon).
##II. Tổng quan về mạng LAN
###1.	Khái niệm về LAN
-	LAN (Local Area Network - Mạng may tỉnh cục bộ) là một hệ thống mạng dùng để kết nối các máy tính trong một phạm vi nhỏ (nhà ở, phòng làm việc, trường học, ...). Các máy tính trong mạng LAN có thể chia sẻ tài nguyên với nhau, mà điển hình là chia sẻ tập tin, máy in, máy quét và một số thiết bị khác.
-	Một mạng LAN tối thiều cần có máy chủ (server), các thiết bị ghép nối(Repeater, Hub, Switch, Bridge), máy tính con (client) và dây cáp (cable) để kết nối các máy tính lại với nhau. Ngày nay hầu hết máy chủ sử dụng hệ điêu hành Windows và tốc độ mạng LAN có thể lên đến 10 Mbps, 100 Mbps hay thậm chí là 1 Gbps
-	Một hình thức khác của LAN là WAN (Wide Area Network), có nghĩa là mạng diện rộng, dùng để nối các LAN lại với nhau (thông qua router).
-	Thêm một hình thức khác nữa của mạng LAN, mới xuất hiện trong những năm gần đây là WLAN( Wireless LAN) mạng LAN không dây.
###2.	Thiết bị được sử dụng trong LAN
**2.1 Card mạng – NIC (Network Interface Card)**
Card mạng – NIC là một thiết bị được cắm vào trong máy tính để cung cấp cổng kết nối vào mạng. Card mạng được coi là một thiết bị hoạt động ở lớp 2 của mình OSI. Mỗi card mạng có chứa một địa chỉ duy nhất là địa chỉ MAC – Media Access Control. Card mạng điều khiển việc kết nối của máy tính vào các phương tiện truyền dẫn trên mạng.
**2.2 Router**
Router (bộ định tuyến) là thiết bị mạng có chức năng chuyển tiếp gói dữ liệugiữa các mạng mày tính. Có thể hiểu, router thực hiện "chỉ đạo giao thông" trên hệ thống mạng. Dữ liệu được gửi đi dưới dạng gói, ví dụ như trang web hay email. Gói dữ liệu sẽ được chuyển tiếp từ router này đến router khác thông qua các mạng nhỏ, được kết nối với nhau để tạo thành mạng liên kết, cho đến khi gói dữ liệu đến được điểm đích.
Có nhiêu kiểu router, từ đơn giản đến phức tạp. Các router thông thường được dùng cho kết nối Internet gia đình, còn nhiều router có mức giá “khủng” thường là business router, được dùng trong các doanh nghiệp, tổ chức lớn. Song, cho dù đặt hay rẻ, đơn giản hay phức tạp thì mọi router đều hoạt động với các nguyên tắc cơ bản như nhau
Các phiên bản Router Cisco 1900, 2900, 3900.
**2.3 Switch**
Switch hay còn gọi là thiết bị chuyển mạch, là một thiết bị dùng để kết nối các đoạn mạng với nhau theo mô hình mạng sao. Theo mô hình này, switch đóng vai trò là thiết bị trung tâm, tất cả các máy tính đều được nối về đây.
Nói cách khác switch là thiết bị giống Bridge và Hub cộng lại nhưng thông minh hơn, hoạt động ở lớp Data Link. Có khả năng chỉ chuyển dữ liệu đến đúng kết nối thực sự cần dữ liệu này làm giảm đụng độ trên mạng và phân đoạn mạng trong các mạng cục bộ lớn (VLAN).
**2.4 Repeater**
Repeater là thiết bị khuếch đại, phục hồi các tín hiệu đã bị suy thoái do tổn thất năng lượng trong khi truyền. Thiết bị này hoạt động ở lớp Physical.
Nó cho phép mở rộng mạng vượt xa chiều dài giới hạn của một môi trường truyền và chỉ được dùng nối hai mạng có cùng giao thức truyền thông.
**2.5 Hub**
Còn được gọi là multiport repeater, nó có chức năng như Repeater nhưng mở rộng hơn với nhiều đầu cắm các đầu cáp mạng. Hub thông thường có 4,8,12 và 4 port và là trung tâm của mạng hình sao. Hub họat động ở tầng Physical Layer của mô hình OSI
Có 3 loại Hub: thụ động, chủ động, thông minh.
    + Hub thụ động (Passive Hub): chỉ đảm bảo chức năng kết nối, không xử lý lại tín hiệu.
    + Hub chủ động (Active Hub): có khả năng khuếch đại tín hiệu để chống suy hao.
    + Hub thông minh (Intelligent Hub): là Hub chủ động nhưng có thêm khả năng tạo ra các gói tin thông báo hoạt động của mình giúp cho việc quản trị mạng dễ dàng hơn.
**2.6  Bridge**
Bridge  là  thiết  bị  mạng  thuộc  lớp  2  của  mô  hình  OSI  (Data  Link  Layer) với 2 chức năng chính là lọc và chuyển vận. Bridge  được  sử  dụng  để  ghép  nối  2  mạng  để  tạo  thành  một  mạng  lớn  duy  nhất. Bridge được sử dụng phổ biến để làm cầu nối giữa hai mạng Ethernet. Dựa trên bảng địa chỉ MAC lưu trữ, Brigde kiểm tra các gói tin và xử lý chúng trước khi có quyết định chuyển đi hay không. Khi thấy một gói tin từ một máy tính thuộc mạng này chuyển tới một máy tính trên mạng khác, Bridge sẽ sao chép và gửi gói tin này tới mạng đích.
###3.	Các loại dây cáp mạng
 Dây cáp mạng là một trong những công cụ cần thiệt và có vai trò quan trọng trong mô hình hệ thống mạng. Hiện nay, có rất nhiều loại dây mạng đang được sử dụng phố biến và mỗi loại dây có những tính năng và công dụng riêng.
**3.1 Cáp xoắn đôi**
Cáp xoắn đôi gồm nhiều cặp dây đồng xoắn lại với nhau nhằm chống phát xạ nhiễu điện từ. Do giá thành thấp nên cáp xoắn được dùng rất rộng rãi. Có hai loại cáp xoắn đôi được sử dụng rộng rãi trong LAN : loại có vỏ bọc chống nhiễu (STP) và loại không có vỏ bọc chống nhiễu (UPT).
     - Cáp  xoắn  đôi  có  vỏ  bọc  chống  nhiễu  STP  (Shielded  Twisted  Pair)  : Gồm nhiều cặp xoắn được phủ bên ngoài một lớp vỏ làm bằng dây đồng bện. Lớp vỏ này có tác dụng chống EMI từ ngoài và chống phát xạ nhiễu bên trong. Lớp vỏ bọc chống nhiễu này được nối đất để thoát nhiễu. Cáp xoắn đôi có vỏ bọc ít bị tác động bởi nhiễu điện và truyền tín hiệu xa hơn cáp xoắn đôi trần.
    - Cáp UTP ( Unshielded Twisted Pair) là loại cáp mạng không có võ bọc chống nhiễu, nên còn được gọi là cáp xoắn đôi không chống nhiều. Cáp UTP được sử dụng phố biển trong các hệ thống mạng LAN. Cấu tạo của loại cáp này bao gồm 4 cặp đôi xoắn, 1 lớp vỏ bảo vệ. Nó có thể giúp người tiêu dùng đáp ứng tốt về băng thông, hơn nữa lại có giá thành tương đối rẻ phù hợp với nhiều đối tượng người sử dụng. Cáp mạng UTP có tính linh hoạt và độ bên khá cao. Cáp xoắn đôi trần sử dụng chuẩn 10 BaseT hoặc 100 BaseT. Độ dài tối đa của một đoạn cáp này khoảng 100m. Đầu nối của loại cáp này là dùng đầu RJ-45.
**3.2  Cáp đồng trục**
       Cáp đồng trục là loại cáp điện với một lõi dẫn điện được bọc lại bởi một lớp điện môi không dẫn điện, chung quanh quấn thêm một lớp bện kim loại, ngoài cùng lại có vỏ bọc cách điện.  
      Cáp đồng  trục thường dùng làm đường truyền cho  tín  hiệu  vô  tuyến. Ứng dụng của nó bao gồm các đường cấp giữa thiết bị thu phát sóng vô tuyến và ăng ten của chúng, các kết nối mạng máy tính, và làm cáp truyền hình.
**3.3	 Cáp quang**
      Cáp quang (Fiber optic cable) là những sợi dài, mảnh bằng thủy tinh rất tinh khiết có đường kính bằng một sợi tóc người. Chúng được sắp xếp theo bó gọi là cáp quang và được sử dụng để truyền tín hiệu ánh sáng qua khoảng cách xa.
   Cấu tạo dây cáp quang như sau:
       + Core - Trung tâm thủy tỉnh mỏng của sợi nơi ánh sáng đi qua
       + Cladding - Vật liệu quang học bên ngoài bao quanh lõi phản chiêu ánh sáng
          vào lõi
      + Buffer coating - Lớp phủ nhựa bảo vệ sợi khỏi hư hại và độ âm 

















