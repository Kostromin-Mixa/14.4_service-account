# 14.4 Сервис-аккаунты   
 
- Создаем сервис-аккаунт   
kubectl create serviceaccount kostromin   
- Проверяем список сервис-акаунтов   
kubectl get serviceaccounts   
kubectl get serviceaccount   

![2021-12-15_09-04-02](https://user-images.githubusercontent.com/78191008/146126044-c27eec00-cba3-4c97-9908-d925bbdf4611.png)   

- Получаем информацию в формате YAML и/или JSON   

![2021-12-15_09-06-20](https://user-images.githubusercontent.com/78191008/146126075-3e1e1871-6bcf-4bf0-b1b1-54c0713b3a8a.png)   

- Выгружаем сервис-акаунт и сохраняем его в файл   
kubectl get serviceaccount kostromin -o yaml > kostromin.yml   

- Удаляем сервис-акаунт   
kubectl delete serviceaccount kostromin

![2021-12-15_09-12-45](https://user-images.githubusercontent.com/78191008/146126124-92c6e1a0-8b7d-4bde-ab99-ce407bd664a3.png)   

- Загружаем сервис-акаунт из файла    

![2021-12-15_09-52-57](https://user-images.githubusercontent.com/78191008/146126173-7ccb5af0-690c-41fc-878c-19db6b3e04ef.png)   
