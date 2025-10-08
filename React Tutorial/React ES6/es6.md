### REACT ES6
- ES6 là viết tắt của ECMAScript 6
- Là chuẩn giúp JavaScript có quy tắc thống nhất


## Arrow Function
- Hàm mũi tên giúp viết hàm ngắn gọn và dễ đọc hơn so với cách viết truyền thống !

- Cách viết truyền thống:

 hello = function() {
  return "Hello World!";        
}


- Arrow Function

hello = () => {
    return "Hello Wolrd!";
}

- Arrow Function rút gợn hơn

hello = () => "Hello World!";    # Nếu chỉ return 1 giá trị thì có thể bỏ '{ }' và 'return'

- Arrow Function với Parameter
hello = (val) => "Hello" + val;

## Variables

- var: function scope

- let: block scope

- const: block scope, thường dùng để gán cho components, state, props

Block scope là cặp dấu { }

## JavaScript Array map()
# map() trong JS
- map() là phương thức của mảng, duyệt qua từng phần tử của mảng rồi trả về một mảng mới

# map() trong React
-  Dùng để render danh sách phần tử

const fruitlist = ['apple', 'banana', 'cherry'];

function MyList() {
  return (
    <ul>
      {fruitlist.map(fruit =>
        <li key={fruit}>{fruit}</li>
      )}
    </ul>
  );
}

Output: 
- apple
- banana
- cherry



