# Array-function-
function Students() {
  const students = [
    { id: 1, name: "Vishnu" },
    { id: 2, name: "Raju" },
    { id: 3, name: "Kiran" }
  ];

  return (
    <div>
      <h2>Student List</h2>
      {students.map(student => (
        <p key={student.id}>{student.name}</p>
      ))}
    </div>
  );
}

export default Students;
