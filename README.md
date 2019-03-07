# maventext
这只是一个测试


package mooc;

import com.github.houbb.opencc4j.util.ZhConverterUtil;

public class ChineseTest {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		String original="声明在于运动";
		String result=ZhConverterUtil.convertToTraditional(original);
		System.out.println(result);
	}

}
package mooc;
import org.apache.commons.math3.util.ArithmeticUtils;
public class Mooc1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int a=ArithmeticUtils.gcd(361, 285);
		System.out.println(a);
	}

}
