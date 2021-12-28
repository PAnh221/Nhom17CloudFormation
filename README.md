# AWS CloudFormation
##Template:
Template là bản thiết kế để xây dựng cái tài nguyên. Một template cơ bản sẽ có các thành phần:
●	Resources: các tài nguyên cơ bản
●	Metadata: cung cấp thông tin về cách triển khai các tài nguyên cụ thể
●	Parameters: là đặc tính của tài nguyên đó
●	Type: ánh xạ với các tài nguyên cần tạo
●	Properties: là đặc tính của tài nguyên đó
●	Mappings: Ánh xạ các key và các giá trị liên quan có thể sử dụng để chỉ định các giá trị tham số có điều kiện
●	Outputs:Mô tả các giá trị được trả về bất cứ khi nào cần xem các properties của stack của mình

###Các thuộc tính level cao nhất quan trọng nhất của một template CloudFormation là các Parameter và Resources. 

##Cách truyền template
Sau khi đã hoàn thành xong một cấu trúc template, vào mục Cloudformation, chọn Create stack (with new resources) -> Upload template a template file -> Chọn định dạng template là yaml hoặc json đã có.
![image](https://user-images.githubusercontent.com/74722049/147558979-9b7b6879-3d74-4b3f-8452-6a324b25760c.png)
![image](https://user-images.githubusercontent.com/74722049/147558993-4ced3df0-9523-4cb2-a604-c610b9fc8bdd.png)
![image](https://user-images.githubusercontent.com/74722049/147559004-cf4ce388-ce25-454f-b8c6-940d34bb6417.png)

Sau khi tạo template thành công thì có thể kiểm tra các thông số và tài nguyên trên Stack.  

