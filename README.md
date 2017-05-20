
package coladeprioridad;

import java.util.PriorityQueue;

public class ColadePrioridad{

    public static void main(String[] args) {
        // TODO code application logic here
        PriorityQueue pq = new PriorityQueue();
        System.out.println(pq.isEmpty());
        //verifica si la lista esta vacia
        pq.isEmpty();
        //agregar elementos
       
         pq.add(3);
          pq.add(14);
           pq.add(7);
            pq.add(10);
            pq.add(1);
            pq.add(6);
            pq.add(-8);
            pq.add(9);
            pq.add(5);
            
            System.out.println(pq);
            System.out.println(pq.isEmpty());
        //devuelve el nodo peek
        System.out.println(pq.peek())
        System.out.println(pq);
        //develve el nodo y lo elimina poll
        pq.poll();
        System.out.println(pq);
    }
}

